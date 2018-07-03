<template>
	<div class="nav-container">
		<ul>
			<li class="active">
    			<a><font-awesome-icon size="3x" icon="home" /></a>
			</li>
			<li>
				<div>
    				<a><font-awesome-icon size="3x" icon="images" /></a>
				</div>
			</li>
			<li>
    			<a><font-awesome-icon size="3x" icon="comment" /></a>
			</li>
			<li>
    			<a><font-awesome-icon size="3x" icon="at" /></a>
			</li>
		</ul>
	</div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-container{
	position: absolute;
	float: left;
	background-color:#68829B;
	min-height: 100%;
	width: 6rem;
}
ul {
	padding: 0;
	margin:0;
}
li {
	display: block;
	padding: 5rem 0;
}
li:hover {
	background-color: #fff;
}
.active{
	background-color: #fff;
}
</style>
