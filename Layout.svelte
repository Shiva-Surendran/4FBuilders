<div class="bar">
	<div class="bar">
		<nav class="nav-title">
			<span class="textwhite"
				>Welcome to
				<span class="textred"> 4f Builders</span>
				<span class="texthid"> & Engineering Pvt. Ltd</span>
			</span>
		</nav>
	</div>

	<nav class="nav-bar">
		<a href="/Home" class="nav-link">Home</a>
		<a href="/About" class="nav-link">About us</a>
		<a href="/Projects" class="nav-link"> Our Projects</a>
		<a href="/Contact" class="nav-link">Contact Us</a>
		<div class="fun">(Hover Over the title)</div>
	</nav>
</div>
<slot />

<footer>
	<div class="bottom">
		<nav class="nav-bar2">
			<span class="bottom">This website was created using svelte </span>
			<div class="image-logo">
				<img src="logo.jpg" alt="Right Image" width="80" height="30" x />
			</div>
			<span class="bottom"> Webmaster: Shiva Surendran</span>
			<p class="bottom">@copyleft 2024. all rights reserved</p>
		</nav>
	</div>
</footer>

<style>
	.bar {
		overflow: hidden;
		background-color: #fff2f2;
		text-align: left;
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
	}

	.nav-bar {
		overflow: hidden;
		background-color: #333;
		font-size: 20px;
		padding: 10px;
	}
	.nav-bar2 {
		overflow: hidden;
		background-color: #333;
		font-size: 20px;
		padding: 0px;
	}
	.right {
		align-items: right;
		display: flex;
		justify-content: flex-end;
	}

	.nav-link {
		border-radius: 5px;
		float: left;
		color: white;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
		font-family: merriweather;
	}

	.fun {
		text-align: right;
		font-family: merriweather;

		padding: 14px 16px;
		color: white;
	}
	.nav-title {
		margin-bottom: 50px;
		margin: 30px;
	}

	.nav-link:hover {
		background-color: #3c460b;
	}

	.textwhite {
		font-size: 50px;
		margin: 0;
		font-family: poppins;
		color: rgb(0, 0, 0);
	}

	.textred {
		font-size: 50px;
		margin: 0;
		font-family: poppins;
		color: rgb(0, 0, 0);
	}

	.texthid {
		font-size: 50px;
		margin: 0;
		color: rgb(255, 255, 255);
		font-family: poppins;
	}

	.nav-title .textwhite:hover {
		color: rgb(57, 234, 57);
	}
	.nav-title:hover .textred,
	.nav-title:hover .texthid,
	.bar {
		background-color: rgb(255, 255, 255);
		color: rgb(0, 0, 0);
		font-size: 60px;
		font-weight: 500;
	}

	.text {
		background-color: white;
		margin-bottom: 0px;
		font-size: 20px;
		margin: 0 auto -20px;
		font-family: poppins;
	}

	.bottom {
		text-align: center;
		color: wheat;
		font-family: Hind SILIGURI;
		font-size: 15px;
	}
	.image-logo {
		padding: 10px;
	}
</style>
