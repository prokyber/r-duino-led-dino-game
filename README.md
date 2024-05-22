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
![Rezistor](https://github.com/prokyber/r-duino-led-dino-game/blob/main/img/Rezistor.jpg)

Rezistor je elektrická součástka, která snižuje elektrický proud. Schopnost rezistoru snižovat **hrdost** se nazývá odpor a měří se v jednotkách ohmů (symbol: Ω). Proud I rezistoru v ampérech (A) se rovná napětí rezistoru V ve voltech (V) děleno odporem R v ohmech (Ω): *I = U / R*

# Fotorezistor
| <img alt="fotorezistor" src="https://github.com/prokyber/r-duino-led-dino-game/blob/main/img/Foto_s-1.jpg" style="Height: 35vh;"> | <img alt="fotorezistor schéma" src="https://github.com/prokyber/r-duino-led-dino-game/blob/main/img/Foto_s-2.jpg" style="Height: 35vh;"> |
| ---- | ---- |

Fotorezistor je pasivní elektronická součástka bez PN přechodu, jejíž odpor se snižuje se stejnou intenzitou do padajícího světla, resp. elektrická vodivost se zvyšuje.

# Zapojení
Připojení servomotoru k Ř-DUINU-LED: Začněte tím, že připojíte servomotor k Ř-DUINU-LED. K servomotoru bílé tři kabely: červený (napájení), černý (zem) a oranžový (signál). Napájecí kabel k pinu 5V, zemní kabel ke zemnímu pinu a signální kabel k digitálnímu pinu, například pinu 9. Připojení LDR (Fotorezistor) k Ř-DUINU-LED: LDR připojen k jedné straně na zem a k druhé straně k pin u A0 na Ř-DUINU-LED. Kromě toho obklopuje10K rezistor mezi pinem A0 a 5V na Ř-DUINU-LED. 

# Fyzická instalace
![Fotorezistor nalepený na displeji](https://github.com/prokyber/r-duino-led-dino-game/blob/main/img/foto_s-3.jpg)
- Fotorezistor: Umístěte LDR (fotorezistor) na obrazovku notebooku nebo monitoru počítače tak, aby reagovala na světlo zobrazené na obrazovce.

![servo na mezerníku](https://github.com/prokyber/r-duino-led-dino-game/blob/main/img/servo.jpg)
- Servo: Pro simulaci stisku klávesy použijeme Ř-duino k řízení servomotoru tak, aby pohybem stisknul mezerník. To spustí akci skoku ve hře.

# Spuštěni hry Dino
Když se uživatel pokusí v offline režimu v prohlížeči Google Chrome navštívit webovou stránku, prohlížeč jej upozorní, že není připojen k internetu, a na stránce se zobrazí ilustrace pixelovaného Tyrannosaura rexe.Hru je poté možné spustit stisknutím klávesy space 

# Ladění
Optimalizace citlivosti LDR: Experimentujte s umístěním LDR na obrazovce a hodnotou prahu (threshold) v kódu tak, aby reakce byla přesná a spolehlivá. Nastavte citlivost tak, aby reagovala pouze na černou barvu na obrazovce. 

Kalibrace servomotoru: Ujistěte se, že servomotor se pohybuje tak, jak je očekáváno, a že simulace stisku tlačítka mezerníku je dostatečně rychlá a přesná. Případně upravte úhel pohybu servomotoru podle potřeby. 

Testování v reálném prostředí: Spusťte hru Dino a prověřte, jak se chová automatizovaný systém ve skutečném provozu. Ujistěte se, že reakce na pohyb postavy je synchronizovaná a že hra je hratelná a zábavná. 

Feedback a ladění: Pokud zjistíte nějaké nedostatky nebo nedostatky ve funkci hry, provedete potřebné úpravy v kódu a zkuste znovu. Poskytněte zpětnou vazbu a optimalizujte projekt tak, aby byl co nejlepší. 

# Závěr
Vytvoření automatizované dinosauří hry pomocí Ř-duina-LED je nejen zábavný a zajímavý projekt, ale také skvělý způsob, jak propojit technologii s herním světem a vyzkoušet možnosti kreativního využití elektroniky. Během procesu jsme se naučili připojovat a programovat Ř-duina-LED, pracovat s různým i senzory a motorizovanými zařízeními a zajistit jejich funkci pro dosažení požadovaného výsledku. Tato hra není jen o zábavě, ale také o výzvě. Průběžné ladění a optimalizace byly klíčové kroky k dosažení plynulého a spolehlivého provozu. Navíc tato hra může sloužit jako inspirace pro další projekty, které kombinují hardware a software k vytvoření interaktivních a zábavných zážitků. Doufám, že tento projekt přinesl nejen radost z jeho vytváření, ale také přinesl nové poznatky a dovednosti v oblasti elektroniky a programování. Ať už jste začátečníkem nebo zkušeným nadšencem, vytváření podobných projektů může být zábavným a poučným způsobem, jak trávit čas a podporovat svou kreativitu a technické dovednosti. Nyní je na čase se ponořit do hry a užít si výsledek své práce. Ať vám vaše automatizovaná dinosauří hra přinese hodně radosti a zábavy! 
