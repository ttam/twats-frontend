<template>
    <header>
        <h1 class="reveal">
            <strong>tw</strong><span>itter st</span><strong>ats</strong>.
        </h1>
        <p>Coming soon.</p>
    </header>
</template>

<script>

</script>

<style lang="scss" scoped>
    @keyframes reveal {
        to {
            max-width: 3.2em;
        }
    }

    header {
        color: #ddf;
        font-family: 'Montserrat', sans-serif;

        p {
            color: rgba(255, 255, 255, 0.7);
            font-size: 1.25rem;
            height: 3rem;
        }
    }

    h1 {
        font-size: 4.5rem;
        font-weight: 700;

        strong, span {
            display: block;
            float: left;
            overflow: hidden;
        }

        span {
            white-space: pre;
            font-weight: 100;
            max-width: 0;
            animation: reveal 500ms forwards linear;
            animation-delay: 1200ms;
        }
    }
</style>
