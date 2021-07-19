<script context="module">
	export const prerender = true;
  import { prefetchRoutes } from '$app/navigation';
  import { browser } from '$app/env';
  if (browser) {
    prefetchRoutes()
  }
</script>

<svelte:head>
	<title>Walk with Pete</title>
</svelte:head>

<section class="outer-wrapper"> 
	<h1>
    Walk<br>
    with<br>
    Pete<br>
	</h1>

	<p>
    <strong>Accompanying you in your one wild life</strong>
  </p>
  <hr>
  <p>
    Are you longing for deeper love and connection?
  </p>
  <p>
    Are you feeling lonely? Stuck? Curious about what more is possible for you?
  </p>
  <p>
    Would you love to feel someone walking alongside you? Someone gently listening, asking questions and helping you explore yourself and navigate the world around you with curiosity? Would you love to take your next steps with own unique wisdom and intuition?
  </p>
  <p>
    
    <quote>
      "Pete is a kind, loving and respectful teacher who can really give people the nourishment they need to grow. I’m often amazed at Pete’s communication ability and interpersonal virtuosity. He has a knack for saying the right thing, at the right time, in just the right way it needs to be said. An amazing instinct." - Rupert
    </quote>
  </p>
  <p>
    As of writing this, 17 July 2021, I'm continuing my journey of turning this passion for accompanying people into a livelihood.
  </p>
  <p>
    <strong>
      So I'm inviting you to walk with me.
    </strong>
  </p>
  <p class="monospace larger">
    📅☎️ <a target="_blank" href="https://calendly.com/peterjacobson-nz/30-min-are-we-a-good-fit-to-travel-together-chat">Book a half hour call</a> to discover if we'll be a good fit to walk together.
  </p>
  <p class="mb-0">
    If it's feeling good, we'll
  </p>
  <ul class="no-dot monospace">
    <li>
      choose a starting call rhythm - weekdays, twice a week, or weekly
    </li>
    <li>
      pick a regular time of day, e.g. 8am.
    </li>
    <li>
      pick a call duration - 10-60 minutes
    </li>
    <li>
      decide a duration we'd like to commit to - perhaps 3 sessions or a week.
    </li>
  </ul>
  <p class="monospace larger">
    🤲 24 hours after each session, I'll invite you to reflect on the value of the session for you, and to gift me a koha - monetary or other.
  </p>


</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

  p, li {
    max-width: 500px;
  }

  a {
    font-weight: 600;
    color: rgb(94, 72, 0);
    background-color: none;
    background: linear-gradient(180deg, rgba(255,255,255,0) 75%, #2dee2372 75%);
  }
  quote {
    display: block;
    font-family: 'Courier New', Courier, monospace;
    font-size: 0.6em;
    padding-left: 40px;
    color: rgb(94, 72, 0);
    /* padding-top: 30px; */
    background: linear-gradient(90deg, #fdc02572 5%, rgba(255,255,255,0) 5%);
    /* background: linear-gradient(90deg, #fdc02572 5%, rgba(255,255,255,0) 5%),  linear-gradient(180deg, #fdc02572 5%, rgba(255,255,255,0) 5%); */
  }

  quote::before {
    display: block;
    content: "\A"
  }
  quote::after {
    display: block;
    content: "\A"
  }

  .monospace {
    font-family: 'Courier New', Courier, monospace;
    font-size: 0.8em;
  }

  li {
    font-size: 1.5em;
  }

  .larger {
    font-size: 1.2em;
  }

	.outer-wrapper {
    padding: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  .inset {
    padding-left: 50px;
  }

  .mb-0 {
    margin-bottom: 0;
  }

  .no-dot {
    list-style-type: none;
  }
  li:before { 
    content: '\1F449'; margin-left: -10px; margin-right: 10px; 
    /* content: '\1F44C'; margin-left: -10px; margin-right: 10px;  */
  } 

</style>
