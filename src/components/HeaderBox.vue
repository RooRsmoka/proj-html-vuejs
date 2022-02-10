<template>
    <header>
        <img src="/img/finance_logo_1x.png">
        <div class="nav-bar">
            <div class="link" v-for="link in nav" :key="link.id">
                <a :href="link.url">
                    {{link.label}}
                </a>
            </div>
            <button>contact</button>
            <div class="plus">+</div>
        </div>
    </header>
</template>

<script>
export default {
    props: {
        nav: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/headerBox.scss';
</style>