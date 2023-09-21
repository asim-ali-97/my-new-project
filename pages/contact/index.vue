<template>
    <div>
        <h1>Welcome to contact page..</h1>
        <p>this my my contact page..</p>


        <CustomBtn @click="$router.push('/')" title="Go to Home Page"/>
    </div>
</template>

<script>
import CustomBtn from "@/components/CustomBtn.vue"
export default{
    components: {
        CustomBtn
    }
}

</script>

<style></style>