---
title: Decentralizirane avtonomne organizacije (DAOs)
description: Pregled DAOs na Ethereumu
lang: sl
template: primeri uporabe v praksi
emoji: ":handshake:"
sidebar: true
sidebarDepth: 2
image: ../../assets/use-cases/dao-2.png
alt: "Predstavitev DAO, ki glasuje o predlogu."
summaryPoints: '[ "Skupnosti v lasti članov brez centraliziranega vodstva", "Varen način za slodelovanje s stujci prek spleta.", "Varno mesto za namen sredstev v specifičen namen", ] ---'
---

## What is DAOs? {#what-are-daos}

DAOs so učinkovit in varen način za delo z enakomislečimi osebami po celem svetu.

Predstavljajte si, da so to "podjetja", ki domujejo na internetu in so v skupniski lasti ter upravljana s strani njihovih članov. Imajo vgrajene blagajne, do katerih brez odobritve skupine ne more dostopati nihče. Odločitve se sprejema na podlagi predlogov in glasovanja, da se vsem članom organizacije zagotovi besedo pri odločanju.

Direkor, ki bi lahko odobril porabo sredtev na podlagi lastnih prebliskov, ne obstaja, prav tako ni sumljivih direktorjev financ, ki bi lahko manipulirali z računovodstvom. Vse je odprte narave in pravila za porabo so zapisana v DAO prek programske kode.

## Zakaj potrebujemo DAOs? {#why-dao}

Z nekom ustanoviti organizacijo, ki vključuje financiranje in denar, zahteva veliko zaupanja v ljudi s katerimi sodelujete. Ampak težko je zaupati nekomu s katerim ste komunicirali le preko spleta. Z DAOs vam ni potrebno zaupati nikomur drugemu iz skupine, le programski kodi, ki je 100% transparentna in jo lahko kdorkoli potrdi.

To predstavlja veliko novih priložnosti za globalno sodelovanje in koordinacijo.

### Primerjava {#dao-comparison}

| DAO                                                                                                            | Tradicionalna organizacija                                                                                 |
| -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| Ponavadi ploska in popolnoma demokratizirana.                                                                  | Ponavadi hierarhična.                                                                                      |
| Glasovanje s strani članov je potrebno za implementacijo kakršnekoli spremembe.                                | Odvisno od struture, so spremembe lahko zahtevane s strani ene osebe ali pa je lahko omogočeno glasovanje. |
| Glasovi so prešteti in rezultat je implementiran samodejno brez zaupanja vrednega posrednika.                  | Če je omogočeno glasovanje, so glasovi prešteti interno in rezultat mora biti izveden ročno.               |
| Ponujene storitve so izvedene samodejno v decentralizirani naravi (na primer razdelitev dobrodelnih sredstev). | Potrebna je šloveška izvedba ali centralno nadzorovana avtomatizacija, ki je nagnjena k manipulaciji.      |
| Vse aktivnosti so transparentne in povsem javne.                                                               | Aktivnosti so ponavadi zasebne in javni vpogled je omejen.                                                 |

### Primeri DAO {#dao-examples}

Da bi bilo vse skupaj bolj smiselno, je tukaj nekaj primerov kako bi lahko uporabili DAO:

- Dobrodelnost – lahko sprejemate članstvo in donacije od kogarkoli na svetu in skupina se lahko odloči kako bodo donacije porabili.
- Mreža freelancerjev – lahko bi ustvarili mrežo izvajalcev, ki združujejo svoja sredstva za najem poslovnih prostorov in najem programske opreme.
- Naložbe in finančna podpora – lahko bi ustvarili naložbeni sklad, ki združuje investicijska sredstva in glasuje o priložnostih, ki bodo podprte. Povrnjen denar je lahko kasneje razdeljen med DAO člane.

## Članstvo v DAO {#dao-membership}

Obstajajo različni modeli za članstvo v DAO. Članstvo lahko določa kako deluje glasovanje in ostali ključni deli DAO.

### Članstvo na podlagi lastništva žetonov {#token-based-membership}

Ponavadi povsem brez potrebnega soglasja, odvisno od uporabljenih žetonov. Mostly these governance tokens can be traded permissionlessly on a decentralized exchange. Others must be earned through providing liquidity or some other ‘proof-of-work’. V obeh pirmerih vam lastništvo zagotavlja možnost glasovanja.

_Ponavadi se ta oblika uporablja za upravljanje obširnih decentraliziranih protokolov in/ali samih žetonov._

#### Znameniti primer {#token-example}

