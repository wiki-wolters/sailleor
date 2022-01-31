<template>
    <section :style="style" :class="classes">
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
        },
        classes() {
            return {
                [this.class]: true,
                ['p-5']: true,
                ['md:p-10']: true
            }
        }
    }
})
</script>

<style scoped>
    section {
        text-align: center;
    }
    .page-block__inner {
        max-width: 1024px;
        margin: 0 auto;
        text-align: left;
    }
</style>
