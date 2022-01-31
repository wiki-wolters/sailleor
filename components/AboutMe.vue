<template>
    <page-block>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
          <div>
            <img src="../assets/images/astrid-profile.jpg" />
          </div>
          <div class="col-span-2">
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus vitae mattis nibh, eu aliquet magna. Vivamus tincidunt cursus elementum. Nunc fringilla vitae est ut tempus. Ut ullamcorper tempor tristique. Nullam pharetra mauris id felis sodales efficitur. Proin nisl tellus, aliquet vel molestie eu, vulputate eget justo. Aenean quis tincidunt erat, vel tempus sapien. Nullam feugiat, risus eget dapibus porttitor, sem ante venenatis tortor, a gravida dolor nunc ut nibh. Aliquam lectus felis, porta rhoncus ex et, interdum pellentesque dolor. Vivamus vulputate aliquet viverra. Nullam sit amet vehicula ligula. Suspendisse a dolor sem. Aliquam dapibus odio in facilisis eleifend.</p>
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
