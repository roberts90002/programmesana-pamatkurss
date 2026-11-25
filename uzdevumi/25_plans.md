
# Spēle – punktu krājējs

## Ievade
1. Pajautāt spēlētāja vārdu.
2. Pajautāt savākto monētu skaitu.
3. Pajautāt pabeigto līmeņu skaitu.

## Apstrāde
4. Aprēķināt kopējo punktu skaitu, par katru monētu
   piešķirot 10 punktus un par katru līmeni 50 punktus.

## Izvade
5. Parādīt spēlētāja vārdu.
6. Parādīt kopējo iegūto punktu skaitu.

## Mainīgie

| Mainīgā vārds | Datu tips | Ko glabā |
|---|---|---|
| speletaja_vards | str | Spēlētāja vārdu |
| monetas | int | Savākto monētu skaitu |
| limeni | int | Pabeigto līmeņu skaitu |
| punkti | int | Kopējo punktu skaitu |

## Formula

punkti = monetas * 10 + limeni * 50

## Mainīgo iegūšana

No input(): speletaja_vards, monetas, limeni.
Tiek aprēķināts: punkti.

## Formulas pārbaude

1. Mazas vērtības:
   monetas = 2, limeni = 1
   punkti = 2 * 10 + 1 * 50 = 70

2. Vidējas vērtības:
   monetas = 10, limeni = 5
   punkti = 10 * 10 + 5 * 50 = 350

3. Lielas vērtības:
   monetas = 100, limeni = 20
   punkti = 100 * 10 + 20 * 50 = 2000

## Secinājums

Formulu ir vērts pārbaudīt pirms visas programmas
rakstīšanas, lai laikus atrastu kļūdas un pārliecinātos,
ka aprēķini ir pareizi.
