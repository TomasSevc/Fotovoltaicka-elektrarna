# Fotovoltaický systém s bateriovým úložištěm

## Cíl projektu

Cílem tohoto projektu je navrhnout a popsat fotovoltaický systém s bateriovým úložištěm, který umožňuje výrobu elektrické energie ze slunečního záření, její ukládání do baterií a následné využití v domácnosti.

---

## Použité komponenty

### Fotovoltaické panely

* **24 ks** pevných solárních panelů **IBC MonoSol 400 Wp**
* Zapojení: **2× (6 + 6) paralelně**
* Celkový instalovaný výkon: **9,6 kWp**

* https://github.com/user-attachments/files/24242180/2005800014_IBC.MonoSol.400.GS10-HC.Black_Data.sheet.Europe.%2B.Japan_EN-2.3.pdf)

### Regulace a měniče

* **2 ks** regulátor **MPPT 250 V / 100 A**
* **3 ks** střídač **Victron MultiPlus II**

  * Napětí: 48 V
  * Výkon: 3000 VA
  * Provedení: 1f
 
  * regulátor: https://www.abctech.cz/mppt-solarni-regulator-victron-energy-smartsolar-250-100-tr-ve-can_d39297.html
  * měnič: https://www.abctech.cz/menic-nabijecka-victron-energy-multiplus-ii-48v-3000va-35a-32a_d39244.html

### Akumulace energie

* **3 ks** baterie **PylonTech US3000C**

  * Napětí: 48 V
  * Kapacita: 3,6 kWh
* Zapojení baterií: **paralelní**
* Celková kapacita úložiště: **10,8 kWh**

* baterie: https://www.fvtservis.cz/baterie-pylontech-us3000c-48v-3-6kwh--74-ah/

  ### Monitorování a řízení systému
* **1 ks** Victron Energy Cerbo GX MKII
  * Funkce: centrální monitorování a řízení FV systému
  * Sledování výroby, spotřeby a stavu baterií v reálném čase
  * Možnost vzdáleného přístupu přes Victron Remote Management (VRM)
    
  * https://www.abctech.cz/victron-energy-cerbo-gx-mkii_d41479.html

### Další komponenty

* DC rozvaděč
* AC rozvaděč

---

## Postup realizace

### 1. Příprava objektu

* Kontrola stávající elektroinstalace objektu
* Ověření možností připojení fotovoltaického systému

### 2. Montáž nosné konstrukce a panelů

* Instalace nosné konstrukce pro solární panely
* Osazení **24 ks** solárních panelů IBC MonoSol 400 Wp
* Celkový instalovaný výkon: **9,6 kWp**
* Vodivé připojení konstrukce a rámů panelů na hlavní ochrannou pospojovací svorkovnici objektu (uzemnění a vyrovnání potenciálů)

### 3. Provedení stejnosměrných (DC) rozvodů

* Realizace DC vedení mezi fotovoltaickými panely a regulátory MPPT
* Zapojení panelů do čtyř stringů po šesti panelech

### 4. Instalace regulátorů MPPT

* Instalace **2 ks MPPT regulátorů** v technické místnosti
* Optimalizace výkonu FV pole
* Řízení nabíjení akumulačního systému
* Zapojení dle projektové dokumentace a technických požadavků výrobce

### 5. Instalace střídače a regulace výkonu

* Instalace **střídačů Victron MultiPlus II** v technické místnosti
**Slouží k:**
 
* Přeměně stejnosměrného napětí na střídavé
* Řízení toku energie mezi:

  * fotovoltaickými panely
  * bateriovým úložištěm
  * elektroinstalací objektu
  * distribuční sítí

### 6. Instalace akumulačního systému

* Instalace **3 ks baterií PylonTech US3000C**
* Paralelní zapojení baterií
* Celková kapacita akumulace: **10,8 kWh**

### 7. Instalace a konfigurace monitorovací jednotky
- Instalace Victron Energy Cerbo GX MKII v technické místnosti
- Připojení ke střídačům, regulátorům a bateriovému úložišti
- Konfigurace pro sledování výroby, spotřeby a stavu baterií v reálném čase
- Nastavení vzdáleného přístupu přes portál Victron Remote Management (VRM) pro monitorování a řízení systému

### 8. Rozvaděče a řízení výkonu

* Osazení podružného rozvaděče FVE
* Zajištění distribučního řízení výkonu výrobny

### 9. Ochrana, revize a uvedení do provozu

* Zajištění ochrany a bezpečnosti provozu systému
* Provedení výchozí revize
* Uvedení fotovoltaické elektrárny do provozu

  # Doplňující části projektu fotovoltaického systému

