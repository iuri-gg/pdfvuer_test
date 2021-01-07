<template>
  <div id="app">
    HI
    <pdf src="./static/relativity.pdf"/>
  </div>
</template>

<script>
import pdfvuer from 'pdfvuer'

export default {
  components: {
    pdf: pdfvuer
  }
}
</script>

<style>
</style>
