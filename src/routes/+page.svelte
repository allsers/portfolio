<script lang="ts">

    import { onMount } from 'svelte';
    import { goto } from '$app/navigation';
    import HeroSection from './en/HeroSection.svelte';

    onMount(() => {
        goto('/en')
    });
</script>

<svelte:head>   
    <title>Redirecting..</title>
    <meta name="description" content="Aleksander's portfolio website with view over projects."/>
</svelte:head>

<HeroSection />

