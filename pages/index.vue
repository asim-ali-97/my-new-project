<template>
  <div>
    <p class="title">welcome to my website</p>
    <p>this is the Home page.. And here i have made some changes..</p>

    <CustomBtn @click="$router.push('/about')" title="Goto About Page" />
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
