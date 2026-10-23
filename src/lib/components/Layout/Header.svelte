<script lang="ts">
	import { Button } from '#components';
	import bookNestLogo from '#lib/assets/app-logo.svg';
</script>

<header>
	<a href="/">
		<img src={bookNestLogo} alt="Go To Home" class="logo" />
	</a>
	<nav>
		<ul>
			<li>
				<Button isMenu={true} href="/register">Create Account</Button>
			</li>
			<li>
				<Button isMenu={true} isSecondary={true} href="/login">Login</Button>
			</li>
		</ul>
	</nav>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 12px 4vw;
	}
	ul {
		display: flex;
		align-items: center;
		column-gap: 24px;
	}

	.logo {
		height: 72px;
	}
</style>
