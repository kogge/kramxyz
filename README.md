:zap:

# [ohmslag.xyz](https://komvuxarbete-ohms-lag.pages.dev/) - Ett komvuxarbete

För att köra hemsida lokalt klona arbetet och kör:
```sh
npm install
```
Sedan
```sh
npm run dev
```
## Varför?
Varför ville jag göra detta som komvuxarbete? Äntligen så kände jag att jag hade en ursäkt att testa något inom IT/programmering och kunna kombinera detta med studierna som jag har. Jag har alltid sneglat över på detta område då jag har spenderat väldigt mycket tid framför en dator men aldrig fått arbeta med de grundläggande byggstenarna.

Elteorin tyckte jag är perfekt för detta då jag tidigare har sett hemsidor med liknande funktionalitet och när Pär (vår lärare i bl.a fastighetsautomation och belysningsteknik) nämnde att detta hade gjorts tidigare av en elev som komvuxarbete så ville jag testa och se ifall jag kunde skapa något liknande.

Så jag tänkte att man då kunde skapa ett flöde med Javascript där man skickar värdena fram och tillbaka via funktioner, "if/else" och "greppar" tag i HTML-objekten för att få fram resultaten till användaren på ett smidigt sätt.

## Verktygen
| Verktyg     | -----                                    | 
|-------------|------------------------------------------|
| Text Editor | Jetbrains Webstorm                       |
| Ramverk     | Node/npm, Astro, Tailwnd CSS             |
| Deployment  | Cloudflare (Hosting) och Namecheap (DNS) |

Så varför valde jag dessa verktyg?

### Jetbrains Webstorm

Simpliciteten. Jag hade inte lust att lägga en massa tid på att sätta upp en texteditor att fungera med en massa välbehövlig funktionalitet. Här fick man allting färdigt i ett paket som snabbt skyndade på hur fort man kunde komma igång. Alternativ som jag kollade på var VScode och Vim/Neovim men ingen av dem kunde erbjuda samma funktionalitet i en tidspressad situation.

En stor fördel var även att programmet erbjöd en integrerad funktionalitet för Git/Github (versionshantering) men överlag simpla menyer som hjälpte en istället för att "krångla" runt med att även lära sig detta i terminalen.

En fördel var även att de hade en 30-dagars prova på så att man inte behövde betala för produkten. Nu när jag testat den har den varit över förväntan och är fylld med nyttiga funktioner "out of the box" för användaren. Kommer definivt titta vidare på detta verktyg ifall jag fortsätter att försöka lära mig vidare eller att försöka sätta upp något eget med Vim/Neovim.

### Ramverk

#### Node/NPM

Applikatpionen som man gör det möjligt att köra javascript-koden. Är branchstandard. NPM är verktyget Node och användaren använder för att ladda hem alla paketen som sen körs av Node.js och i mitt exempel blir detta t.ex. Astro och Tailwind.

#### [Astro](www.astro.build)

Ville göra en så pass simpel sida som möjligt men samtidigt kunna behålla modern funktionalitet så jag landade i att skapa en sida i Astro. Här kunde jag skapa komponenter av sidorna både för att återbruka och hålla isär kod så i slutsteget så bygger Astro ihop sidan åt en efter hur man valt att lägga upp funktionaliteten.

#### [Tailwind CSS](https://tailwindcss.com/)

Att sätta in sig i vanlig CSS kändes som ett eget program i sig så fallet blev att luta sig emot Tailwind CSS. Då kunde jag applicera klasser direkt på HTML-objekten för de funktioner jag ville ha. På så sätt kom jag igång snabbt och kunde få layouten att fungera acceptabelt (efter egen uppfattning). Att dessutom kunna använda sig att så kallade ["cheat sheets"](www.https://tailwindcomponents.com/cheatsheet/) förenklade processen något då jag kunde söka efter de funktionerna som jag ville ha och leta mig fram på det sättet, applicera och sedan se och testa ifall det fungerade som man hade tänkt sig.

### Deployment

#### Cloudflare
Att välja detta var lite av en djungel. Mina alternativ rörde sig inom de som Astro hade dokumentation för. Att valet hamnade på Cloudflare var både en rekommendatíon när jag kollade forum som Reddit och X/Twitter men har även själv tidigare varit ägare av aktier i bolaget så kände mig rätt så hemma med det valet. Två andra alternativ stod ut och var lämpliga kandidater, Netlify och Vercel som rekommenderades av både Astro och på nämnda forum.

#### Namecheap
Jag köpte namnet ohmslag.xyz hos Namecheap men märkte efter att jag satt upp kontot hos Cloudflare att namnet man vill köra med måste ligga hos Cloudflare själva så tyvärr fick jag inte detta att fungera för tillfället. Pengar i sjön kanske?

### Notis

Stackoverflow har även varit ett ypperligt verktyg även fast det är ett forum för programmerare. Här kan man ställa frågor men även söka efter likadana eller liknande problem som andra har gått igenom. Ofta

## Lärdomar

Internet är komplext och det verkar som att den har ökat med tiden. Allting byggs mer eller mindre med ramverk som istället för att förenkla för utvecklaren har höjt ribban att ta sig in på området och höjt kompetensen som krävs för att nå en modern verkshöjd om man jämför med senast jag sneglade över på området i början på 2000-talet. Jag kommer ihåg att man la sin layout genom att skapa HTML-tabeller för att då fanns varken CSS Flex eller CSS Grid som nu är ett standardiserat arbetssätt inom webblayout. Lärdomen blev att det tar bra mycket längre tid att ta sig från start till mål när kunskaperna är knappa även fast man inte känner sig helt "bakom flötet" när det kommer teknik i allmänhet.

Men samtidigt så känns standarderna mer genomarbetade och webben har kommit längre i sin mognad och möjligheterna känns oändliga i jämförelse, allt man behöver är lite tid, vilja och nyfikenhet för att få något att fungera i praktiken.

##### AV:
Karl-Oskar Andersson

:zap: