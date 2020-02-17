<template>                                  <!--定义nav-tabs-card全局组件，主要用于Dashboard-->
  <md-card class="md-card-nav-tabs">
    <md-card-content>
      <slot name="content"></slot>          <!--预留内容位-->
    </md-card-content>
  </md-card>
</template>

<script>
export default {
  name: "nav-tabs-card"
};
</script>
