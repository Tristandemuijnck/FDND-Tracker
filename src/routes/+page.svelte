<script>
    import Heading from "../lib/components/landing/Heading.svelte";
    import Notitie from "../lib/components/landing/Notitie.svelte";
    import Progress from "../lib/components/landing/Progress.svelte";
    import Recent from "../lib/components/landing/Recent.svelte";
    import MobileNav from "../lib/components/landing/general/MobileNav.svelte";
</script>

<Heading />

<Notitie />

<Progress />

<h2>Recente notities</h2>

<Recent />

<MobileNav />

<style>
    h2{
        font-size: 1rem;
        font-family: 'Inter SemiBold';
        margin-left: 5%;
    }
</style>
