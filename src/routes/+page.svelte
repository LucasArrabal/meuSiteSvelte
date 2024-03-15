<script>
    const lista = [
       { nome:'Teste 1', idade: 12},
       { nome:'Teste 2', idade: 32},
       { nome:'Teste 3', idade: 22},
    ]
</script>
<h1>Meu site</h1>
{#each lista as {nome , idade} }
    <p>Nome: {nome} | Idade: {idade}</p>
{/each}

