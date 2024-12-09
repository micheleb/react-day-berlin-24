<script lang="ts">
	import { onMount } from "svelte";
	import Fragment from './fragment.svelte';
	import Reveal from 'reveal.js';
  import Slide from './slide.svelte';

  export let deck: Reveal.Api;

  onMount(() => {
    if (deck) {
      deck.on('fragmentshown', (event) => {
        const { fragment } = event as unknown as {fragment: Element};

        console.log("fragment", fragment);

        // Remove previous "focused" and add "grayed-out"
        const previous = document.querySelector('.row.current-fragment');
        if (previous) {
          previous.classList.add('grayed-out');
        }

        setTimeout(() => {
        // Scroll to keep the focused fragment centered
        fragment.scrollIntoView({ behavior: 'smooth', block: 'center' });
        }, 0);
      });
    }
  })
</script>

<Slide animate>
	<Fragment>But distribution</Fragment>
	<Fragment>But OTA updates</Fragment>
	<Fragment>But multiplatform</Fragment>
	<Fragment>But form factors</Fragment>
	<Fragment>But localization</Fragment>
	<Fragment>But authentication</Fragment>
	<Fragment>But dark mode</Fragment>
	<Fragment>But pipelines</Fragment>
	<Fragment>But analytics</Fragment>
	<Fragment>But monetization?</Fragment>
	<Fragment>But SEO?</Fragment>
	<Fragment>But competition?</Fragment>
</Slide>
