<template >
    <div style="display:flex; flex-direction: column; align-items: center; justify-content: center; border:1px solid">
        <h1>Component 3</h1>
        <div style="display:flex; flex-direction:row; align-items:center;">
            <img v-if="userData?.avatar" :src="userData.avatar" style="height: 50px; width:50px; border-radius:100%; margin-right: 10px;" />
            <h3 v-if="userData?.name">{{ userData.name }}</h3>
        </div>
    </div>
</template>
<script>
export default {
    name: "ComponentThree",
    inject: ['userData']
}
</script>
<style lang="">
    
</style>