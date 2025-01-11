\# AI-NFT metaandmed

AI-NFT loomine sarnaneb olemasoleva NFT loomise protsessiga, kuid
lisatakse väli \*\*\`ai_agent\`\*\*. See väli viitab AI-agendi sätetele
ja kasutusmootorile ning see teave salvestatakse metaandmetesse.

\## Toetatud AI mootorid \<a href=\"#metadata-json\"
id=\"metadata-json\"\>\</a\>

\<table\>\<thead\>\<tr\>\<th width=\"224\"\>Mootor\</th\>\<th
width=\"231\"\>Mootori nimi\</th\>\<th\>Tähemärgifail\</th\>\</tr\>\<
/thead\>\<tbody\>\<tr\>\<td\>\<a
href=\"https://github.com/elizaOS/eliza\"\>Eliza\</a\>
(ElizaOS)\</td\>\<td\>eliza\</td\>\<td\>\<ul\>\<li\>Kasutage \<a
href=\"https://elizaos.github.io/eliza/docs/core/characterfile/\"\>
Dokumentatsioon\</a\>\</li\>\<li\>\<a
href=\"https://github.com/elizaOS/characterfile\"\>Mall\</a\>\</li\>\<li\>\<a
href=\"https://github.com/elizaOS/eliza/tree/main/characters\"\>Näide\</a\>\</li\>\</ul\>\</td\>\</tr\>\</tbody\>\</table
\>

\## AI-NFT metaandmete JSON \<a href=\"#metadata-json\"
id=\"metadata-json\"\>\</a\>

\| väli \| Tüüp \| Kirjeldus \| \|
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-- \| \-\-\-\-\--
\|
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--
\| \| \*\*ai\\\_agent\*\* (äsja lisatud) \| objekt \| \<p\>Selle NFT-ga
ühendatud AI-agendi sätted\</p\>\<ul\>\<li\>\<strong\>mootor\</strong\>
(string): AI-agendi käitamiseks kasutatav mootor. Vaikimisi on
\"eliza\"\</li\>\<li\>\<strong\>märk\</strong\> (objekt): JSON-vormingus
märgifail, mis kirjeldab tehisintellekti agenti. Lisateabe saamiseks
vaadake \<a
href=\"https://github.com/elizaOS/characterfile?tab=readme-ov-file\"\>siit\</a\>.\</li\>\</ul\>
\| \| \*\*nimi\*\* \| string \| Vara nimi \| \| \*\*kirjeldus\*\* \|
string \| Vara kirjeldus \| \| \*\*pilt\*\* \| string \| URI, mis
tähistab vara logo \| \| \*\*animatsioon\\\_url\*\* \| string \| URI,
mis esindab vara animatsiooni \| \| \*\*väline\\\_url\*\* \| string \|
URI, mis viitab vara kirjeldavale välisele URL-ile -- näiteks mängu
ametlikule veebisaidile \| \| \*\*atribuudid\*\* \| massiiv \|
\<p\>Atribuutide massiiv, mis määratleb vara
omadused.\</p\>\<ul\>\<li\>\<strong\>tunnuse_tüüp\</strong\> (string):
tunnuse tüüp\</li\>\<li\>\<strong\>väärtus \</strong\> (string):
atribuudi väärtus\</li\>\</ul\> \| \| \*\*omadused\*\* \| objekt \|
\<p\>Täiendavad atribuudid, mis määravad vara
omadused\</p\>\<ul\>\<li\>\<p\>\<strong\>failid\</strong\> (massiiv):
varaga kaasas olevad täiendavad failid\</p\>\<ul\>
\<li\>\<strong\>uri\</strong\> (string): faili
URI\</li\>\<li\>\<strong\>tüüp\</strong\> (string): faili tüüp, nt
\<code\>image/png\</li\>. kood\>,
\<code\>video/mp4\</code\>\</li\>\<li\>\<strong\>cdn\</strong\> (tõve
väärtus, valikuline): kas faili edastatakse CDN-ist\</li\>\</ul\>\</li
\> \<li\>\<strong\>kategooria\</strong\> (string): vara
meediakategooria, nt \<code\>video\</code\>,
\<code\>pilt\</code\>\</li\>\</ul\> \|

\## näide

\`\`\` json { // AI agendi väli ai_agent: { mootor: \"eliza\", märk: {
// agendi nimi nimi: \"eliza\", // taustaväited bio: \[ \"Bio read on
kõik lühikesed katkendid, mida saab juhuslikus järjekorras kokku
panna.\" \"Leidsime, et iga konteksti jaoks juhusliku ja ainult osa
biograafia valimine suurendab entroopiat.\" \"See \"entroopia\" aitab
laiendada võimalike väljundite jaotust, mis peaks andma mitmekesisemaid,
kuid pidevalt asjakohaseid vastuseid.\" \], pärimus: \[ \"Lore read on
kõik lühikesed jupid, mida saab juhuslikus järjekorras koostada, täpselt
nagu bio\", \"Kuid need on tavaliselt rohkem faktilised või ajaloolised
ja vähem biograafilised kui biograafilised read,\" \"Vestluspäevikutest
ja säutsudest saab välja võtta pärimusliine kui asju, mis tegelaskuju
või nendega juhtus\", \"Kontekstis entroopia suurendamiseks tuleks ka
pärimust randomiseerida ja valida sellest valim.\" \], \...
//xxx.character.json saidilt
https://github.com/elizaOS/eliza/tree/main/characters } }, // tüüpiline
NFT metaandmete standard nimi: \"Minu NFT\", kirjeldus: \"See on Solana
NFT\", pilt: imageUri\[0\], external_url: \'https://example.com\',
atribuudid: \[ { trait_type: \'tunnus1\', väärtus: \'väärtus1\', }, {
trait_type: \'tunnus2\', väärtus: \'väärtus2\', }, \], omadused: {
failid: \[ { uri: imageUri\[0\], tüüp: \'image/jpeg\', }, \],
kategooria: \'pilt\', }, } \`\`\`
