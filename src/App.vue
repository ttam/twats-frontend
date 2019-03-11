<template>
    <div id="app">
        <div id="container">
            <Header/>
        </div>
        <Footer/>
    </div>
</template>

<script>
    import Header from './components/Header.vue';
    import Footer from './components/Footer.vue';

    export default {
        name: 'app',
        components: {
            Header,
            Footer
        }
    }
</script>

<style>
    html, body, h1, p {
        margin: 0;
    }

    p {
        line-height: 1.6em;
    }

    html {
        /** "Diamond Upholstery" from https://www.transparenttextures.com/ */
        background: #008ca6 url(./assets/bg.png) fixed center center;
        font-size: 10px;
        height: 100%;
    }

    @media (min-width: 768px) {
        html {
            font-size: 13px;
        }
    }

    @media (min-width: 992px) {
        html {
            font-size: 16px;
        }
    }

    @media (min-width: 1200px) {
        html {
            font-size: 20px;
        }
    }

    body {
        height: 100%;
        text-align: center;
    }

    #app {
        height: 100%;
    }

    #container {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        min-height: 100%;
    }
</style>
