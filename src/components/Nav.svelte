<script>
	import Icon from "fa-svelte/src/Icon.svelte";
	import { faTwitter } from "@fortawesome/free-brands-svg-icons/faTwitter";
	import { faLinkedin } from "@fortawesome/free-brands-svg-icons/faLinkedin";
	import { faGithub } from "@fortawesome/free-brands-svg-icons/faGithub";
	export let segment;
</script>

<style>
	nav {
		font-weight: 300;
		padding: 0 1em;

		display: flex;
		justify-content: space-between;
	}

	ul {
		margin: 0;
		padding: 0;
	}

	/* clearfix */
	ul::after {
		content: '';
		display: block;
		clear: both;
	}

	li {
		display: block;
		float: left;
	}

	[aria-current] {
		position: relative;
		display: inline-block;
	}

	[aria-current]::after {
		position: absolute;
		content: '';
		width: calc(100% - 1em);
		height: 2px;
		background-color: rgb(255,62,0);
		display: block;
		bottom: -1px;
	}

	a {
		text-decoration: none;
		padding: 1em 0.5em;
		display: block;
	}

	.social_links > li {
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.social_links > li > a {
		padding: 0.5em;
		font-size: 20px;
		display: flex;
	}
</style>

<nav>
	<ul>
		<li><a aria-current="{segment === undefined ? 'page' : undefined}" href=".">About me</a></li>
		<li><a aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">Blog</a></li>
<!-- 		<li><a aria-current="{segment === 'about' ? 'page' : undefined}" href="about">about</a></li> -->
		<!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
		<li><a rel=prefetch aria-current="{segment === 'blog' ? 'page' : undefined}" href="blog">Blog</a></li>
		     the blog data when we hover over the link or tap it on a touchscreen -->
	</ul>
	<ul class="social_links">
		<li><a aria-label="GitHub" href="https://github.com/aaralh"><Icon icon={faGithub}/></a></li>
		<li><a aria-label="LinkedIn" href="https://www.linkedin.com/in/aaro-alhainen-514170138"><Icon icon={faLinkedin}/></a></li>
		<li><a aria-label="Twitter" href="https://twitter.com/AAlhainen"><Icon icon={faTwitter}/></a></li>
	</ul>
</nav>
