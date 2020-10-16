<template>
  <div id="app" class="app">
    <wl-form-designer class="ft-form-designer">
      <template slot="title-left">
        <span class="form-designer-back" @click="handleBack">
          <i class="el-icon-arrow-left"></i>
        </span>
        <span>请假</span>
      </template>
    </wl-form-designer>
  </div>
</template>

<script>
export default {
  name: "app",
  methods: {
    handleBack() {},
  },
};
</script>

<style>
html,
body,
.app {
  height: 100%;
}
</style>
