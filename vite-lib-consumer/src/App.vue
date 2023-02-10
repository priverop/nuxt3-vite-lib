<script setup>
import {
  AstoreButton,
  HelloWorld,
  LibraryComponent,
} from "@prp-astara/vite-vue3-test-lib";
</script>
<template>
  <div>
    <h1>Vite 4 app</h1>

    <LibraryComponent> LibraryComponent </LibraryComponent>
    <AstoreButton> AstoreButton </AstoreButton>
    <HelloWorld msg="Astara Store" />
  </div>
</template>