[MakerDAO](https://makerdao.com) – Žeton organizacije MakerDAO MKR je široko dostopen na decentraliziranih borzah. Tako si lahko kdorkoli kupi pravico do glasovanja o prihodnosti Maker protokola.

### Članstvo na podlagi deleža {#share-based-membership}

DAOs, ki delujejo na podlagi deleža zahtevajo dovoljenje, vendar so še vedno precej odprti. Katerikoli potencialni član lahko vloži predlog za pridružitev DAO, ponavadi s ponujenim prispevkom določene vrednosti v obliki žetonov ali dela. Deleži predstavljajo neposredno glasovalno pravico in lastništvo. Člani lahko kadarkoli izstopijo in prejmejo proporcionalen del sredstev v blagajni.

_Ponavadi se ta oblika uporablja za tesneje prepletene organizacije osredotočene na ljudi, kot so dobrodelne organizacije, delavski kolektivi in naložbeni klubi. Prav tako pa lahko upravljajo protokole in žetone._

#### Znameniti primer {#share-example}

[MolochDAO](http://molochdao.com/) – MolochDAO se osredotoča na financiranje Ethereum projektov. Za pridobitev članstva zahtevajo vlogo, da skupina lahko oceni, če imate potrebno strokovno znanje in kapital za sprejemanje premišljenih mnenj o potencialnih prejemnikih financiranja. Lahko pa preprosto kupite dostop do DAO na prostem trgu.

## Kako delujejo DAOs? {#how-daos-work}

Podlaga za DAO je pametna pogodba. Ta pogodba določa pravila organizacije in hrani sredstva skupine. Ko je pogodba aktivna na Ethereumu, nihče ne more spremeniti pravil, razen z glasovanjem. Če kdorkoli poskusi narediti nekaj kar ni določeno v pravilih in logiki programske kode, ta poskus ne bo uspel. In ker je blagajna prav tako opredeljena s strani pametne pogodbe to pomeni, da nihče ne more porabiti sredstev brez soglasja skupine. To pomeni, da DAOs ne potrebujejo osrednje oblasti. Namesto tega skupina sprejema odločitve kot celota in po uspešnem glasovanju so plačila odobrena samodejno.

To je mogoče, saj so pametne pogodbe odporne proti posegom, ko so enkrat aktivne na Ethereumu. Ne morete kar urejati kode (DAO pravil) brez, da bi kdo opazil, saj je vse javno dostopno.

<DocLink to="/developers/docs/smart-contracts/" title="Več o pametnih pogodbah" />

## Ethereum in DAOs {#ethereum-and-daos}

Ethereum iz večih razlogov predstavlja popolno podlago za DAOs:

- Ethereumovo lastno soglasje je dovolj distribuirano in vzpostavljeno, da organizacije lahko zaupajo omrežju.
- Ko je pametna pogodba enkrat aktivna njena programska koda ne more biti spremenjena niti s strani lastnikov. To omogoča, da DAO deluje po pravilih, ki so napisana v programski kodi.
- Pametne pogodbe lahko pošiljajo/sprejemajo sredstva. Brez tega bi potrebovali zaupanja vrednega posrednika, ki bi upravljal s sredstvi skupine.
- Ethereum skupnost je dokazala, da je bolj usmerjenja paroti sodelovanju kot tekmovanju, kar omogoča najboljše prakse in podporo ekosistemu, da se hitro razvija.

## Pridružite se / ustanovite DAO {#join-start-a-dao}

### Pridruižete se DAO {#join-a-dao}

- [DAOs Ethereum skupnosti](/community/#decentralized-autonomous-organizations-daos/community/#decentralized-autonomous-organizations-daos)
- [DAOHaus seznam DAOs](https://app.daohaus.club/explore)

### Ustanovite DAO {#start-a-dao}

- [Prikličite DAO z DAOHaus](https://app.daohaus.club/summon)
- [Ustvarite DAO, ki ga poganja Aragon](https://aragon.org/product)
- [Ustanovite kolonijo](https://colony.io/)
- [Razvite DAO z DAOstack](https://daostack.io/)

## Nadaljno branje {#further-reading}

### DAO članki {#dao-articles}

- [Kaj je DAO?](https://aragon.org/dao) – [Aragon](https://aragon.org/)
- [Hiša DAOs](https://wiki.metagame.wtf/docs/great-houses/house-of-daos) – [Metagame](https://wiki.metagame.wtf/)
- [Kaj je DAO in čemu je namenjen?](https://daohaus.substack.com/p/-what-is-a-dao-and-what-is-it-for) – [DAOHaus](https://daohaus.club/)
- [Kako ustanoviti DAO-Powered Digital Community](https://daohaus.substack.com/p/four-and-a-half-steps-to-start-a) – [DAOhaus](https://daohaus.club/)
- [Kaj je DAO?](https://coinmarketcap.com/alexandria/article/what-is-a-dao) – [Coinmarketcap](https://coinmarketcap.com)

### Videoposnetki {#videos}

- [Kaj je DAO v kriptu?](https://youtu.be/KHm0uUPqmVE)
