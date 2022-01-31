<template>
    <page-block class="contact">
        <h2>Get in touch</h2>
        <p><strong>Phone:</strong> 021 055 5563</p>
        <p><strong>Address:</strong> 2/70 Glamorgan Drive, Torbay 0630, Auckland, NEW ZEALAND</p>
    </page-block>
</template>

<script>
import { defineComponent } from '@vue/composition-api'
import PageBlock from './PageBlock.vue'

export default defineComponent({
  components: { PageBlock },
})
</script>

<style scoped>
.contact {
    background: rgb(255,209,190);
    background: linear-gradient(342deg, rgba(255,209,190,1) 0%, rgba(255,235,215,1) 61%, rgba(255,249,244,1) 100%);
}
</style>
