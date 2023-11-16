<template>
  <nav>
    <ul class="nav__lista">
        <li><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="menu-przycisk">
        <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
        </svg></li>
        <li><a href="#">Produkty</a></li>
        <li><a href="#">Promocje</a></li>
        <li><a href="#">Outlet</a></li>
        <li><a href="#">Gazetka</a></li>
        <li><a href="#">Aktualności</a></li>
        <li><a href="#">Klub</a></li>
        <li><a href="#">Sklepy</a></li>
        <li><a href="#">Usługi</a></li>
    </ul>   </nav>
</template>

<script>
export default {

}
</script>

<style>
nav{
    width: 100%;
    padding-top: 6em;
    background-color: var(--tlo-czerwony);
    border-top: 1px solid var(--tlo-szary);
    border-bottom: 1px solid var(--tlo-szary);

}

.nav__lista{
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0;
}

.nav__lista a{
    padding: var(--rozmiar-base);
    font-size: var(--rozmiar-base);
    color: var(--czcionka-bialy);
    transition: color 0.3s;
}

.nav__lista a:hover{
    color: var(--tlo-szary);
    border-bottom: 1px solid var(--czcionka-bialy);
}

.menu-przycisk{
    color: var(--czcionka-bialy);
    background-color: var(--tlo-czerwony);
    width: var(--rozmiar-5xl);
    height: var(--rozmiar-5xl);
    cursor: pointer;
}
</style>