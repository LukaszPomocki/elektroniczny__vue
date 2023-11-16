<template>
  <header>
        <div class="header-lewy">
          <form action="" class="header-formularz">
            <input type="text" placeholder="" class="header-placeholder">
            <button type="submit" class="przycisk-lupa"><img src="../assets/Lupa.svg" alt="Lupa" class="obrazek-lupa"></button>
          </form>
        </div>
        
          <div class="header-prawy">
            <ul class="header-lista">
                <li class="header-link1"><svg xmlns="http://www.w3.org/2000/svg" 
                    fill="none" viewBox="0 0 24 24" stroke-width="1.5" 
                    stroke="currentColor" 
                    class="Obrazek-user">
            
                    <path stroke-linecap="round" stroke-linejoin="round" d="M17.982 18.725A7.488 7.488 0 0012 15.75a7.488 7.488 0 
                    00-5.982 2.975m11.963 0a9 9 0 10-11.963 0m11.963 0A8.966 8.966 0 0112 21a8.966 8.966 0 01-5.982-2.275M15 9.75a3
                     3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                  <a href="#" class="header-link">Zaloguj się</a></li>
                <li class="header-link1"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="Obrazek-user">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 8.25c0-2.485-2.099-4.5-4.688-4.5-1.935 0-3.597 1.126-4.312 2.733-.715-1.607-2.377-2.733-4.313-2.733C5.1 3.75 3 5.765 3 8.25c0 7.22 9 12 9 12s9-4.78 9-12z" />
                  </svg>
                  <a href="#" class="header-link">Schowek</a></li>
                <li class="header-link1"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="Obrazek-user">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
                  </svg>
                  <a href="#" class="header-link">Koszyk</a></li>
                  <li class="header-link1"><button onclick="funkcjaRozwiniecie()" class="header__przycisk"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
              </svg>
              </button>
              </li>
            </ul>
              </div>
              <!-- Koniec head prawy -->
              <div class="header__rozwiniecie" id="header__rozwiniecie">
                  <ul class="nav__lista">
                    <li><a href="#">Produkty</a></li>
                    <li><a href="#">Promocje</a></li>
                    <li><a href="#">Outlet</a></li>
                    <li><a href="#">Gazetka</a></li>
                    <li><a href="#">Aktualności</a></li>
                    <li><a href="#">Klub</a></li>
                    <li><a href="#">Sklepy</a></li>
                    <li><a href="#">Usługi</a></li>
                  </ul>
            </div>
    </header>
</template>

<script>
export default {

}
</script>

<style>
:root{

    /* kolory */
    --czcionka-bialy: rgb(250, 246, 246);
    --czcionka-czarny: rgb(10, 10, 10);
    --tlo-czerwony: rgb(181, 20, 20);
    --tlo-szary: rgb(204, 198, 198);

    /* rozmiary*/
    --rozmiar-xxs: 0.5rem;
    --rozmiar-xs: 0.75rem;
    --rozmiar-sm: 0.875rem;
    --rozmiar-base: 1rem;
    --rozmiar-lg: 1.125rem;
    --rozmiar-xl: 1.25rem;
    --rozmiar-2xl: 1.5rem;
    --rozmiar-3xl: 1.875rem;
    --rozmiar-4xl: 2.25rem;
    --rozmiar-5xl: 3rem;

}

header{
    height: auto;
    width: 100%;
    position: fixed;
    z-index: 2;
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 1.4rem;
    padding-bottom: 1.4rem;
    background-color: var(--tlo-czerwony);
}


.header-lewy{
    padding: 0 var(--rozmiar-base);

}

.header-formularz{
    display: flex;
    align-items: center;
    background-color: var(--czcionka-bialy);
    padding: var(--rozmiar-xxs);
}

.header-placeholder{
    width: 30vw;
    font-size: var(--rozmiar-base);
    background: var(--czcionka-bialy);
    flex: 1;
    border: 0;
    outline: none;
    padding-right: var(--rozmiar-lg);
}

.przycisk-lupa{
    border: 0;
    background: var(--czcionka-bialy);
}

.header-prawy{
    padding-left: var(--rozmiar-base);
    display: flex;
    align-items: center;
    flex-direction: column;
}

.header-lista{
    display: flex;
    align-items: center;
    padding: 0;
    gap: 2em;
}

.header-link1{
    display: flex;
    align-items: center;
    justify-content: center;
}

.header-link{
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: var(--rozmiar-base);
    color: var(--czcionka-bialy);
    transition: color 0.3s;
}

.header-link:hover{
    color: var(--tlo-szary);
}

.Obrazek-user{
    color: var(--czcionka-bialy);
    width: var(--rozmiar-3xl);
    height: var(--rozmiar-3xl);
    padding: var(--rozmiar-xxs);
}



.header__przycisk{
    color: var(--czcionka-bialy);
    background-color: var(--tlo-czerwony);
    width: var(--rozmiar-5xl);
    height: var(--rozmiar-5xl);
    border: 0;
    display: block;
    display: none;
}


.header__rozwiniecie{
    padding: 0 18px;
    width: 100%;
    display: none;
    background-color: var(--kolor-kremowy);
}

.header__lista li{
    display: flex;
    justify-content: center;
    align-items: center;
}

.header__lista a{
    color: var(--czcionka-bialy);
}

.header__lista a:hover{
    color: var(--tlo-szary);
}

</style>