<script>
    import CallToAction from "../components/CallToAction.svelte";
    import MainSlider from "../components/MainSlider.svelte";
</script>

<main>
    <div class="wrapper">
        <div class="mainSlider">
            <MainSlider />
        </div>

        <br />
        <div class="cta">
            <CallToAction />
        </div>
    </div>
</main>

<style>
    main {
        min-height: 100em;
        background: rgb(233, 233, 233);
    }
</style>
