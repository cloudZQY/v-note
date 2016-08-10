<template>
  <div class="left-bar">
    <div id="new-note-btn" class="left-bar-btn">
      <i class="iconfont icon-jia"></i>
    </div>
    <div id="search-note-btn" class="left-bar-btn">
      <i class="iconfont icon-sousuo"></i>
    </div>
    <div id="shortcut-btn" class="left-bar-btn">
      <i class="iconfont icon-xingxing"></i>
    </div>
    <div id="my-notes-btn" class="left-bar-btn">
      <i class="iconfont icon-biji1"></i>
    </div>
    <div id="notebook-btn" class="left-bar-btn">
      <i class="iconfont icon-biji"></i>
    </div>
    <div id="tags-btn" class="left-bar-btn">
      <i class="iconfont icon-iconfontmoban"></i>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<style scoped>
.left-bar {
  width: 80px;
  height: 100%;
  background-color: #f8f8f8;
}
.left-bar-btn {
  width: 36px;
  height: 36px;
  color: #fff;
  border-radius: 50%;
  text-align: center;
  border: 1px solid #ccc;
  cursor: pointer;
  margin-left: 20px;
  margin-top: 40px;
}
.left-bar-btn .iconfont {
  font-size: 24px;
  color: #5cb85c;
  display: inline-block;
}
.left-bar-btn:hover {
  background-color: #5cb85c;;
}
.left-bar-btn:hover .iconfont {
  color: #fff;
}

.icon-xingxing {margin-top: 2px;}
.icon-jia {margin-top: 5px;}
.icon-sousuo {margin-top: 4px;}
.icon-biji {margin-top: 5px;}
.icon-biji1 {margin-top: 4px;}
.icon-iconfontmoban {margin-top: 2px;}
.icon-yonghu {margin-top: 2px;}
</style>
