# 🧩 Přiřazovačka

Výuková aplikace pro iPad a interaktivní tabuli: učitel si vytvoří vlastní přiřazovací
úlohy (pozadí, cílové zóny, obrázky) a dítě je řeší přetahováním obrázků prstem.

**Spuštění:** otevřete https://valsorims.github.io/prirazovacka/ v Safari nebo jiném
prohlížeči. Na iPadu doporučujeme Sdílet → *Přidat na plochu* — aplikace pak běží
na celou obrazovku a funguje i offline se scénáři, které už jsou v zařízení uložené.

**📖 Návod pro učitele:** https://valsorims.github.io/prirazovacka/navod.html
(tisknutelný, odkaz je i v aplikaci v režimu učitele)

- **Režim učitele** se otevírá podržením tlačítka „🔧 Pro učitele“ (1,2 s).
- Scénáře a výsledky se ukládají lokálně v prohlížeči daného zařízení (IndexedDB);
  mezi zařízeními se přenášejí přes Export / Nahrát scénář ze souboru.
- Vyhledávání obrázků používá knihovnu piktogramů [ARASAAC](https://arasaac.org)
  (autor Sergio Palao, vlastník Gobierno de Aragón, licence CC BY-NC-SA).

Celá aplikace je jediný soubor `index.html` bez závislostí.
