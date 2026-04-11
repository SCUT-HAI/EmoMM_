<script>
import Title from './sections/Title.vue'
import Abstract from './sections/Abstract.vue'
import Markdown from './sections/Markdown.vue'
import BibTeX from './sections/BibTeX.vue'
import Overview from './sections/Overview.vue'
import Benchmark from './sections/Benchmark.vue'

export default {
  components: {
    Title,
    Abstract,
    BibTeX,
    Overview,
    Benchmark,
  }
}
</script>

<template>
  <Title/>
  <Abstract/>
  <Overview/>
  <Benchmark/>
  <BibTeX/>
</template>
