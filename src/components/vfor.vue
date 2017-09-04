<template>
	<div class="vfor">
      <ul id="aa">
        <li v-for="user in users">
          {{user.firstname}} {{user.lastname}}
        </li>
      </ul>

	  <input type="text" v-model="message" >
	  <p>{{ message }}</p>


	  
</template>

<script>
export default{
	name:'aa',
	data(){
		return{
			users:[
				{firstname: 'Sebastian', lastname: 'Eschweiler'},
	    	    {firstname: 'Bill', lastname: 'Smith'},
	        	{firstname: 'John', lastname: 'Porter'},
	        	{firstname: 'Tim', lastname: 'Young'}
			],
			message:''
		}
	}

}

</script>



