<template>
	
	<div class="footer">
		{{ year }} @copy {{ mesg }}
	</div>
	
</template>

<script>
	export default {
		name: 'Footer',
		data:function(){
			return {
				mesg:'Pos all rights reserved.',
				year: new Date().getFullYear(),

			}
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
