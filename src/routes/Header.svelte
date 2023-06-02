<script lang="ts">
  import { page } from '$app/stores'
  $: header_element = $page.route.id === '/' ? 'h1' : 'h2';
</script>

<header>
    <div class = "header-container">
        <div>
          <h1> thermomix mags </h1>
          <h3> Independent Thermomix Advisor </h3>
          <p> Gosforth, Newcastle-upon-tyne</p>
        </div>
    </div>
</header>

<style lang="postcss">
  header {
		padding: 10px;
		background-color: var(--bg);
		color: var(--color);
	}

	.header-container {
		display: grid;
		align-items: center;
		gap: 20px;
		max-width: 1600px;
		margin: 0 auto;
	}

  @media(min-width: 850px) {
    h1 {
      font-size: 6rem;
    }
    h3 {
      font-size: 3rem;
    }

    p {
      font-size: 2.5rem;
      display: block;
    }
  }
  @media(max-width: 850px) {
    h1 {
      font-size: 3rem;
      display: block;
    }

    p {
      font-size: 1rem;
      display: block;
    }
    h3 {
      font-size: 1rem;
      display: block;
    }
  }

	nav a {
		text-decoration: none;
		color: var(--color);
		text-decoration: none;
		border-bottom: solid 3px transparent;
		transition: border-color 0.2s ease;
		&:hover {
			border-bottom: solid 3px var(--primary);
		}
	}

  h3 {
    margin-top: 0rem;
    text-align: center;
    margin-bottom: 0rem;
    
  }

  h1 {
    margin-bottom: 0rem;
    margin-top: 0rem;
    text-align: center;
    color: var(--green)
  }

  p {
    margin-top: 0rem;
    margin-bottom: 0rem;
    text-align: center;
  }
</style>