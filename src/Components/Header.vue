<template>
    <header>
        <ul>
            <li>Inicio</li>
            <li>Séries</li>
            <li>Filmes</li>
            <li>Animes</li>
            <li>Jogos</li>
        </ul>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
    header {
        height: var(--header-height);
        background-color: var(--dark-10);

        display: flex;
    }
</style>