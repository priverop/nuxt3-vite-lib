<script setup>
import { AstoreButton, HelloWorld, LibraryComponent } from "./index.js";
</script>
<template>
  <div>
    <h1>Minimal component library</h1>
    <LibraryComponent> LibraryComponent </LibraryComponent>
    <AstoreButton> AstoreButton </AstoreButton>
    <HelloWorld msg="Astara Store" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
