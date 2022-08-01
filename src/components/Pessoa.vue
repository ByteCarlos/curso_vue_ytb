<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
        <Info :email="email" :esta_trabalhando=false />
        <Form />
    </div>
</template>
<script>
import Info from './Info.vue'
import Form from './Form.vue'

    export default {
        components: { Info, Form },
        name: 'Pessoa',
        data() {
            return {
                nome: 'Carlos',
                email: 'carlos@email.com'
            }
        }
    }
</script>