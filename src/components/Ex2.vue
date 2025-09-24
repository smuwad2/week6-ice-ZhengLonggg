<script>
    export default { 
        data() {
            return {
                width: '200',
                height: '200',
                myImg: '/assets/me.png'
            }
        },
    }
</script>

<template>

    <div>

     <img v-bind:src="myImg" v-bind:width="width" v-bind:height="height" />

    </div>


    <!-- add code here -->
     <!-- <img v-bind:src="myImg" v-bind:width="width" v-bind="height" /> -->
     
   
</template>
