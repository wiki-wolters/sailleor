<template>
    <page-block>
        <div class="grid grid-cols-1 md:grid-cols-3 md:gap-10">
          <div class="col-span-2">
            <h2>About Me</h2>

            <p>I graduated from Auckland University of Technology in 2021 after five years of study with a Bachelor of Health Science in Podiatry, and a Diploma in Applied Science. While in my second year of study, I had been searching for the right dance school for my child, as I was aware that her desire for ballet and dancing would lead to pointe work in the not too distant future. This concerned me from a medical perspective, as how would I know when she was physically ready? Do I just take the teacher’s word she is ready? What about the changes to her joints and bones? She seemed so small and flexible, and surely that meant injuries and bunions at an early age!</p>
            <p>After time spent researching safe pointe practice, at the end of 2020, I was able to meet and join forces with Esther Juon and her team, who have developed a customised program and teaching platform for safe pointe work and fitting.</p>
            <p>During 2021, I undertook her Bronze Standard fitting course, finishing at the beginning of 2022.</p>
            <p>I am dedicated to ensuring the health of dancers of all ages and stages. This service includes medical referrals, exercise rehabilitation and strengthening, referrals to Esther Juon for her tailored dancer mentorship program, and podiatric advice.</p>
          </div>
          <div>
            <img src="~/assets/images/splits.jpg" />
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
