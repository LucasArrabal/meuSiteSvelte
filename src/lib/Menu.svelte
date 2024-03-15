<script>
  import Logo from "./Logo.svelte";

  const item =[
    {href: '/', label: 'Início'},
    {href: '/sobre', label: 'Sobre'},
    {href: '/contato', label: 'Contato'},
    {href: '/portfolio', label: 'Portfolio'},
    {href: '/faq', label: 'FAQ'}
  ];

</script>
<a href="/"> <Logo/> </a> 

{#each item as {href, label} }
<a href="{href}" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">{label}</a>
{/each}

<!-- <a href="/" class="text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-blue-500 mx-1.5 sm:mx-6">Início</a> -->



