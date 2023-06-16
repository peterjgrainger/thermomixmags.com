<script>
	import Icon from '$lib/Icon.svelte';
</script>

<div>
	<img
		src="https://res.cloudinary.com/di4veouyn/image/upload/v1685684827/mags.jpg"
		alt="Mags smiling beside a thermomix"
	/>
	<div class="hero-tiles-container">
		<div class="hero-image">
			<a href="https://calendly.com/thermomixmags/demo">
				<h1>📆</h1>
				<h2>Book a demo</h2>
			</a>
		</div>
		<div class="hero-image">
			<h3>Get in touch</h3>
			<div class="social-container">
				<div class="social-item">
					<a href="https://www.tiktok.com/@thermomixmags">
						<Icon name="tiktok" />
					</a>
				</div>
				<div class="social-item">
					<a href="https://www.facebook.com/profile.php?id=100092326532900">
						<Icon name="facebook" />
					</a>
				</div>
				<div class="social-item">
					<a href="mailto:hi@thermomixmags.com">
						<Icon name="email" />
					</a>
				</div>
			</div>
		</div>
	</div>
	<div class="blurb">
		<p>
			Hi! My name is Mags, I'm based in Newcastle upon Tyne and I'm a thermomix advisor. 
			I can help you decide if thermomix is right for you.
		</p>
	</div>
</div>

<style>
	img {
		width: 100%;
		object-fit: cover;
		margin-left: auto;
		margin-right: auto;
		display: block;
	}

	.blurb {
		margin-top: -80px;
		margin-left: 50px;
		margin-right: 50px;
	}

	@media (max-width: 850px) {
		img {
			height: 400px;
		}
		.social-item {
			margin: 1rem;
		}
		
	}

	@media (min-width: 850px) {
		img {
			height: 700px;
		}
		.social-item {
			margin: 1.5rem;
		}

		.hero-tiles-container {
			padding-right: 80px;
			padding-left: 80px;
		}
	}

	.hero-image {
		flex: 1;
		min-height: 160px;
		min-width: 230px;
		background-color: var(--white);
		position: relative;
		padding: 10px;
		bottom: 120px;
		border-radius: 18px;
		border: 1px solid var(--black);
		margin: 30px;
		transition: transform 0.5s, box-shadow 0.5s ease-in-out;
	}

	.hero-tiles-container {
		display: flex;
		flex-wrap: wrap;
		margin-right: auto;
		margin-left: auto;
		justify-content: space-evenly;
		width: 100%;
		text-align: center;
	}

	.social-container {
		display: flex;
		flex-wrap: wrap;
		margin-right: auto;
		margin-left: auto;
		justify-content: space-evenly;
		width: 100%;
		text-align: center;
	}

	.hero-image h1 {
		margin: 5px;
	}

	.hero-image h2 {
		margin: 0px;
	}

	.hero-image h3 {
		margin: 0px;
	}

	.social-item {
		flex: 1;
	}
</style>
