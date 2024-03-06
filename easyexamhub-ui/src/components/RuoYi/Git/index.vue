<template>
  <div>
    <svg-icon icon-class="github" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'EasyExamHubGit',
  data() {
    return {
      url: 'https://gitee.com/y_project/EasyExamHub-Vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
