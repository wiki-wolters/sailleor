<template>
    <page-block>
        <div class="grid grid-cols-1 md:grid-cols-3 md:gap-10">
          <div>
            <img src="~/assets/images/astrid-profile.jpg" />
          </div>
          <div class="col-span-2">
            <h2>Hi there! I'm Astrid</h2>
            <p>I'm an Auckland-based podiatrist and a Grishko custom pointe shoe fitter.</p>
            <p><strong><em>I'm a passionate advocate for keeping young dancers safe as they progress through their dancing careers. I'm all about safe dance practice, ensuring that dancers only progress into pointe work when they have built up the necessary muscle strength in their feet, learnt how to tape their feet correctly, and have the required core strength to be able to dance en pointe.</em></strong></p> 
            <p><strong><em>As a medical professional, and parent of a dancing child, you can rest assured that your dancer is receiving the same care, muscle strengthening exercises, pre-pointe &amp; pointe assessments, and fitting process, that my daughter is receiving.</em></strong></p>
          </div>
        </div>
    </page-block>
</template>

<script>
import { defineComponent } from '@vue/composition-api'
import PageBlock from './PageBlock.vue'

export default defineComponent({
  components: { PageBlock },
    
})
</script>
