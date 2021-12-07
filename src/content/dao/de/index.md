---
title: Dezentralisierte Autonome Organisationen (DAO)
description: Eine Übersicht der DAOs auf Ethereum
lang: de
template: use-cases
emoji: ":handshake:"
sidebar: true
sidebarDepth: 2
image: ../../assets/use-cases/dao-2.png
alt: "Eine Repräsentation eines Abstimmungsvorschlags in einem DAO."
summaryPoints: '[ "Im Mitgliederbesitz befindliche Gemeinschaften ohne zentrale Führung.", "Eine sichere Art, mit Fremden im Internet zusammenzuarbeiten.", "Ein sicherer Ort, um Geld für bestimmte Zwecke freizugeben.",] ---'
---

## Was sind DAOs? {#what-are-daos}

DAOs sind eine effektive und sichere Möglichkeit, mit Gleichgesinnten auf der ganzen Welt zu arbeiten.

Stellen Sie sich DAOs wie internetbasierte Unternehmen vor, die sich im Besitz aller Mitglieder befinden und die kollektiv geführt werden. Sie verfügen über eingebaute Finanzabteilungen, auf die niemand ohne die Zustmmung der Gruppe Zugriff hat. Entscheidungen werden durch Vorschläge und Abstimmungen geregelt, um sicherzustellen, dass jedes Mitglied der Organisation eine Stimme bekommt.

Es gibt keine Geschäftsführer, die Geld nach eigenen Ermessen ausgeben können, und keinen Finanzvorstand, der die Bilanzen manipulieren könnte. Alles wird transparent offengelegt und das Regularium, um über geplante Ausgaben zu entscheiden, ist durch den Code in die DAO integriert.

## Warum brauchen wir DAOs? {#why-dao}

Ein Unternehmen mit jemandem zu gründen und dafür Gelder und Finanzierungsmöglichkeiten bereitzustellen, benötigt viel Vertrauen in die Menschen, mit denen Sie arbeiten. Allerdings ist es schwierig, jemandem zu vertrauen, den Sie nur durch das Internet kennen. Durch DAOs müssen Sie anderen in der Gruppe nicht vertrauen, sondern nur dem DAO-Code, der 100 % transparent und für jeden einsehbar ist.

Dies eröffnet viele neue Möglichkeiten für globale Zusammenarbeit und Koordination.

### Ein Vergleich {#dao-comparison}

| DAO                                                                                                                   | Ein traditionelles Unternehmen                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Normalerweise flach und vollständig demokratisiert.                                                                   | Normalerweise hierarchisch.                                                                                                      |
| Abstimmung durch die Gruppe notwendig, um Veränderungen zu implementieren.                                            | Je nach Struktur können Veränderungen entweder durch einzelne Parteien verlangt oder durch offene Abstimmungen angeboten werden. |
| Stimmen werden gezählt und das Ergebnis wird automatisch ohne vertrauenswürdige Dritte implementiert.                 | Sofern Abstimmungen erlaubt sind, werden Stimmen intern gezählt und das Ergebnis muss manuell umgesetzt werden.                  |
| Angebotene Dienste werden automatisch auf dezentrale Weise abgewickelt (etwa die Verteilung philantropischer Mittel). | Benötigt menschlichen Eingriff oder zentral kontrollierte Automatismen, anfällig gegenüber Manipulation.                         |
| Alle Aktivitäten sind transparent und vollständig öffentlich.                                                         | Alle Aktivitäten bleiben normalerweise unternehmensintern, begrenzte Einsicht durch Öffentlichkeit.                              |

### Beispiele für DAOs {#dao-examples}

Für ein besseres Verständnis bieten sich diese Beispiele für die Nutzung einer DAO an:

- Eine Wohltätigkeitsorganisation: Sie können Mitgliedschaften und Spenden von allen Menschen auf der Welt annehmen und die Gruppe entscheidet, wie die Gelder ausgegeben werden sollen.
- Ein Freelancer-Netzwerk: Sie könnten ein Netzwerk aus Auftragnehmern schaffen, die ihr Geld für Büroräume und Softwarelizenzen zusammenlegen.
- Unternehmen und Zuschüsse - Sie könnten einen Risikofonds gründen, der Investitionskapital bündelt und über zu unterstützende Unternehmen abstimmt. Das zurückgezahlte Geld könnte später unter den DAO-Mitgliedern neu verteilt werden.

## DAO Mitgliedschaft {#dao-membership}

Es gibt verschiedene Modelle für eine DAO-Mitgliedschaft. Die Mitglieder können bestimmen, wie Abstimmungen und andere wichtige Teile der DAO funktionieren.

### Token-basierte Mitgliedschaft {#token-based-membership}

In der Regel völlig zustimmungsfrei, je nach verwendetem Token. Mostly these governance tokens can be traded permissionlessly on a decentralized exchange. Others must be earned through providing liquidity or some other ‘proof-of-work’. In jedem Fall gewährt der Besitz des Tokens Zugang zur Abstimmung.

_In der Regel werden sie zur Steuerung umfangreicher dezentraler Protokolle und/oder Token selbst verwendet._

#### Ein berühmtes Beispiel {#token-example}

