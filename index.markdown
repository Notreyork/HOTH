---
layout: default
title: Home
---

<style>

	main {
		margin-bottom: 0;
	}

	.main-image__wrapper {
		position: relative;
		width: 100%;
		height: 100dvh;
	}

	.main-image {
		position: absolute;
		width: 35rem;
		padding: 1rem;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}

	.main-image img,
	.main-image video {
		display: block;
		width: 100%;
	}

	.main-image video { /* Targeting the second image */
		position: absolute;
		width: 30%;
		bottom: 1rem;
		left: 50%;
    	transform: translateX(-50%);
	}

	@media only screen and (max-width: 50rem) {
		.main-image {
			width: 100%;
			padding: 1rem 5rem 1rem 1rem;
		}

	}
	
</style>

<div class="main-image__wrapper">

	<div class="main-image">

		<img src="/assets/images/main.png">

		<video autoplay muted loop>
            <source src="/assets/images/main2.mp4" type="video/mp4">
        </video>

	</div>
</div>