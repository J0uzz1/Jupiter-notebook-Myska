# FLOW ACCUMULATION - Analýza toku vody v digitálním modelu terénu 
## **POZOR!**
**Pro fungování tohoto Jupiter notebooku je nutné naimportovat přiložené conda prostředí enviroment_m.yml**
### Jak naimportovat Conda prostředí do svého zařízení:
1. **Stáhněte si soubor s prostředím**
   Ujistěte se, že jste obdrželi soubor `environment_m.yml`.
2. **Otevřete příkazový řádek**
   Otevřete příkazový řádek (konzoli) na svém zařízení. Pokud máte v zařízení Anaconda Promt použijte jej.
3. **Přejděte do správné složky**
   Pomocí příkazu `cd` přejděte do složky, kde jste uložili soubor `environment.yml`.
4. **Vytvořte Conda prostředí**
   Spusťte následující příkaz pro vytvoření Conda prostředí z uloženého souboru:
    ```
    conda env create -f environment.yml
    ```
    Tento příkaz nainstaluje všechny potřebné balíčky do nového Conda prostředí podle specifikací ve souboru `environment.yml`.
5. **Aktivujte nové Conda prostředí**
   Aktivujte nově vytvořené Conda prostředí pomocí příkazu:
    ```
    conda activate nazev_prostredi
    ```
    Kde `nazev_prostredi` je jméno nově vytvořeného Conda prostředí.
6. **Připojte se k novému prostředí**
   Při vytváření nového notebooku vyberte nově vytvořené Conda prostředí z nabídky prostředí kernelu. Pokud jste prostředí správně nainstalovali, mělo by být k dispozici ve vaší nabídce.

## Popis: 
Tento projekt zahrnuje skript napsaný v jazyce Python pro analýzu toku vody v digitálním modelu terénu (DEM) pomocí knihovny pysheds. Projekt se skládá z několika částí, které zahrnují načtení a zpracování DEM, definování směrů toku, výpočet akumulace toku, vizualizaci výsledků a další analýzy. 
## Obsah: 
- **FLOW_ACCUMULATION.ipynb**: Jupyter notebook obsahující kompletní kód pro analýzu toku vody v digitálním modelu terénu.
- **dem1-3.tif**: Vzorové soubory digitálního modelu terénu (DEM) ve formátu GeoTIFF použitý v analýze.
- **enviroment_m.yml**: Conda prostředí nutné pro správné fungování notebooku.
## Knihovny: 
numpy - pysheds.grid - matplotlib.pyplot - matplotlib.colors - matplotlib.patches - seaborn - rasterio 
## Spuštění: 
Pro spuštění skriptu je nejprve nutné mít nainstalované všechny použité knihovny. Poté lze spustit každou buňku v Jupyter notebooku postupně od začátku, nebo vybrané části kódu podle potřeby. 
## Autor: 
Josef Myška
## Kontakt: 
Pro jakékoliv dotazy nebo připomínky můžete kontaktovat na myska-josef@seznam.cz.
## Poznámky: 
Tento projekt byl vytvořen jako součást předmětu PRODA a to jako semestrální práce. 
