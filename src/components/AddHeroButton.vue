<script>
export default {
    name: "add-hero-button",
    props: {
        text: String,
    }
}
</script>

<template>
    <a class="f6 link dim br-pill ph3 pv2 mb2 dib white bg-black" href="#0" @click="$emit('add-hero', true)">{{ text }}</a>
</template>