<template>
    <div class="services">
        <h1>Specialty Services</h1>
        <div class="spacer"></div>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do tempor incididunt ut labore et dolore magna aliqua.</p>
        <p>Laboris nisi ut aliquip ex ea commodo consequat.</p>
        <div class="container">
            <div class="services-cards">
                <div class="card">
                    <h2>Small Business Loans</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt it labore et dolore magna aliqua.</p>
                    <div class="info">Learn More</div>
                </div>
                <div class="card">
                    <h2>Credit Rating Advice</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt it labore et dolore magna aliqua.</p>
                    <div class="info">Learn More</div>
                </div>
                <div class="card">
                    <h2>Fast Crowd Funding</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt it labore et dolore magna aliqua.</p>
                    <div class="info">Learn More</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.services {
    background-color: #f6f7f7;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding: 50px 0;

    p {
        color: #949494;
    }

    .services-cards {
        margin-top: 100px;
        display: flex;

        .card {
            position: relative;
            background-color: #fff;
            width: calc((100% / 3) - 20px);
            text-align: center;
            margin: 0 10px;
            padding: 30px 0;

            h2 {
                margin-bottom: 20px;
            }

            p {
                padding: 0 30px;
                margin-bottom: 50px;
            }

            .info {
                position: absolute;
                bottom: 0;
                width: 100%;
                padding: 10px 0;
                background-color: #58d6cb;
                color: #fff;
                cursor: pointer;
            }
        }
    }
}
</style>