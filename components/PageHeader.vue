<template>
    <page-block class="page-header">
      <h1>Sailleor Dance Co.</h1>
      <p>English: occupational name for a dancer<br />
          or acrobat, from Old French sailleor<br />
          'dancer', 'leaper'.</p>
    </page-block>
</template>

<script>
import { defineComponent } from '@vue/composition-api'
import PageBlock from "./PageBlock.vue";

export default defineComponent({
    components: {
        PageBlock
    }
})
</script>

<style scoped>
h1 {
    margin: 0 0 20px 0;
    color: #fff;
}
p {
    color: #fff;
    font-style: italic;
}
.page-header {
    background: rgb(4,59,18);
    background: linear-gradient(342deg, rgba(4,59,18,1) 0%, rgba(6,84,26,1) 61%, rgba(13,124,41,1) 100%);
}
</style>
