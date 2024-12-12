<script lang="ts">
	import Fragment from './fragment.svelte';
	import Notes from './notes.svelte';
	import Slide from './slide.svelte';
</script>

<Slide backgroundImage="title-bg.jpg">
	<h1><span id="mainTitle">Build things that don't scale at all</span></h1>
</Slide>

<Slide animate>
	<p class="r-fix-text">I wish I had an app that...</p>
</Slide>

<Slide>
	<div class="flex content-start justify-center">
		<video class="object-contain h-svh" data-autoplay src="app-store.mp4"><track kind="captions" /></video>
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="choose-one.webp" class="cover" alt="Choose one meme" />
	</div>
</Slide>


<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="ATTF.png" class="cover" alt="iOS ATTF dialog" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="Notifications.png" class="cover" alt="iOS Push Notifications dialog" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="Camera.png" class="cover" alt="iOS Camera dialog" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="Location.png" class="cover" alt="iOS Location dialog" />
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="onboarding1.png" class="cover" alt="fake onboarding dialog" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="onboarding2.png" class="cover" alt="fake onboarding dialog" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="onboarding3.png" class="cover" alt="fake onboarding dialog" />
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="paywall.png" class="cover" alt="fake paywall" />
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="ben.webp" class="cover" alt="Ben Affleck Smoking meme" />
	</div>
</Slide>
<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="ben-gdpr.webp" class="cover" alt="Ben Affleck Smoking meme, with a GDPR dialog on top" />
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center h-dvh">
		<img data-src="bender.jpg" class="cover" alt="Bender I'll make my own meme" />
	</div>
