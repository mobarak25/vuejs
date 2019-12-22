<template>
    <div class="">
        <Header />
        <section class="site-content">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-2 pl-0">
                        <div class="sidebar">
                            <Sidebar />
                        </div>
                    </div>
                    <div class="col-lg-10">
                        <div class="home">
                            <router-view/>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        
        
        <Footer />
    </div>
</template>

<script>
    import Header from '@/components/Header.vue'
    import Footer from '@/components/Footer.vue'
    import Sidebar from '@/components/Sidebar.vue'

    export default {
        name: '',
        components: {
            Header,
            Footer,
            Sidebar
        }
    }
</script>

<style>

</style>
