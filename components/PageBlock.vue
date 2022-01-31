<template>
    <section :style="style" :class="class">
        <div class="page-block__inner">
            <slot />
        </div>
    </section>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
    props: {
        backgroundColor: {
            type: String,
            required: false,
            default: 'transparent'
        },
        class: {
            type: String,
            required: false,
            default: ''
        }
    },

    computed: {
        style() {
            const style = {};

            if (this.backgroundColor) {
                style.backgroundColor = this.backgroundColor;
            }

            return style;
        }
    }
})
</script>

<style scoped>
    section {
        padding: 40px;
        text-align: center;
    }
    .page-block__inner {
        max-width: 1024px;
        margin: 0 auto;
        text-align: left;
    }
</style>
