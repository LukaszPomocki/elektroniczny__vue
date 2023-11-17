<template>
  <footer>
      <div class="footer-kontener">
        <h4>Produkty</h4>
        <ul>
          <li><a href="#" class="footer-link">Telefony i Smartwatche</a></li>
          <li><a href="#" class="footer-link">RTV i Telewizory</a></li>
          <li><a href="#" class="footer-link">Komputery i Tablety</a></li>
          <li><a href="#" class="footer-link">Gaming</a></li>
          <li><a href="#" class="footer-link">AGD</a></li>
          <li><a href="#" class="footer-link">AGD do zabudowy</a></li>
          <li><a href="#" class="footer-link">AGD małe</a></li>
          <li><a href="#" class="footer-link">Foto i Kamery</a></li>
          <li><a href="#" class="footer-link">Pojazdy elektryczne</a></li>
          <li><a href="#" class="footer-link">Sport i rekreacja</a></li>
          <li><a href="#" class="footer-link">Strefa Rodzica</a></li>
          <li><a href="#" class="footer-link">Klimatyzacja i Wentylacja</a></li>
          <li><a href="#" class="footer-link">Marki własne</a></li>
</ul>
      </div>

      <div class="footer-kontener">
        <h4>Na skróty</h4>
        <ul>
          <li><a href="#" class="footer-link">Aktualności</a></li>
          <li><a href="#" class="footer-link">Klub</a></li>
          <li><a href="#" class="footer-link">Pomoc</a></li>
          <li><a href="#" class="footer-link">Dla Firm</a></li>
          <li><a href="#" class="footer-link">Leasing</a></li>
          <li><a href="#" class="footer-link">Karty Podarunkowe</a></li>
          <li><a href="#" class="footer-link">Tax free</a></li>
          <li><a href="#" class="footer-link">Ogólne warunki umowy sprzedaży</a></li>
          <li><a href="#" class="footer-link">Polityka prywatności</a></li>
          <li><a href="#" class="footer-link">Polityka Prywatności Cookies</a></li>
          <li><a href="#" class="footer-link">Regulamin sklepu internetowego</a></li>
          <li><a href="#" class="footer-link">Fałszywe promocje</a></li>
          <li><a href="#" class="footer-link">Reklamacja produktu</a></li>
          <li><a href="#" class="footer-link">Sprawdź status reklamacji</a></li>
          <li><a href="#" class="footer-link">Sprawdź status zamówienia</a></li>
          <li><a href="#" class="footer-link">Zwrot produktu</a></li>
          <li><a href="#" class="footer-link">Zarządzaj ciasteczkami</a></li>
        </ul>
      </div>
      <div class="footer-kontener">
        <h4>Strefa marek</h4>
        <ul>
          <li><a href="#" class="footer-link">Sklep Apple</a></li>
          <li><a href="#" class="footer-link">Sklep Xiaomi</a></li>
          <li><a href="#" class="footer-link">Sklep Bosch</a></li>
          <li><a href="#" class="footer-link">Sklep DeLonghi</a></li>
          <li><a href="#" class="footer-link">Sklep DJI</a></li>
          <li><a href="#" class="footer-link">Sklep Dyson</a></li>
          <li><a href="#" class="footer-link">Sklep Hama</a></li>
          <li><a href="#" class="footer-link">Sklep Huawei</a></li>
          <li><a href="#" class="footer-link">Sklep Miele</a></li>
          <li><a href="#" class="footer-link">Marki własne</a></li>
          <li><a href="#" class="footer-link">Sklep Samsung</a></li>
        </ul>
      </div>

      <div class="footer-kontener">
        <h4>Firma</h4>
        <ul>
          <li><a href="#" class="footer-link">O nas</a></li>
          <li><a href="#" class="footer-link">Informacje prasowe</a></li>
          <li><a href="#" class="footer-link">Zrównoważony rozwój - BetterWay</a></li>
          <li><a href="#" class="footer-link">Compliance</a></li>
          <li><a href="#" class="footer-link">Prawa człowieka i ochrona środowiska - zgłaszanie skarg</a></li>
          <li><a href="#" class="footer-link">Kariera</a></li>
          <li><a href="#" class="footer-link">Reklama</a></li>
          <li><a href="#" class="footer-link">Strategia podatkowa</a></li>
          <li><a href="#" class="footer-link">IODO</a></li>
          <li><a href="#" class="footer-link">Cyber Security</a></li>
          <li><a href="#" class="footer-link">Zasady plasowania</a></li>
          <li><a href="#" class="footer-link">UOKiK Ogłoszenie ISY ITS 2000</a></li>
        </ul>
      </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style>
footer{
    display: flex;
    flex-wrap: wrap;
    background-color: var(--czcionka-bialy);
    border-top: 1px solid var(--tlo-szary);
    }

    .footer-kontener{
        width: 25%;
    }
    .footer-kontener ul, h4{
      padding-left: 1rem;
    }

    .footer-link{
        color: var(--czcionka-czarny);
        transition: color 0.3s;
        display: flex;
        padding: 0.125rem;
    }

    .footer-link:hover{
        color: var(--tlo-czerwony);
        text-decoration: underline;
    }

@media (max-width: 475px) {
}

@media (max-width: 640px) {
    .footer-link{
        font-size: var(--rozmiar-xs);
    }
}

@media (max-width: 768px) {
.footer-link{
    font-size: var(--rozmiar-sm);
}
.footer-kontener{
    width: 50%;
}
}

@media (max-width: 1024px) {
}
</style>