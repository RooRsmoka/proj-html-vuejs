<template>
    <header>
        <img src="/img/finance_logo_1x.png">
        <div class="nav-bar">
            <div class="link" v-for="link in nav" :key="link.id">
                <a :href="link.url">
                    {{link.label}}
                </a>
            </div>
            <div>contact</div>
            <div>+</div>
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
header {
    display: flex;
    justify-content: space-between;

    img {

    }

    .nav-bar {
        display: flex;

        .link {

            &:hover {
                background-color: #f6f7f7;
            }
            a {
                text-transform: uppercase;
                text-decoration: none;
                color: #949494;
                margin: 0 10px;

                &:hover {
                    color: #1a3154;
                }
            }
        }
    }
}
</style>