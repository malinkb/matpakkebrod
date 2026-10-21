# Matpakkebrød

**Open-source Norwegian lunchbox bread.**

Matpakkebrød er et eksperimentelt, åpent brødprosjekt med ett hovedmål: å lage et godt brød som faktisk fungerer i matpakken.

Brødet utvikles iterativt gjennom baking, smakstesting og praktiske matpakketester. Oppskriftene publiseres åpent slik at andre kan bake dem, forbedre dem og lage egne varianter.

## Designmål

Referanseoppskriftene skal så langt som mulig være:

- saftige og gode også etter at brødet er skåret i skiver
- egnet til å ligge flere timer i en tradisjonell matpakke
- mettende, med fornuftig innhold av protein og fiber
- faste nok til jevne skiver og vanlig pålegg
- basert på rimelige ingredienser som er enkle å finne i vanlig dagligvare
- enkle å bake hjemme med vanlig kjøkkenutstyr
- dokumenterte slik at resultatene kan reproduseres og forbedres

Prosjektet optimaliserer ikke primært for økologiske ingredienser eller spesialprodukter. Slike varianter kan naturligvis lages som egne forks.

## Status

Første utviklingsgren er **Original med tørrgjær**.

- `v0.1` er bakt og testet.
- Et kjent problem er at restene ble merkbart tørre etter noen døgn i kjøleskap.
- Neste test undersøker først om lagringsmetoden var hovedårsaken før selve oppskriften endres vesentlig.

Planlagte grener inkluderer blant annet:

- Original / tørrgjær
- Original / surdeig
- grovere varianter
- varianter med høyere proteininnhold

Se `recipes/` og `CHANGELOG.md` for versjoner og utviklingshistorikk.

## Guinness i tidlige versjoner

De første versjonene bruker Guinness som en praktisk referanse for mørkt maltpreg, bitterhet og væske.

Dette er **ikke ment som en permanent avhengighet til ett bestemt varemerke**. Et langsiktig mål er å erstatte Guinness-avhengigheten med en rimelig og lett tilgjengelig, generisk løsning som gir tilsvarende ønskede egenskaper i brødet. Det kan for eksempel bli en spesifisert stout-type eller en egen åpen maltbase utviklet for baking.

Guinness er et varemerke tilhørende sin respektive rettighetshaver. Matpakkebrød-prosjektet er ikke tilknyttet eller godkjent av Guinness.

## Utviklingsmodell

Prosjektet behandles litt som programvare:

1. Bak en versjon.
2. Test den i faktisk bruk.
3. Registrer problemer som issues.
4. Endre så få variabler som mulig.
5. Test på nytt.
6. Dokumenter resultatet og versjoner endringen.

En ny oppskrift regnes ikke som en forbedring bare fordi den ser bedre ut på papiret. Den skal bakes og testes først.

## AI-assistert utvikling

Prosjektet ble startet og testes fysisk av **Malin Bruland (Malinux)**, med AI-assistanse fra **OpenAI ChatGPT**. Den første utviklingen er gjort med modellen **GPT-5.6 Sol**.

AI brukes blant annet til beregninger, forslag til oppskriftsendringer, testdesign og dokumentasjon. Praktiske resultater, smak, konsistens og holdbarhet avgjøres gjennom faktisk baking og testing.

Se `CONTRIBUTORS.md` for mer informasjon.

## Lisens

Oppskrifter og dokumentasjon i dette prosjektet er lisensiert under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**, med mindre noe annet er uttrykkelig angitt.

Du kan dele og bearbeide materialet, også kommersielt, så lenge vilkårene om kreditering og deling på samme vilkår følges.

Se `LICENSE.md`.
