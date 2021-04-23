<template>
    <div class="home">
        <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld";

export default {
    name: "Login",

    components: {
        // eslint-disable-next-line vue/no-unused-components
        HelloWorld,
    }
}
</script>