</Slide>
<!-- {#if deck}
<OneByOne deck={deck} />
{/if} -->

<Slide animate>
	<Fragment animation="fade-in-then-semi-out">But Distribution 🤦‍♂️</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Authentication 😵</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Multiplatform 🫠</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Form Factors 😶</Fragment>
	<Fragment animation="fade-in-then-semi-out">But Dark Mode 🙃</Fragment>
</Slide>

<Slide animate>
	<Slide animate>
		<Fragment animation="fade-in-then-semi-out">Analytics 📈</Fragment>
		<Fragment animation="fade-in-then-semi-out">Monetization 🤑</Fragment>
		<Fragment animation="fade-in-then-semi-out">SEO️ ‍🏴‍☠️</Fragment>
		<Fragment animation="fade-in-then-semi-out">Localization 🌍</Fragment>
		<Fragment animation="fade-in-then-semi-out">Competition 🥊</Fragment>
		<Fragment animation="fade-in-then-semi-out">CI️️ 🏗️</Fragment>
		<Fragment animation="fade-in-then-semi-out">OTA Updates 🤯️</Fragment>
	</Slide>
</Slide>

<Slide>
	<div class="flex content-center justify-center">
		<img src="imaginary-scale.png" alt="O RLY book cover" />
	</div>
</Slide>

<Slide>
	<Notes>Sorry for reusing pic. Recently joined Zattoo as Principal, so my job is to actually care about all of that.</Notes>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="whoami.png" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>It's-a me!</h3>
			<Slide animate>
				<Fragment animation="fade-in-then-semi-out">Full-Stack Dev</Fragment>
				<Fragment animation="fade-in-then-semi-out">Working with RN on 📺 @Zattoo</Fragment>
				<Fragment animation="fade-in-then-semi-out">Opinions are my very own</Fragment>
			</Slide>
		</div>
	</div>
</Slide>

<Slide>
	<h1>Examples</h1>
</Slide>

<Slide animate>
	<Notes>It took me one day</Notes>
	<div class="flex content-center justify-center">
		<img src="shottino0.png" alt="shottino showcase"/>
	</div>
</Slide>

<Slide animate>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino0.png" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
		</div>
	</div>
</Slide>

<Slide animate>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino0.png" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
		</div>
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino1.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
		</div>
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino2.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
		</div>
	</div>
</Slide>

<Slide>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino3.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
		</div>
	</div>
</Slide>

<Slide animate>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino4.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
		</div>
	</div>
</Slide>

<Slide animate>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino4.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Shottino</h3>
			<p>📷 Auto-crops Screenshots</p>
			<p>🚀 Streamlines Sharing</p>
		</div>
	</div>
</Slide>

<Slide>
	<Notes>Still works, but Bluesky fixed the issue. Plug via USB, update.</Notes>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="shottino4.jpeg" alt="shottino showcase"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Features</h3>
			<Slide animate>
				<Fragment animation="fade-in-then-semi-out">1 Platform <img class="inline" src="android.svg" width="36" alt="Android logo"/></Fragment>
				<Fragment animation="fade-in-then-semi-out">1 Form Factor 📱</Fragment>
				<Fragment animation="fade-in-then-semi-out">1 User 🧔🏼‍♂️</Fragment>
				<Fragment animation="fade-in-then-semi-out">1 Locale 🇮🇹</Fragment>
				<Fragment animation="fade-in-then-semi-out">No Auth 🫥</Fragment>
				<Fragment animation="fade-in-then-semi-out">RN Cli 💻</Fragment>
			</Slide>
		</div>
	</div>
</Slide>

<Slide animate>
	<Notes>Designed for iPads, no WhatsApp, there's a lib for that (gifted chat)</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp, there's a lib for that (gifted chat)</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp, there's a lib for that (gifted chat)</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Designed for iPads, no WhatsApp, there's a lib for that (gifted chat)</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-chat.jpeg" class="ipad" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp, there's a lib for that (gifted chat)</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp</Notes>
	<div class="flex content-center justify-center">
		<img src="caminora-splash.png" alt="CamiNora splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Designed for iPads, no WhatsApp</Notes>
	<div class="flex content-center justify-center">
		<img src="timesup.png" alt="Time's up dialog"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp</Notes>
	<div class="flex content-center justify-center">
		<img src="timesup1.png" alt="Time's up dialog"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp</Notes>
	<div class="flex content-center justify-center">
		<img src="timesup1.png" alt="Time's up dialog"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
			<p>Using Expo Go️️ 💡</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Designed for iPads, no WhatsApp, no native anything, no launcher! CamiNora is old, we'll see sthg better later</Notes>
	<div class="flex content-center justify-center">
		<img src="expo-go.png" alt="Time's up dialog"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
			<p>Using Expo Go️️ 💡</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Designed for iPads, no WhatsApp, no native anything, no launcher! CamiNora is old, we'll see sthg better later</Notes>
	<div class="flex content-center justify-center">
		<img src="expo-go.png" alt="Time's up dialog"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>CamiNora</h3>
			<p>A Private Chat App 👭</p>
			<p>Expo Notifications 📩</p>
			<p>And a Timer️️ ⏲️</p>
			<p>Using Expo Go️️ 🤫</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Yes, it's the Expo Dev Server, apps connect to it and auto-reload</Notes>
	<div class="flex content-center justify-center">
	  <img src="why-not.jpg" class="contain " alt="Bilbo Baggins why not meme"/>
	</div>
</Slide>
<Slide animate>
	<Notes>Yes, it's the Expo Dev Server, apps connect to it and auto-reload</Notes>
	<div class="flex content-center justify-center">
	  <img src="rsc.png" class="contain " alt="Expo Go Server"/>
	</div>
</Slide>

<Slide>
	<Notes>There's a simple Express.js server on Hetzner (5EUR/month)</Notes>
	<div class="flex content-center justify-center">
		<div class="flex-1">
			<img src="caminora-splash.png" alt="CamiNora Splash Screen"/>
		</div>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Features</h3>
			<Slide animate>
				<Fragment animation="fade-in-then-semi-out">1 Platform</Fragment>
				<Fragment animation="fade-in-then-semi-out">1 Form Factor</Fragment>
				<Fragment animation="fade-in-then-semi-out">2 Users 👭</Fragment>
				<Fragment animation="fade-in-then-semi-out">1 Locale 🇩🇪</Fragment>
				<Fragment animation="fade-in-then-semi-out">DIY Auth 📞</Fragment>
				<Fragment animation="fade-in-then-semi-out">Expo Go 📷</Fragment>
			</Slide>
		</div>
	</div>
</Slide>

<Slide animate>
	<Notes>Work in Progress, a bit more in depth</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-splash.png" alt="Ancuo Splash Screen"/>
	</div>
</Slide>
<Slide animate>
	<Notes>Work in Progress, a bit more in depth</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-splash.png" alt="Ancuo Splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Work in Progress, a bit more in depth</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-splash.png" alt="Ancuo Splash screen"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Work in Progress, a bit more in depth</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-sign-in.png" alt="Ancuo Sign In"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Work in Progress, a bit more in depth</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-oauth.png" alt="Ancuo Sign In with Google"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Work in Progress, a bit more in depth, default layout by the showcase app</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-welcome.png" alt="Ancuo Homepage"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Work in Progress, a bit more in depth, default layout by the showcase app</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-events.png" alt="Ancuo Events page"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
		</div>
	</div>
</Slide>
<Slide animate>
	<Notes>Work in Progress, a bit more in depth, default layout by the showcase app</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-events.png" alt="Ancuo Events page"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
			<p>Expo Dev Build 🛠️</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Work in Progress, a bit more in depth, default layout by the showcase app</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-dev.png" alt="Ancuo Dev Build"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
			<p>Expo Dev Build 🛠️</p>
		</div>
	</div>
</Slide>
<Slide>
	<Notes>Work in Progress, a bit more in depth, default layout by the showcase app</Notes>
	<div class="flex content-center justify-center">
		<img src="ancuo-launcher.png" alt="Ancuo Dev Build"/>
		<div class="flex flex-1 flex-col self-stretch justify-self-stretch justify-center">
			<h3>Ancuo</h3>
			<p>A GCal Synchronizer 📆</p>
			<p>Expo Dev Build 🛠️</p>
		</div>
	</div>
</Slide>

<Slide animate>
	<h3>Takeaways</h3>
</Slide>
<Slide animate>
	<h3>Takeaways</h3>
	<p>Think Small 🤏</p>
</Slide>
<Slide animate>
	<h3>Takeaways</h3>
	<p>Think Small 🤏</p>
	<p>Smaller Scope 👉 P(🚢) ⬆️⬆️⬆️️</p>
</Slide>
<Slide animate>
	<h3>Takeaways</h3>
	<p>Think Small 🤏</p>
	<p>Smaller Scope 👉 P(🚢) ⬆️⬆️⬆️️</p>
	<p>Have Fun with Libraries! 🦄</p>
</Slide>
<Slide animate>
	<h3>Takeaways</h3>
	<p>Think Small 🤏</p>
	<p>Smaller Scope 👉 P(🚢) ⬆️⬆️⬆️️</p>
	<p>Have Fun with Libraries! 🦄</p>
	<p>...But One at the Time 😅</p>
</Slide>
<Slide animate>
	<Notes>Even with Expo, they're a black hole</Notes>
	<h3>Takeaways</h3>
	<p>Think Small 🤏</p>
	<p>Smaller Scope 👉 P(🚢) ⬆️⬆️⬆️️</p>
	<p>Have Fun with Libraries! 🦄</p>
	<p>...But One at the Time 😅</p>
	<p>Stay Away from the Stores if you can! 🤕</p>
</Slide>

<Slide>
	<h3>Thanks!</h3>
	<div class="flex justify-center">
		<img class="qr" alt="QR code to my website" src="qr-code.png" />
	</div>
	<a href="https://michelebonazza.com">https://michelebonazza.com</a>
</Slide>