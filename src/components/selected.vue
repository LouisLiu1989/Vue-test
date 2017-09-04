<template>
	<div id="selected" multiple>
	  <select v-model="selected">
	    <option>A</option>
	    <option>B</option>
	    <option>C</option>
	  </select>
	  <div>selected = {{ selected }}</div>
	  <p>{{ msg }}</p>	
	</div>
</template>

<script>
	 export default{
	 	data(){
	 		return{
	 			// selected1:null,
	 			selected:[],
	 			msg: `Hi, vue-kit@ ${new Date().toLocaleString()}`
	 		}
	 	}
	 }
</script>