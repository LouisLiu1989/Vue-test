<template>
	<div id="Checkb">
	  <input type="checkbox" v-model="toggle" :true-value="1" :false-value="2"/>
	  <label>我是複選框</label>
	  toggle = {{ toggle }}
	</div>

	<div id="Checkboxmore">
	  <input type="checkbox" v-model="group" value="1" /><label>我是複選框 1</label>

	  <input type="checkbox" v-model="group" value="2" /><label>我是複選框 2</label>

	  <input type="checkbox" v-model="group" value="3" /><label>我是複選框 3</label>

	  <div>group = {{ group }}</div>
	</div>
</template>


<script>
	export default{
		data(){
			return{
				toggle: 0,
				group: []
			}
		}
	}
</script>