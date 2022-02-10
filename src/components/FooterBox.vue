<template>
    <footer>
        <div class="top-footer">
            <div class="footer-logo">
                <img src="/img/finance_logo_footer.png" alt="">
            </div>
            <div class="recent-posts">
                <h3>recent posts</h3>
                <a :href="post.url" v-for="post in recentPosts" :key="post.id">
                    <i class="fas fa-angle-right"></i>{{post.postTitle}}
                </a>
            </div>
            <div class="services">
                <h3>services</h3>
                <a :href="service.url" v-for="service in servicesList" :key="service.id">
                    <i class="fas fa-angle-right"></i>{{service.serviceTitle.toUpperCase()}}
                </a>
            </div>
            <div class="latest">
                <h3>latest</h3>
                <i class="fab fa-twitter"></i>
            </div>
        </div>
        <div class="bot-footer">
            <div class="rights">
                <p>
                    <i class="far fa-copyright"></i>
                    Copyright 2012-2020 | Avada Theme by Theme Fusion | All Rights Reserved | Powered by WordPress
                </p>
            </div>
            <div class="social-icons">
                <div class="icon">
                    <i class="fab fa-facebook-f"></i>
                </div>
                <div class="icon">
                    <i class="fab fa-twitter"></i>
                </div>
                <div class="icon">
                    <i class="fab fa-youtube"></i>
                </div>
                <div class="icon">
                    <i class="fab fa-instagram"></i>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    props: {
        recentPosts: Array,
        servicesList: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/footerBox.scss';
</style>

