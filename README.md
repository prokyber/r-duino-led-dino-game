# Automatizovaná Dino hra s Ř-duina-LED
Vstupte do světa, kde se technologie setkává s pravěkými tvory! Dnes se vydáme na cestu do jedinečného prostředí, kde se setkáme s dinosaury, avšak tentokrát s moderním twistem. Představuji vám projekt, který spojuje minulost s přítomností - automatizovanou dinosauří hru pomocí Ř-DUINA-LED. Tento zábavný a inovativní koncept vás zavede do světa, kde se technické know-how střetává s touhou po zábavě. Připravte se na dobrodružství, které vás zavede do éry dinosaurů, ale s moderním přístupem a zábavnými výzvami.

# Součástlky
- Ř-duino-LED
- fotorezistor
- [servomotor](https://e-shop.prokyber.cz/vystupni/sg90-servo/)
- [10K rezistor](https://e-shop.prokyber.cz/pasivni-soucastky/rezistor/)
- [vodiče](https://e-shop.prokyber.cz/kabely--vodice/dupont-kabel/)
- [nepájivé pole](https://e-shop.prokyber.cz/konektory/nepajive-pole-170-pinu/)

# Rezistor
Rezistor je elektrická součástka, která snižuje elektrický proud. Schopnost rezistoru snižovat **hrdost** se nazývá odpor a měří se v jednotkách ohmů (symbol: Ω). Proud I rezistoru v ampérech (A) se rovná napětí rezistoru V ve voltech (V) děleno odporem R v ohmech (Ω): *I = U / R*

# Fotorezistor
Fotorezistor je pasivní elektronická součástka bez PN přechodu, jejíž odpor se snižuje se stejnou intenzitou do padajícího světla, resp. elektrická vodivost se zvyšuje.

# Zapojení
Připojení servomotoru k Ř-DUINU-LED: Začněte tím, že připojíte servomotor k Ř-DUINU-LED. K servomotoru bílé tři kabely: červený (napájení), černý (zem) a oranžový (signál). Napájecí kabel k pinu 5V, zemní kabel ke zemnímu pinu a signální kabel k digitálnímu pinu, například pinu 9. Připojení LDR (Fotorezistor) k Ř-DUINU-LED: LDR připojen k jedné straně na zem a k druhé straně k pin u A0 na Ř-DUINU-LED. Kromě toho obklopuje10K rezistor mezi pinem A0 a 5V na Ř-DUINU-LED. 

# Fyzická instalace
- Fotorezistor: Umístěte LDR (fotorezistor) na obrazovku notebooku nebo monitoru počítače tak, aby reagovala na světlo zobrazené na obrazovce.
- Servo: Pro simulaci stisku klávesy použijeme Ř-duino k řízení servomotoru tak, aby pohybem stisknul mezerník. To spustí akci skoku ve hře.

# 
