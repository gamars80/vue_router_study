<template>
    <div>
        <h1>이유저의 현재 아이디는 {{userId}}</h1>
       
    </div>
</template>

<script>
export default{
    computed:{
        userId(){
            //return this.$route.params
            return this.$route.params.userId
        }
    }
}

</script>