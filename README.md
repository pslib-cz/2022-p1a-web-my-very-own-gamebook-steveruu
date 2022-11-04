# Oprava testu na odkazy mezi soubory

## Zadání

Vytvořte svůj vlastní gamebook pomocí HTML a odkazů mezi soubory. Vytvořte stránky, prolinkujte je podle potřeby tak, aby byly splněny podmínky zadání.

## Struktura souborů

Příklad struktury souborů. Složky vytvořte a nazvěte podle potřeb příběhu.

Složka projektu

* zona1
    * misto1
        * index.html
        * lokace1.html
        * lokace2.html
    * misto2
        * index.html
        * mistoVMiste2
            * index.html
            * lokace1.html
* zona2
    * misto1
        * index.html
* images
    * image1.jpg
    * image1.jpg
* index.html

## Podmínky splnění

* hra obsahuje alespoň 8 míst
* příběh je libovolný, ale obsahuje větvení
* struktura složek má v jednom místě alespoň tři úrovně
* existuje odkaz z jedné větve do druhé (například z *zona1/misto1/lokace2.html* do *zona2/misto1/index.html*)
* každá lokace má odpovídající obrázek ze složky */images*
* soubory jsou správně pojmenované - tj. bez diakritiky, mezer, je použit index.html
* cely web (gamebook) je uložen do námi poskytnutého repozitáře pomocí VS Code a commit+push
* stránky jsou validní
