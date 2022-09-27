<script>
	import '../app.scss';
</script>

<nav class="navbar navbar-expand-lg bg-dark">
	<div class="container-fluid">
		<a class="navbar-brand" href="/">
			<img src="/wideWhiteLogo.png" width="100px" height="35px" alt="Mission X" />
		</a>
		<button
			class="navbar-toggler"
			type="button"
			data-bs-toggle="collapse"
			aria-controls="navbarNav"
			aria-expanded="false"
			aria-label="Toggle navigation"
		>
			<span class="navbar-toggler-icon" />
		</button>
		<div class="collapse navbar-collapse" id="navbarNav">
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link" href="/about">About Us</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="/competitions">Competitions</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="/cyberchats">Cyber Chats</a>
				</li>
				<a
					class="btn btn-primary"
					href="https://calendar.google.com/calendar/embed?src=contactmissionxlamc%40gmail.com&ctz=America%2FLos_Angeles"
					role="button">Calendar</a
				>
			</ul>
		</div>
	</div>
</nav>
<slot />

<style>
	.nav-link {
		color: white;
	}
	.nav-item :hover {
		color: rgb(0, 120, 255);
	}
</style>
