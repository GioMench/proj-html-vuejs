<script>
export default {
    name: 'LinksHeaderApp.vue',
    props: {
        info: String
    }
}
</script>

<template>

    <li class="px-2 ">
        <a class="text_accent text-capitalize" href="#" v-if="info === 'home'">{{ info }}</a>

        <a class="text-light text-capitalize" href="#" v-else>{{ info }}</a>
    </li>
</template>