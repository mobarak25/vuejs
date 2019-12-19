<template>
	<div class="hello">
		<div class="header">
            <ul>
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/about">About</router-link></li>
            </ul>
        </div>
	</div>
</template>

<script>
	export default {
		
		name: 'Header',
		data:function(){
			return {

			}
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
