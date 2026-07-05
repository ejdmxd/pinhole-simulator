# Simulátor dírkové komory (Camera Obscura)

Interaktivní webový nástroj pro návrh a pochopení fungování dírkové komory. Umožňuje bez nutnosti fyzického prototypování prozkoumat, jak parametry krabice a dírky ovlivňují výslednou fotografii.

## ⚙️ Funkce
* **Výpočet optiky v reálném čase:** Automaticky počítá zorný úhel, clonové číslo a optimální průměr dírky (Rayleighovo kritérium).
* **Dynamický náhled:** Plátno (Canvas) vykresluje scénu a aplikuje na ni simulovanou neostrost, ořez a expozici podle zadaných parametrů.
* **Kalkulačka expozice:** Doporučení času na základě světelných podmínek, citlivosti materiálu (ISO) a Schwarzschildova jevu.
* **Recepty (Předvolby):** Ukázky typických nastavení pro různé kreativní techniky (zmrazení pohybu, solargrafie, atd.).

## 🛠 Technologie
Projekt je napsán v čistém HTML, CSS a Vanilla JavaScriptu. Nevyužívá žádné externí frameworky ani knihovny, veškeré výpočty a renderování (Canvas API) probíhají přímo na straně klienta.
