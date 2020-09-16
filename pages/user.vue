<template>
 <div>
     <h1>
         用户管理界面
     </h1>
     <router-link to="/about">关于我们</router-link>
     <nuxt-link to="/login">登录页面</nuxt-link>
     <hr>
     <div>
         <!-- <router-view></router-view> -->
         <nuxt />
     </div>
 </div>
</template>

<script>
export default {
 data(){
 return{}
 },
 created(){},
 methods:{},
 components:{}
}

</script>
<style scoped>
</style>