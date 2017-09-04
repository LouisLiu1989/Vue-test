<template>
	<div id="app">
	  <input type="radio" v-model="selected" value="我是單選按鈕 1" /><label>我是單選按鈕 1</label>

	  <input type="radio" v-model="selected" value="我是單選按鈕 2" /><label>我是單選按鈕 2</label>

	  <input type="radio" v-model="selected" value="我是單選按鈕 3" /><label>我是單選按鈕 3</label>

	  <div>selected ={{ selected }}</div>
	</div>
</template>


<script>
	export default{
		data(){
			return{
				selected: '尚未選擇任何一項'
			}		
		}
	}

</script>
