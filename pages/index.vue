<template>
  <div>
    <h1 class="title">Welcome to my website</h1>
    <p>this is the Home page.. And here i have made some changes..</p>

    <CustomBtn @click="$router.push('/about')" title="Goto About Page" />
    <CustomBtn @click="$router.push('/contact')" title="Go to Contact Page"/>
  </div>
</template>

<script>
import CustomBtn from "@/components/CustomBtn.vue"
export default {
  name: 'IndexPage',
  components: {
    CustomBtn
  }
}
</script>

<style>
.title {
  color: red;
}
</style>
