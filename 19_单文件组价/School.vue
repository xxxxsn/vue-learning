<template>
      <div>
            <h2>学校:{{name}}</h2>
            <h2>地址:{{address}}</h2>
            <Student></Student>
      </div>
</template>

<script>
import Student from "./Student.vue"
export default { 
    name:"School",
    data(){
        return {
            name:"北京大学",
            address:"首都"
        }
    },
    components:{
       Student
    }

}
</script>

<style>

</style>