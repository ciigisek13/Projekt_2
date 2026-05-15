# Druhý ročníkový projekt
## Cíl projektu
Cílem projektu je vytvořit zařízení, které bude testovat naše reakce. Zařízení v náhodných intervalech rozsvítí LED diodu a úkolem je co nejrychleji stisknout tlačítko.
## Hardware
- Raspberry Pi Pico w 2
- Micro USB kabel
- Breadboard
- LED dioda
- Rezistor
- Tlačítko
- Propojovací dráty
## Software
- Thonny IDE
- CircuitPython
## Porovnání
### DIY
- Levnější
- Otevřený systém, možnost si cokoliv doprogramovat
- Připojení pomocí Wi-Fi
- Potřeba ho sám sestavit
### Komerční
- Dražší (+-5000,-)
- Uzavřený systém
- Připojení přes bluetooth
- Jednoduché pro běžné uživatele
 ![blazepod](blazepod.webp)
 ![blazepod](blazepod2.jpg)
### Shrnutí
DIY verze se vyplatí po finanční stránce, ale na komerční verzi je vidět, že je více robustní a vhodná pro mnoho typů tréninků, takže záleží na našich schopnostech a kreativitě a tom jak by sme chtěli tento reakční senzor využít. Pokud by to bylo na kvalitní trénink, tak by se vyplatilo samozřejmě komerční zařízení.
Pokud je někdo kutil a chce pouze nějaký zajimavý projekt a není to seriozní trenér tak se samozřejmě vyplatí si ho vytvořit sám doma.
## Postup práce
- Zapojíme Pico do breadboardu
- V Picu užmáme nahraný CircuitPython, takže nám to ulehčí práci
- Zapojíme LED diodu anodou přes rezistor a katodou na zem
- Poté připojíme tlačítko k jednomu pinu a poté na zem
- K vytvoření kódu jsem použil AI, jelikož nemám takové skušenosti s kódováním
 ![kodik](reakce.png)
 ![kodik2](reakce2.png)
## Stav projektu
Projekt mám pouze jako návod jak toto zařízení udělat, sám sem ho nevytvořil. Pokud bych v budoucnu chtěl toto vytvořit tak můžu využít tento projekt jako návod.
## Proč právě zařízení na měření reakčního času
Při tréninku jsme hráli hru, kde byla důležitá rychlost a právě naše reakce, tak mě přislo že bych se podíval po internetu jestli existuje něco, co pomáho zlepšovat reakci a narazil sem na BlazePod a přišlo mi to zajímavé, ale poté, co jsem viděl cenovku tak sem si křekl jestli by nebylo lepší si to zkusit vyrobit doma.
# Citace
BlazePod. Online. In: . Dostupné z: https://eshop.3dfitness.cz/blazepod-standard-kit/. [cit. 2026-05-15].
BlazePod Training. Online. In: . Dostupné z: https://www.blazepod.com/blogs/all/5-reasons-blazepod-is-the-ultimate-reaction-training-platform?srsltid=AfmBOoqubukJ-0iQhTMt1HR5dBqbpw83zlyq6ICFGrzDhZDG1ZX3CM07. [cit. 2026-05-15].
GOOGLE. Google Gemini. Online. Dostupné z: https://gemini.google.com/app?hl=cs. [cit. 2026-05-15].
MicroPython. Online. Dostupné z: https://micropython.org. [cit. 2026-05-15].
BlazePod Reaction Lights. Online. Dostupné z: https://blazepod.eu. [cit. 2026-05-15].
