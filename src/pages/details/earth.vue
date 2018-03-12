<template>
	<div>
		开放产品1111:{{ getOrder }}
	</div>
</template>
<script>
	
export default{
	name:"earth",
	data(){
		return{

		}
	},
	computed:{
		getOrder(){
			return this.$store.getters.getOrder
		}
	}
}	

</script>
<style>
	
</style>