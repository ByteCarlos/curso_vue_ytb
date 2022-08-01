<template>
    <img :src="avatar" :alt="descricao">
    <Reutilizacao />
</template>
<script>
    import Reutilizacao from './Reutilizacao.vue'
    export default {
        components: { Reutilizacao },
        name: 'Picture',
        data() {
            return {
                avatar: "/img/avatar.png",
                descricao: "Carlos Henrique"
            }
        }
    }
</script>