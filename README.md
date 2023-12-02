## Nábytek XXXMuck

<details>
  <summary><b>Detail</b></summary>

  **DŮLEŽITÉ: Nejedná se o žádnou spolupráci ani nic podobného!**

  Jedná se projekt sloužící k zopakování znalostí z kurzu React1 od Czechitas.
  Je postaven na **Vite** balíčku.
  
  Pro spuštění projektu stačí v terminálu zadat příkaz:
  **npm run dev**

  Následně se v terminálu zobrazí adresa. Aby ji bylo možné v prohlížeči zobrazit, je nutné při kliku na na ní držet **ctrl/cmd**.

  Originální zadání projektu:
  Vyrobte v Reactu jednoduchý e-shop pro nový nábytkový řetězec XXXMuck. Web bude sestávat ze dvou stránek: nabídka produktů a detail produktu.

  1. Pomocí **npm init kodim-app@latest** xxxmuck vytvořte základ webové aplikace.
  2. Prohlédněte si [design hlavní stránky](https://kodim.cz/cms/assets/vyvoj-webu/react-2/lekce/opakovani/projektik/xxxmuck/homepage.png) obchodu. Nemusíte jej přesně dodržet, stačí jej brát jako inspiraci. Než začnete programovat, rozvrhněte si strukturu stránky do srozumitelně pojmenovaných komponent. Hlavní stránka nechť je celá obsažena v komponentě **HomePage**.
  3. Prostudujte si výstup následujicícho [API endpointu](https://apps.kodim.cz/react-2/xxxmuck/products), který vrací seznam produktů ve formátu JSON.
  4. Vytvořte jednotlivé komponenty a sestavte z nich výslednou stránku. Data pro jednotlivé produkty načtěte z API.
  5. Pomocí příkazu **npm install react-router-dom** nainstalujte React Router.
  6. Přidejte do vašeho projektu routování. Komponenta **HomePage** bude mít cestu **/**.
  7. Vytvořte zatím prázdnou komponentu **ProductPage** u zapojte ji pod cestu **/product**.
  8. Dotvořte komponentu **ProductPage** dle [dodaného designu](https://kodim.cz/cms/assets/vyvoj-webu/react-2/lekce/opakovani/projektik/xxxmuck/productpage.png).
  9. Zařiďte, že po kliknutí na produkt na hlavní stránce se zobrazí stránka zatím prázdná **ProductPage** bez produktu.
  10. Na **ProductPage** zobrazte vybraný produkt. K tomu je potřeba si předat **id** produktu v URL stránky a použít hook **useParams**. Jednotlivé produkty pod jejich **id** najdete na [tomto endpointu](https://apps.kodim.cz/react-2/xxxmuck/products/2c6VoCaD). Tlačítko pro obejdnání zatím nebude funkční.


</details>

## Furniture XXXMuck

<details>
  <summary><b>Detail</b></summary>

  **IMPORTANT: This is not a collaboration or anything like that!**

  This is a private website project, built on the Webpack package for package management and project launching. 
  
  To start the project, just type the following command in the terminal:
  **npm run start**

  This will then open a new panel in the browser where the page will be displayed.

</details>

