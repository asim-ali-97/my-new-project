<template>
    <div>
        <p>welcome to about page</p>
        <p>this is my sub title</p>

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