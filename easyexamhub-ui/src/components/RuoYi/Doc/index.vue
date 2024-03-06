<template>
  <div>
    <svg-icon icon-class="question" @click="goto" />
  </div>
</template>

<script>
export default {
  name: 'EasyExamHubDoc',
  data() {
    return {
      url: 'http://doc.easyexamhub.vip/easyexamhub-vue'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
