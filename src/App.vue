<template>
  <router-view/>
</template>

<style>
html, body{
  padding: 0;
  margin: 0;
}

ul{
  list-style-type: none;
  padding: 0;
}
   
a{
  text-decoration: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}


nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

@media (max-width: 475px) {
    .header-placeholder{
        font-size: var(--rozmiar-xs);
    }



}

@media (max-width: 640px) {

    header{
        margin-top: -2rem;
        padding-bottom: var(--rozmiar-xxs);
        flex-direction: column;
    }

    .header__przycisk{
        display: block;
    }
    

    .menu-przycisk{
        display: none;
    }

    .header-placeholder{
        min-width: 50vw;
    }

    .nav__lista{
        flex-direction: column;
        gap: 0.5em;
    }

    .nav__lista li{
        margin: var(--rozmiar-xxs);
    }

    .footer-link{
        font-size: var(--rozmiar-xs);
    }

    .main-lewy{
        display: none;
    }

    .main-prawy{
        width: 90%;
        margin-top: 9em;
        margin-left: 1.7em;
    }   

    .artykuly-cena h1{
        font-size: var(--rozmiar-2xl);
    }

    .artykuly-statystyki{
        margin-left: 1em;
    }

    nav{
        display: none;
    }
}

@media (max-width: 768px) {
.header-link{
    font-size: var(--rozmiar-sm);
}

.Menu-bottom{
    padding: var(--rozmiar-sm);
    font-size: var(--rozmiar-sm);
}

/* nav */
nav{
    padding-top: 7em;
    padding-bottom: var(--rozmiar-xxs);
}

.menu-przycisk{
    display: none;
}

.header-lista{
    gap: 1em;
}

.footer-link{
    font-size: var(--rozmiar-sm);
}
/* main */
main{
    display: flex;
    flex-direction: column;
}

.main-lewy{
    width: 70%;
    margin: var(--rozmiar-xl);
}

.sortowanie-lewe{
    margin-left: var(--rozmiar-xxs);
}

.wraper-dol{
    display: flex;
    flex-direction: column;
}

}

@media (max-width: 1024px) {
    
    
}
</style>
