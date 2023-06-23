<template>
  <div></div>
</template>

<script>
export default {
  mounted() {
    this.openPdf()
  },
  methods: {
    openPdf() {
      const file = this.$route.params.file
      const pdfUrl = '/os-cinco-niveis-de-apego' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
