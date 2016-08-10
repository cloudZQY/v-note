<template>
  <div class="note-view">
    <div class="edit-box">
      <div class="edit-head">
      </div>
      <div class="edit-body">
        <div class="note-title-box">
          <input type="text" id="note-title" v-model="title">
        </div>
        <div class="note-content-box">
          <textarea name="note-content" id="note-content" v-model="content" cols="30" rows="10"></textarea>
        </div>
        <button id="post-note" @click="postNote">完成</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: '',
      content: ''
    }
  },
  methods: {
    postNote: function () {
      console.log(this.title)
      fetch('api/addNote').then(res => {
        console.log(res)
      })
    }
  }
}
</script>

<style scoped>
.note-view {
  flex: 1;
}
</style>
