<template>
    <div class=" w-full flex flex-col items-center justify between text-center"><img src="../assets/logo.png" alt="" class="w-32">
       <h1 class="text-center text-orange-400 text-3xl font-medium mt-10">Sign Up</h1>
       <div class="mt-10 "> 
            <input type="text" placeholder="Enter Name" class=" w-80 pl-20 py-2 my-5 block border-solid border-2 border-inherit rounded">
            <input type="email" placeholder="Enter Email" class=" w-80 pl-20 py-2 my-5 block border-solid border-2 border-inherit rounded">
            <input type="password" placeholder="Enter Password" class=" w-80 pl-20 py-2 my-5 block border-solid border-2 border-inherit rounded">
            <button class="bg-orange-400 text-white text-xl px-8 py-2 rounded-full">Sign Up</button>
       </div>
    </div>
</template>

<script>
   export default {
    name : 'SignUp'
   }
</script>

<style scoped>

</style>