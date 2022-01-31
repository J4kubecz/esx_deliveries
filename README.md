<div align="center">

# ESX_Deliveries
##### Práce poštáka do fivem. Pronajmete si vozidlo a rozvážíte zásilky náhodně po městě.




</div>


Možnosti:
- 3 různé druhy doručování - **Motorka / Dodávka / Kamion**
- Různé **objekty** a animace pro různé typy rozvozu.
- **Náhodné** množství zásilek.
- **Lehké na ovládání** - systém s **popisky** a **oznaceni** pri celem procesu.
- **Možnost** upravit počet zásilek.
- **Možnost** upravit výplaty za každý druh doručení.


### Požadavky
* ESX (kvůli platbám)

## instalace a Spusteni

### Instalace
- Stahnete soubor z https://github.com/J4kubecz/esx_deliveries
- Vložte do `[esx]` složky v databázi vašeho serveru.


## Spusteni
- Přidejte na nový řádek v server.cfg :

```
start esx_deliveries
```
## Úpravy
- Tyto následující úpravy jsou možné. pokud hodnoty nezměníte budou použity základní.
```
# Decorcode -Nic nepřepisujte pokud to nechcete měnit/nevíte k čemu to je. - základní 1450
  setr esx_deliveries_decorcode [int number]

# Minimální počet zásilek - základní 5
  setr esx_deliveries_min [int number]

# Maximalní počet zásilek - základní 7
  setr esx_deliveries_max [int number]

# Odmena za doruceni na MOTORCE - základní 750
  setr esx_deliveries_reward_scooter [int number]

# Odmena za doruceni DODAVKOU - základní 1000
  setr esx_deliveries_reward_van [int number]

# odmena za doruceni KAMIONEM - základní 1450
  setr esx_deliveries_reward_truck [int number]

# Zaloha za MOTORKU -  základní 4000
  setr esx_deliveries_safe_deposit_scooter [int number]

# Zaloha za DODAVKU - základní 6000
  setr esx_deliveries_safe_deposit_van [int number]

# Zaloha za KAMION - základní 8000
  setr esx_deliveries_safe_deposit_truck [int number]
```
