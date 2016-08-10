<template>
  <div id="app">
    <left-bar></left-bar>
    <note-list></note-list>
    <note-view></note-view>
  </div>
</template>

<script>
import 'whatwg-fetch'
import LeftBar from './components/leftBar'
import NoteView from './components/noteView'
import NoteList from './components/noteList'

export default {
  components: {
    'left-bar': LeftBar,
    'note-view': NoteView,
    'note-list': NoteList
  }
}
</script>

<style>
html {
  height: 100%;
}

body {
  height: 100%;
}

#app {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
  display: flex;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
