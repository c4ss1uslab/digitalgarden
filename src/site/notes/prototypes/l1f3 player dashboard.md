---
{"dg-publish":true,"permalink":"/prototypes/l1f3 player dashboard/","tags":["🌿","prototype","l1f3","lab","spatialnavigation","quantifiedself","selfmanagement","design","player"],"created":"2024-03-19T14:21:06.710-03:00","updated":"2024-07-20T18:24:43.738-03:00"}
---

inspired by the [[integral dashboard.jpeg|integral dashboard]], [[RPG\|RPG]]s, [[references/player/anime ; manga ; webtoon/sword art online\|sword art online]]/[[references/player/anime ; manga ; webtoon/solo leveling\|solo leveling]]'s simple [[images/gaming & anime references/solo leveling UIs\|UIs]], and [[topics/player/game interfaces\|game interfaces]] in general, i've been experimenting with creating a dashboard for [[concepts/self-management\|self-management]] for a long time.

the idea is to have a flexible dashboard, integrating different frameworks/data sources for self-management. it can range from low-fidelity/self-designed [[game elements\|game elements]] (like my [[000 ⛓ toolkit index\|toolkit]] design, [[models & frameworks/fourgames\|fourgames]]), to more philosophically/scientifically sound models of [[human development\|human development]] (such as [[concepts/integral theory\|integral]]'s [[models & frameworks/AQAL\|AQAL]], [[people/references/hanzi freinacht\|hanzi freinacht]]'s [[stage\|stage]], [[code\|code]], [[state\|state]] & [[depth\|depth]]), to very practical [[models & frameworks/biopsychosocial model\|biopsychosocial]] data ([[topics/lab/quantified self\|quantified self]]), to more therapeutic/esoteric stuff (like [[models & frameworks/internal family systems\|IFS]]/[[tbprocessed/base notes/people/bill plotkin\|bill plotkin]]'s/other psychological/shamanic inner management frameworks, [[human design\|human design]], [possibility management]]'s [[possibilitator toolkit\|possibilitator toolkit]]/[[concepts/first position\|first position]]), etc...

i was never able to prioritize building it completely (and learning what's necessary to make it actually good), so it's an unfinished [[_001_MOCs/050 🟩 mid game/070 🔩 prototypes MOC\|prototype]], but i did create some preliminary designs and it's still intended to be a core mechanism of the [[_004_L1F3/L1F3 game\|L1F3 game]].

here's an overview of what i was able to develop and its current status:

##### phase 1 - 2020

at first i started using a simple yet beautiful UI on [figma](https://www.figma.com/file/5UpGleobC3WJFckn9BNA6U/c4ss1us'-l1f3-dashboard?type=design&mode=design&t=8W2QvUSxNCEwymnl-1), but ended up stopping v1 midway, to focus more on just adding the information i found most relevant, without any wireframing (see phase 2).

![figma player dashboard draft 1.png](/img/user/images/made%20by%20me/figma%20player%20dashboard%20draft%201.png)

![figma player dashboard draft 2.png](/img/user/images/made%20by%20me/figma%20player%20dashboard%20draft%202.png)

![figma player dashboard draft 2 (zoom).png](/img/user/images/made%20by%20me/figma%20player%20dashboard%20draft%202%20(zoom).png)


##### phase 2 - 2022

![figma - player dashboard v2 (raw draft).png](/img/user/images/made%20by%20me/figma%20-%20player%20dashboard%20v2%20(raw%20draft).png)

![figma - player dashboard v2 (zoom, raw draft).png](/img/user/images/made%20by%20me/figma%20-%20player%20dashboard%20v2%20(zoom,%20raw%20draft).png)

##### phase 3 - 2023

after that, i could keep developing it/connect it to some data source/tracking mechanism, but i started feeling that it wasn't enough for it to be a dashboard dedicated only to self-management. i also wanted it to be a prototype for intentional spatial navigation across [[_001_MOCs/050 🟩 mid game/060 🗡 projects MOC\|projects]], [[_001_MOCs/025 🔷 long game/025 🗺 topics & references MOC\|topics]], [[initiatives, orgs & communities/communities MOC\|communities]], etc. (information in general)

an interface that'd pull information from different sources and help you navigate it - [[youtube\|youtube]], [[tbprocessed/base notes/tools;products - general/notion\|notion]], [[tbprocessed/base notes/ventures - general/obsidian\|obsidian]], [[telegram\|telegram]], [[social media\|social media]], etc - in a user-centric and not platform-centric way.

despite all its back-end / API / interoperability challenges, i started researching how to do it and decided to design/prototype it as a different project, which i called the [[prototypes/omnichannel curation feed\|📲 omnichannel curation feed]].

i started visually sketching it on figma as well, as you can see below.

![figma navigation dashboard 1 - topics & projects (raw draft).png](/img/user/images/made%20by%20me/figma%20navigation%20dashboard%201%20-%20topics%20&%20projects%20(raw%20draft).png)

![figma navigation dashboard 2 - relationships (raw draft).png](/img/user/images/made%20by%20me/figma%20navigation%20dashboard%202%20-%20relationships%20(raw%20draft).png)

![figma navigation dashboard 3 - media overview (raw draft).png](/img/user/images/made%20by%20me/figma%20navigation%20dashboard%203%20-%20media%20overview%20(raw%20draft).png)

today, it's more possible to make this "navigation dashboard" within obsidian itself (it has the canvas function and the excalidraw plugin), but they're still not intended for that (multiple cache/loading/GPU usage/UI/data management problems).

in a few years when [soft.space](https://soft.space) is more advanced, it may be better to continue building this there. [[fermat.ws\|fermat.ws]], [[kosmik\|kosmik]] and a few other [[spatial tools for thought\|spatial tools for thought]] also seem like viable alternatives. maybe creating something custom in a [[game engine\|game engine]], or building on top of something like [[projects & tools/tools/rvbbit\|rvbbit]] or [[udara jay\|udara jay]]'s [stats](https://github.com/UdaraJay/Stats).

##### references

other visual references: [c4ss1us.art pinterest "2d dashboards" board](https://br.pinterest.com/c4ss1usart/digital-art-professional/2d-dashboards/)