## Doporučené zdroje informací
- Technická dokumentace Victron Energy
- Technická dokumentace PylonTech
- Portál Victron Remote Management
- Normy a doporučení pro instalaci fotovoltaických systémů
- Odborné články o fotovoltaice a bateriových úložištích
- Vědomosti mého otce
---

# Výpočty a dimenzování systému

## Výkon fotovoltaických panelů
Použité panely:
- 24× IBC MonoSol 400 Wp

Výpočet celkového výkonu:

24 × 400 Wp = 9600 Wp = 9,6 kWp

Celkový instalovaný výkon fotovoltaické elektrárny je tedy 9,6 kWp.

## Kapacita bateriového úložiště
Použité baterie:
- 3× PylonTech US3000C
- Kapacita jedné baterie: 3,6 kWh

Výpočet celkové kapacity:

3 × 3,6 kWh = 10,8 kWh

Celková kapacita bateriového úložiště je 10,8 kWh.

## Odhad denní výroby energie
Při dobrých podmínkách může fotovoltaický systém v letních měsících vyrobit přibližně:

9,6 kWp × 5 h = 48 kWh za den

V zimních měsících je výroba výrazně nižší kvůli kratším dnům a nižší intenzitě slunečního záření.

## Výhody bateriového úložiště
Bateriové úložiště umožňuje:
- ukládání přebytečné energie
- využití energie ve večerních hodinách
- snížení odběru energie z distribuční sítě
- částečnou energetickou nezávislost

---

# Zdůvodnění volby komponent

## Fotovoltaické panely
Byly zvoleny panely IBC MonoSol 400 Wp kvůli:
- vysokému výkonu
- dobré účinnosti
- dlouhé životnosti
- vhodnému poměru cena/výkon

## Střídače Victron MultiPlus II
Tyto střídače byly vybrány díky:
- vysoké spolehlivosti
- možnosti spolupráce s bateriovými systémy
- možnosti záložního napájení
- pokročilému monitorování systému

## Baterie PylonTech US3000C
Baterie byly zvoleny kvůli:
- bezpečné technologii LiFePO4
- dlouhé životnosti
- možnosti paralelního rozšíření
- komunikaci se systémem Victron

---

# Spotový trh a přetoky

Spotový trh umožňuje nákup a prodej elektrické energie podle aktuální ceny elektřiny. Cena se během dne mění podle výroby a spotřeby energie.

Přetoky vznikají v případě, kdy fotovoltaická elektrárna vyrábí více energie, než objekt aktuálně spotřebuje. Přebytečná energie může být:
- uložena do baterií
- dodána do distribuční sítě
- omezena regulací výkonu

Moderní systémy umožňují řízení přetoků a optimalizaci spotřeby energie podle aktuálních cen elektřiny.

---

# Bezpečnost práce a požární bezpečnost

## Bezpečnost při montáži
Při montáži fotovoltaického systému je nutné dodržovat:
- použití ochranných pomůcek při práci ve výškách
- bezpečnost práce na elektrických zařízeních
- používání vhodného nářadí a ochranných prostředků
- správné odpojení systému při servisních pracích

## Požární bezpečnost
Fotovoltaický systém musí obsahovat:
- správné jištění DC i AC části
- přepěťové ochrany
- kvalitní uzemnění
- správně dimenzované kabely
- možnost bezpečného odpojení systému

Bateriové úložiště musí být umístěno v dobře větraném prostoru a instalováno podle požadavků výrobce.

---

# Možné problémy a jejich řešení

## Přehřívání komponent
Řešení:
- dostatečné chlazení
- správné umístění zařízení
- pravidelná kontrola systému

## Pokles výroby panelů
Příčiny:
- znečištění panelů
- zastínění
- poškození panelu

Řešení:
- pravidelné čištění panelů
- kontrola stavu systému

## Výpadek systému
Řešení:
- kontrola jištění
- kontrola komunikace mezi zařízeními
- diagnostika pomocí Victron Cerbo GX

---

# Závěr

Fotovoltaický systém s bateriovým úložištěm představuje moderní způsob výroby elektrické energie z obnovitelných zdrojů. Díky akumulaci energie do baterií lze efektivně využívat vyrobenou energii i v době, kdy fotovoltaické panely nevyrábějí dostatek energie.

Použitý systém Victron a baterie PylonTech umožňují spolehlivý provoz, monitorování a možnost dalšího rozšíření systému v budoucnosti. Projekt mi umožnil lépe pochopit návrh, zapojení a fungování fotovoltaických elektráren v praxi.

---
**Poděkování**

Na závěr bych chtěl poděkovat svému otci za přizvání k realizaci projektu fotovoltaického systému,
možnost nahlédnout do návrhu a praktické realizace a za cenné praktické zkušenosti.


Dále děkuji asistenčnímu nástroji ChatGPT za pomoc při formulaci textů a strukturování projektu.

