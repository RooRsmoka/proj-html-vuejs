<template>
    <div class="feedback">
        <div class="title">
            <h1>Client Feedback</h1>
            <div class="spacer"></div>
        </div>
        <div class="feedback-list">
            <div class="client-feedback">
                <img src="/img/client-logo-4.png" alt="">
                <p>"Avada Finance offers a fantastic service! it is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it."</p>
                <p>andre mendoza</p>
                <p>creative market</p>
            </div>
            <div class="client-feedback">
                <img src="/img/client-logo-1-1.png" alt="">
                <p>"Avada Finance offers a fantastic service! it is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it."</p>
            </div>
            <div class="client-feedback">
                <img src="/img/client-logo-2.png" alt="">
                <p>"Avada Finance offers a fantastic service! it is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it."</p>
            </div>
            <div class="client-feedback">
                <img src="/img/client-logo-3.png" alt="">
                <p>"Avada Finance offers a fantastic service! it is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it."</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.feedback {
    display: flex;
    flex-direction: column;
    align-items: center;

    .title {
        display: flex;
        flex-direction: column;
        width: 100%;
        background-color: #f6f7f7;
        padding: 50px;
        text-align: center;

        .spacer {
            align-self: center;
        }
    }

    .feedback-list {
        display: flex;
        background-color: #fff;

        .client-feedback {
        }
    }
}
</style>