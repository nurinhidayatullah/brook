<template>
    <div class="main-container">
        <div class="container mt--150 pb--150">
            <h5>Lihat B2C:</h5>
            <nuxt-link class="btn btn-danger w-100 btn-lg" to="/b2c">B2C</nuxt-link>
            <h5 class="mt-5">Lihat B2B:</h5>
            <nuxt-link class="btn btn-danger w-100 btn-lg" to="/b2b">B2B</nuxt-link>
        </div>
        <Footer />
    </div>
</template>

<script>
    import Footer from "@/components/Footer"

    export default {
        components: {
            Footer,
        },

        data() {
            return {
                navOpen: false,
                searchOpen: false
            }
        },

        mounted () {
            document.body.classList.add('template-color-1', 'template-font-2')
        },
        unmounted () {
            document.body.classList.remove('template-color-1', 'template-font-2')
        }
    };
</script>