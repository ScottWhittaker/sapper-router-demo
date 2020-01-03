<script>
	export let segment;
</script>

<style>
	.selected {
		color: rgb(255,62,0);
	}
</style>

<h1>Profile</h1>

<nav>
	<ul>
		<li><a class="{segment === 'account' ? 'selected' : ''}" href="profile/account/username">account</a></li>
		<li><a class="{segment === 'email' ? 'selected' : ''}" href="profile/email">email</a></li>
		<li><a class="{segment === 'notifications' ? 'selected' : ''}" href="profile/notifications">notifications</a></li>
	</ul>
</nav>
<slot></slot>
