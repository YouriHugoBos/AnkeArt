<template>
	<div class="home-container">
		<div class="img-container">
			<div id="img-one" class="img">
				<img src="../assets/voorbeeld.jpg">
			</div>
			<div id="img-two" class="img"></div>
			<div id="img-three" class="img"></div>
			<div id="img-four" class="img"></div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-container{
	padding-left:6rem;
}
.img-container{
	float: right;
	width: 60%;
	padding-top:10rem;
}
img{
	width: 100%;
	height: auto;
}
.img{
    width: 40%;
    height: 16rem;
    border: 1px solid black;
    margin: 1rem;
    display: inline-block;
}

</style>
