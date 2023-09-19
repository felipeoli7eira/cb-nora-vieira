<script setup>

</script>

<template>
    <header class="border text-center d-flex flex-column align-items-center justify-content-center">
        <h1 class="playfair-font m-0">Centro de beleza Nora Vieira</h1>
        <p class="m-0">De segunda á Sábado, das 09h ás 18h com agendamento fácil pelo WhatsApp.</p>
        <button class="agendar text-uppercase border-none bg-transparent">agendar</button>
    </header>
</template>

<style scoped>
header {
    background-color: #E0DFF0;
    color: #BC749A;
    height: 20rem;
}

header h1 {
    font-weight: 300 !important;
    font-size: 36px;
}

header p {
    font-size: 1rem;
    font-weight: 300;
    color: #786890;
}

header button {
    font-size: 1rem;
    font-weight: 400;
    border: 1px solid #BC749A;
    color: #BC749A;
    width: 182px;
    height: 54px;
    margin-top: 31px;
    transition: all .2s;
}

header button:hover {
    cursor: pointer;
    opacity: 0.8;
}

@media (max-width: 500px) {
    header {
        padding: 2rem;
    }
}
</style>
