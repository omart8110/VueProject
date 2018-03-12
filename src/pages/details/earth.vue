<template>
	<div>
		开放产品1132323232311:{{ getOrder }}
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