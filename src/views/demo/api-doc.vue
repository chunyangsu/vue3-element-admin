<!-- 接口文档 -->
<template>
  <div class="app-container">
    <iframe
      src="https://www.apifox.cn/apidoc/shared-195e783f-4d85-4235-a038-eec696de4ea5"
      width="100%"
      height="100%"
      frameborder="0"
    ></iframe>
  </div>
</template>

<style lang="scss" scoped>
.app-container {
  display: flex;
  flex-direction: column;

  /* 84 = navbar + tags-view = 50 + 34 */
  height: calc(100vh - 50px);
}

.hasTagsView {
  .app-container {
    height: calc(100vh - 84px);
  }
}
</style>
