<template >
    <div style="display:flex; flex-direction: column; align-items: center; justify-content: center; border:1px solid">
        <h1>Component 2</h1>
        <ComponentThree />
    </div>
</template>
<script>
import ComponentThree from './ComponentThree.vue';
export default {
    name: "ComponentTwo",
    components: { ComponentThree }
}
</script>
<style lang="">
    
</style>