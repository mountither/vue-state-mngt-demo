<template >
    <div style="display:flex; flex-direction: column; align-items: center; justify-content: center; border:1px solid">
        <h1>Component 1</h1>
        <ComponentTwo />
    </div>
</template>
<script>
import ComponentTwo from './ComponentTwo.vue';
export default {
    name: "ComponentOne",
    components: { ComponentTwo }
}
</script>
<style lang="">
    
</style>