[MakerDAO](https://makerdao.com) – Der Token MKR von MakerDAO ist auf dezentralen Börsen weit verbreitet. Jeder kann sich also ein Stimmrecht über die Zukunft des Maker-Protokolls erkaufen.

### Anteilbasierte Mitgliedschaft {#share-based-membership}

Anteilsbasierte DAOs sind stärker reglementiert, aber immer noch recht offen. Jedes potenzielle Mitglied kann einen Antrag auf Beitritt zur DAO stellen und bietet in der Regel eine Gegenleistung in Form von Token oder Arbeit an. Anteile stehen für direkte Stimmrechte und Eigentum. Die Mitglieder können jederzeit mit ihrem Anteil an der Kapitalbeteiligung aussteigen.

_Wird in der Regel für kleinere, auf den Menschen ausgerichtete Organisationen wie Wohltätigkeitsorganisationen, Arbeitnehmerkollektive und Investmentclubs verwendet. Sie können auch Protokolle und Token regeln._

#### Ein berühmtes Beispiel {#share-example}

[MolochDAO](http://molochdao.com/) – MolochDAO ist auf die Finanzierung von Ethereum-Projekten ausgerichtet. Sie verlangen einen Antrag auf Mitgliedschaft, damit die Gruppe beurteilen kann, ob über das nötige Fachwissen und Kapital verfügt, um fundierte Urteile über potenzielle Zuschussempfänger zu treffen. Man kann den Zugang zur DAO nicht einfach auf dem freien Markt kaufen.

## Wie funktionieren DAOs? {#how-daos-work}

Das Rückgrat einer DAO ist ihr Smart Contract. Der Smart Conttract legt die Regeln der Organisation fest und verwaltet die Finanzmittel der Gruppe. Sobald der Smart Cointract auf Ethereum aktiv ist, kann niemand mehr die Regeln ändern, außer durch eine Abstimmung. Wenn jemand versucht, etwas zu tun, was nicht durch die Regeln und die Logik des Codes abgedeckt ist, wird es fehlschlagen. Und da die Schatzkammer ebenfalls durch den Smart Contract definiert ist, kann auch niemand das Geld ohne die Zustimmung der Gruppe ausgeben. Das bedeutet, dass DAOs keine zentrale Autorität benötigen. Stattdessen trifft die Gruppe gemeinsam Entscheidungen, und die Zahlungen werden automatisch genehmigt, wenn die Abstimmung positiv ausfällt.

Dies ist möglich, weil Smart Contracts manipulationssicher sind, sobald sie auf Ethereum in Betrieb gehen. Man kann nicht einfach den Code (die Regeln der DAOs) ändern, ohne dass es jemand merkt, weil alles öffentlich ist.

<DocLink to="/developers/docs/smart-contracts/" title="Mehr zu Smart Contracts" />

## Ethereum und DAOs {#ethereum-and-daos}

Ethereum ist aus einer Reihe von Gründen die perfekte Grundlage für DAOs:

- Der Ethereum-eigene Konsens ist so weit verbreitet und etabliert, dass Unternehmen dem Netzwerk vertrauen können.
- Der Code eines Smart Contracts kann nicht mehr geändert werden, auch nicht von seinen Besitzern. Dies ermöglicht es der DAO, nach den Regeln zu arbeiten, mit denen sie programmiert wurde.
- Intelligente Verträge können Gelder senden/empfangen. Andernfalls bräuchten Sie einen vertrauenswürdigen Vermittler für die Verwaltung der Geldmittel der Gruppe.
- Die Ethereum-Community hat sich als eher kollaborativ als konkurrierend erwiesen, so dass sich schnell bewährte Verfahren und Unterstützungssysteme herausbilden konnten.

## Einer DAO beitreten / gründen {#join-start-a-dao}

### Einer DAO beitreten {#join-a-dao}

- [Ethereum Community DAOs](/community/#decentralized-autonomous-organizations-daos/community/#decentralized-autonomous-organizations-daos)
- [DAOHaus Liste der DAOs](https://app.daohaus.club/explore)

### Eine DAO gründen {#start-a-dao}

- [Gründe eine DAO mit DAOHaus](https://app.daohaus.club/summon)
- [Gründe eine von Aragon betriebene DAO](https://aragon.org/product)
- [Beginne deine Kolonie](https://colony.io/)
- [Gründe eine DAO mit DAOstack](https://daostack.io/)

## Weiterführende Informationen {#further-reading}

### DAO Artikel {#dao-articles}

- [Was ist eine DAO?](https://aragon.org/dao) – [Aragon](https://aragon.org/)
- [Haus der DAOs](https://wiki.metagame.wtf/docs/great-houses/house-of-daos) - [Metagame](https://wiki.metagame.wtf/)
- [Was ist eine DAO und wofür ist sie da?](https://daohaus.substack.com/p/-what-is-a-dao-and-what-is-it-for) – [DAOhaus](https://daohaus.club/)
- [Wie man eine DAO-gestützte digitale Gemeinschaft gründet](https://daohaus.substack.com/p/four-and-a-half-steps-to-start-a) – [DAOhaus](https://daohaus.club/)
- [Was ist eine DAO?](https://coinmarketcap.com/alexandria/article/what-is-a-dao) – [Coinmarketcap](https://coinmarketcap.com)

### Videos {#videos}

- [Was ist eine DAO in der Kryptowirtschaft?](https://youtu.be/KHm0uUPqmVE)
