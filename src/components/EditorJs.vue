<template>
  <div id="editorjs" class="prose mx-auto"></div>
</template>

<script>
import Editorjs from "@editorjs/editorjs";
import Header from "@editorjs/header";
import Embed from "@editorjs/embed";
export default {
  name: "EditorJs",
  data() {},
  mounted() {
    new Editorjs({
      holder: "editorjs",
      tools: {
        header: Header,
        embed: Embed,
      },
    });
  },
};
</script>
