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
header {
    height: 60px;
    padding: 0 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;


    img {
        height: 60%;
        cursor: pointer;
    }

    .nav-bar {
        display: flex;
        line-height: 60px;

        .link {

            &:hover {
                background-color: #f6f7f7;
            }
            
            a {
                text-transform: uppercase;
                text-decoration: none;
                color: #949494;
                margin: 0 20px;

                &:hover {
                    color: #1a3154;
                }
            }
        }

        button {
            align-self: center;
            margin: 0 40px;
        }

        .plus {
            color: #949494;
            cursor: pointer;
        }
    }
}
</style>