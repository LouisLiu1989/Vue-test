<template>
<div id="navbar">
	<div class="navleft">
        <ul>
          	<li v-on:click="say">Lady首頁</li>
          	<li>我的商品</li>
          	<li>上架商品</li>
        </ul>
    </div>
    <div class="navcenter">
        <select name="" id="">
            <option value="">2</option>
            <option value="">1</option>
            <option value="">3</option>
        </select>
    </div>

    <div class="navright">
        <input type="text" name="search">
    </div>
</div>
</template>



<script>
export default{
	name:'navbar',
	methods:{
		say:function(event){
			console.log('hello')
		}
	}
}
</script>

<style lang="sass" scoped>
$lineheight  :35px;

.navleft{
	outline: 2px solid #ccc;
	color: #222;
	line-height:35px;
	text-align:center; 
	display:inline-block;
	float:left;
	width: 615px;
	ul{
		li{
			width: 205px;
			float: left;
		}	
	}
}
.navcenter{
	display:inline-block;
	float:left;
	margin-left: 42.5px;
	select{
		width: 250px;
		height: 35px;
	}
}

.navright{		
	display:inline-block;
	float:left;
	margin-left: 38.5px;
		
	input{
		width: 250px;
		line-height: 32px;
		font-size: 24px;
	}
} 	
</style>














