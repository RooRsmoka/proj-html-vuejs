<template>
    <div class="container">
        <div class="finance">
            <div class="text">
                <h1>Cloud Based Finance</h1>
                <div class="spacer"></div>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do tempor incididunt ut labore et dolore magna aliqua.</p>
                <p>Laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
                <button>learn more</button>
            </div>
            <div class="graph">
                <img src="/img/graph.jpg" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.finance {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px 0;

    .text {
        width: 50%;

        h1 {
            color: #19191f;
        }

        p {
            color: #949494;
            margin: 20px 0;
        }

        button {
            margin: 10px 0;
        }
    }

    .graph {
        width: 50%;

        img {
            width: 100%;
        }
    }
}
</style>