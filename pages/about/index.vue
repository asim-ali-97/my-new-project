<template>
    <div>
        <h1>Welcome to about page</h1>
        <p>this is my sub title.. And it has been Modified..</p>

        <CustomBtn @click="$router.push('/')" title="Goto Home Page"/>
    </div>
</template>

<script>
import CustomBtn from "@/components/CustomBtn.vue"
export default {
    components: {
        CustomBtn
    }
}
</script>

<style></style>