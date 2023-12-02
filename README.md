## Nábytek XXXMuck (CZ)

<details>
  <summary><b>Detail</b></summary>

  **Jedná se projekt na začátku kurzu React2. Slouží k zopakování znalostí z kurzu React1 od Czechitas.**
  **Je postaven na Vite balíčku.**
  
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

## Furniture XXXMuck (EN)

<details>
  <summary><b>Detail</b></summary>

   **This is project was at the beginning of the React2 course. It is used to review the knowledge from the React1 course created by Czechitas.**
   **For the project Vite package is used.**

   To start the project, just enter the following command in the terminal:
   **npm run dev**

   The address is then displayed in the terminal. To view it in the browser, you must hold **ctrl/cmd** while clicking on it.

   Assignment:
   Make a simple e-shop in React for the new furniture chain XXXMuck. The website will consist of two pages: products offer and product detail.

  1. Use **npm init kodim-app@latest** xxxmuck to create the basic structure of the web application.
  2. Review the [main page design](https://kodim.cz/cms/assets/vyvoj-webu/react-2/lekce/opakovani/projektik/xxxmuck/homepage.png) of the store. You don't have to follow it exactly, just take it as inspiration. Before you start coding, break down the structure of the page into clearly named components. Let the home page be contained entirely in the **HomePage** component.
  3. Study the output of the following [API endpoint](https://apps.kodim.cz/react-2/xxxmuck/products), which returns a list of products in JSON format.
  4. Create the individual components and build the resulting page from them. Retrieve the data for each product from the API.
  5. Use the **npm install react-router-dom** command to install React Router.
  6. Add routing to your project. The **HomePage** component will have the path **/**.
  7. Create an empty **ProductPage** component and have it under the **/product** path.
  8. Complete the **ProductPage** component according to the [provided design](https://kodim.cz/cms/assets/vyvoj-webu/react-2/lekce/opakovani/projektik/xxxmuck/productpage.png).
  9. When you click on a product on the main page, the **ProductPage** will be displayed without the product yet.
  10. Display the selected product on the **ProductPage**. To do this, you need to pass the **id** of the product in the URL of the page and use the **useParams** hook. You can find individual products under their **id** at [this endpoint](https://apps.kodim.cz/react-2/xxxmuck/products/2c6VoCaD). The ordering button will not work yet.
   

</details>

