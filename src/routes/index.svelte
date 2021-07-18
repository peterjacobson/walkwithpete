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
  <p>
    I love walking alongside people - gently listening, asking questions and exploring with curiosity and love - helping people discover their next steps through their unique wisdom.
  </p>
  <p>
    I've been told my presence is 
    <quote>
      "like a warm hug"
    </quote>
    and that I can
    <quote>
      "create a space of unconditional, non-judgemental love"
    </quote>
  </p>
  <p>
    Some of the greatest joys in my life is seeing the people I've walked with flourishing - finding their love, belonging and contributions.
  </p>
  <p>
    As of writing this, 17 July 2021, I'm starting a journey of turning this passion of four years into a livelihood.
  </p>
  <p>
    <strong>
      So I'm inviting you to walk with me.
    </strong>
  </p>
  <p>
    We can jump on a <mark>half hour call</mark> to sense if we'll be a good fit to walk together.
  </p>
  <p class="mb-0">
    If it's feeling good, we'll
  </p>
  <ul class="no-dot">
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

  mark {
    background: linear-gradient(180deg, rgba(255,255,255,0) 75%, #2dee2372 75%);
  }
  quote {
    background: linear-gradient(180deg, rgba(255,255,255,0) 75%, #fdc02572 75%);
  }

  quote::before {
    display: block;
    content: "\A"
  }
  quote::after {
    display: block;
    content: "\A"
  }

	.outer-wrapper {
    padding: 20px;
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
