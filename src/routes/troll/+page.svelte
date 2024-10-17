<script>
	import * as Fluent from "fluent-svelte";
	import "fluent-svelte/theme.css";
</script>

<style>

	nav {
		display: flex;
		justify-content: left;
		align-items: center;
		padding: 8px;
	}

	h1, h2, h3, h4, h5, h6, span, p, nav a {
		font-family: 'Segoe UI', system-ui, -apple-system, BlinkMacSystemFont, Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
	}

	h1 {
		font-weight: 500;
		transition: 1s ease-in-out;
		animation: ease-in-out font-weight;
	}

	h1:hover {
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 10px;
	}

	nav {
		background: var(--fds-solid-background-base);
		border-bottom: 1px solid rgba(205, 205, 205, 0.25);
	}

	nav a {
		text-decoration: none;
		color: white;
		margin-right: 14px !important;
	}

	nav a.logo img {
		width: 30px;
		height: 30px;
		border-radius: 100%;
		margin-top: 5px;
		margin-left: 5px;
		margin-right: 5px;
	}

	main h1 {
		margin-top: 0;
	}
	
	footer {
		padding-top: 10px;
		padding-bottom: 10px;
		padding-left: 25px;
		background: var(--fds-solid-background-base);
		border-top: 1px solid rgba(205, 205, 205, 0.25);
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		position: absolute;
		bottom: 0;
		width: calc(100vw - 25px);
	}

	@keyframes font-weight {
		0% {
			font-weight: 500;
		}
		25% {
			font-weight: 600;
		}
		100% {
			font-weight: 700;
		}
	}
</style>

<div>
	<nav>
		<a href="/" class="logo"><img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages.wallpapersden.com%2Fimage%2Fdownload%2Flofoten-norway_bGdlbGuUmZqaraWkpJRobWllrWdma2U.jpg&f=1&nofb=1&ipt=02df2dad3d3484a9cc57c13c9b2c065f1bdd44710fe34cab98dee464f5c8a884&ipo=images" alt="Xandaland's pfp"></a>
		<Fluent.Button href="/" style="margin-right: 14px;" variant="hyperlink">Home</Fluent.Button>
		<Fluent.Button href="/plans" style="margin-right: 14px;" variant="hyperlink">Plans</Fluent.Button>
		<Fluent.Button href="/contact" variant="hyperlink">Contact me</Fluent.Button>
	</nav>
	<main>
		<p>WIN64 KEVIN RAIRANEOANRAOSM OSMDVPAJBPWARIZKI MOTHERFUCKER, IF YOU ARE SEEING THIS, I GOT YOUR IP AND YOU ARE ABOUT TO BE DEAD MEAT</p>
        </main>
</div>
