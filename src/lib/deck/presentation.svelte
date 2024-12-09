<script lang="ts">
	import Reveal from 'reveal.js';
	import Code from './code.svelte';
	import Fragment from './fragment.svelte';
	import Markdown from './markdown.svelte';
	import Notes from './notes.svelte';
	import Slide from './slide.svelte';
</script>

<Slide backgroundImage="title-bg.jpg">
	<h1><span id="mainTitle">Build things that don't scale at all</span></h1>
</Slide>

<Slide animate>
	<p class="r-fix-text">I wish I had an app that...</p>
</Slide>

<!-- {#if deck}
<OneByOne deck={deck} />
{/if} -->

<Slide animate>
	<Fragment animation="fade-in-then-semi-out">But Distribution</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Authentication</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Multiplatform</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Form Factors</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Dark Mode</Fragment>
</Slide>

<Slide animate>
	<Slide animate>
		<Fragment animation="fade-in-then-semi-out">But Analytics</Fragment>
		<Fragment animation="fade-in-then-semi-out">But Monetization</Fragment>
		<Fragment animation="fade-in-then-semi-out">But SEO</Fragment>
		<Fragment animation="fade-in-then-semi-out">But Localization</Fragment>
		<Fragment animation="fade-in-then-semi-out">But Competition</Fragment>
		<Fragment animation="fade-in-then-semi-out">But CI</Fragment>
		<Fragment animation="fade-in-then-semi-out">But OTA Updates</Fragment>
	</Slide>
</Slide>

<Slide>

</Slide>

<Slide animate>
	<p>First</p>
	<p>Slide!</p>
	<p>With <a href="https://github.com" target="_blank">links</a>!</p>
</Slide>

<Slide animate>
	<p>First</p>
	<p>Slide!</p>
	<p>With <a href="https://github.com" target="_blank">links</a>!</p>
	<p>Press <span class="font-mono bg-slate-200 text-indigo-900 px-2 py-1">s</span> for Speaker Notes</p>
	<Notes>Here are some speaker notes, too</Notes>
</Slide>

<Slide animate>
	<Fragment animation="highlight-current-blue"><p>fragments</p></Fragment>
	<Fragment animation="fade-in-then-semi-out"><p>are also</p></Fragment>
	<Fragment animation="fade-in-then-out"><p>supported</p></Fragment>
	<Fragment animation="fade-right"><p>with animations, too</p></Fragment>
</Slide>

<Slide>
	<Slide animate>
		<h3>Vertical slides</h3>
	</Slide>

	<Slide animate>
		<h3>Vertical slides</h3>
		<p>Nest your slides</p>
	</Slide>

	<Slide animate>
		<h3>Vertical slides</h3>
		<p>Nest your slides</p>
		<p>And you can navigate vertically</p>
	</Slide>
</Slide>

<Markdown>
	{`
# Markdown Slide
- This is another slide
- and it's written in Markdown!

---

# Another Markdown Slide
- You can create multiple slides at once!
	`}
</Markdown>

<Markdown external name="external-example.md" />

<Slide animate>
	<Code id="code" lines="|2">
		{`
		const myFunction = (message: string) => {
			console.log(message);
		}
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="|3">
		{`
		const myFunction = (message: string) => {
			console.log(message);
			console.log("done!");
		}
		`}
	</Code>
</Slide>