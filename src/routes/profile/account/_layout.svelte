<script>
    export let segment;
</script>

<style>
	.selected {
		color: rgb(255,62,0);
	}
</style>

<h2>Account</h2>

<nav>
    <ul>
        <li><a class='{segment === "username" ? "selected" : ""}' href='profile/account/username'>Username</a></li>
        <li><a class='{segment === "password" ? "selected" : ""}' href='profile/account/password'>Password</a></li>
    </ul>
</nav>

<slot></slot>
