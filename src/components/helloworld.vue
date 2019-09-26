<template>
  <div>
    Welcome !!! {{message}}
    <p v-text="message"></p>
  </div>
</template>

<script>
export default {
    
        name: "Hello world",
        data: function(){
                return {
                message: 'Vue is awesome'
                }
            }
};
    

</script>
<style>
</style>

