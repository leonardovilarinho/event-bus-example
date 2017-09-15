<template>
    <section>
        <button @click="$bus.$emit('notify', 'sua senha é inválida')">
            Senha inválida!
        </button>
        <button @click="$bus.$emit('notify', 'seu usuário é inválido')">
            Usuário inválido!
        </button>
    </section>
</template>

<script>
export default{
    name: 'lv-container',
}
</script>
