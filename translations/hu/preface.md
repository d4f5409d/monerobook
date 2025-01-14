# Előszó

## A szerzőről

Én Nico (“SerHack”) vagyok, egy olasz biztonságtechnikai szakértő, egy közreműködő a Monero projektben és ennek a könyvnek a szerzője. Megfelelő, jó anyagokat találni és megismerni, valamint megtanulni a kriptovaluták használatát, működési elvét egy rémisztő feladat lehet. Az új felhasználók számára különösen nagy kihívást jelenthet az műszaki szempontból érthető, technikai szaknyelven megírt dokumentációt pontosan értelmezni. Amikor először szereztem tudomást a Monero-ról, elég sok időt kellett töltenem a témával kapcsolatos különböző források felkutatásával és elemzésével.

Azért írtam a Mastering Monero könyvet, hogy segítselek elkísérni téged ezen utadon, attól függetlenül, hogy éppen az első tárcádat készíted el, vagy csak érdekelnek az egyes megbúvó technikai részletek. Az első pár fejezet bárki számára érdekes lehet, aki kíváncsi arra, hogy miért és hogyan használjuk a Monero-t; egyszerűen megérthető magyarázatokat és példákat tartalmaz, a megfelelő használathoz való útmutatásokkal együtt. A későbbi fejezetek már bonyolultabb témákat is érintenek, mint például összeállítási (compiling) információk fejlesztőknek, akik szeretnének építkezni és közreműködni a Monero ökoszisztémájában.

A kalandom a kriptovaluták világával akkor kezdődött el, amikor tudomást szereztem a Bitcoin-ról 2016-ban, de mindig is aggasztott a teljesen nyílt és átlátható főkönyv hátulütő tulajdonsága.   
Mivel a Bitcoin és több más kriptovaluta is nyílt és nyomon követhető címek és érmék köré épül kristálytiszta háttértörténeti információkkal, a tranzakciók gyakran akaratukon kívül is kiteszik a felhasználókat személyes pénzügyi adatainak a kiszivárogtatásában. Minden címnek az egyenlege nyilvános információként bukkan fel, ami bárkit lehetővé tesz arra, hogy a jövedelmünket, költekezési szokásainkat tanulmányozza és megállapítsa a kriptovaluta vagyonunk nagyságát.
Ez olyan nem kívánatos következményekhez vezethez, mint például az árak manipulálása a tárcák egyenlege alapján.

I thought that Bitcoin was the only cryptocurrency until a friend introduced me to Monero in May 2017. I was blown away by its beautiful new paradigm: a world where vulnerable details such as account balances and transaction amounts are kept confidential to protect both the sender and the receiver. With privacy features implemented by default and always required, the entire Monero blockchain is veiled; users do not even have the option to accidentally send revealing transactions.

Recognizing the importance of this project, I began looking for ways to contribute to the community. I quickly saw an opportunity to support mass adoption by building payment gateways for online businesses, 
so I spearheaded the Monero Integrations project. This open-source codebase is designed around Monero's privacy-centric mentality: no signup or third-party service is required, since funds are routed directly to the recipient's wallet. The Monero community was very supportive throughout this endeavor, and the entire project was crowdfunded by donations through the Monero Forum Funding System (FFS).

While working on the Monero Integrations project, I learned that the lack of a comprehensive guide to Monero was an obstacle for end users and prospective contributors. This need for a thorough guide inspired me to write Mastering Monero as a universal resource for our global community. I am grateful for the generous FFS support that has made it possible to publish this document as a free eBook (and physical book!) for the general public. Whether you read Mastering Monero cover-to-cover or jump through sections pertinent to your questions, I hope you enjoy learning about Monero and the exciting projects within the community.

## How this resource is organized

The first two chapters of this book are friendly non-technical introductions to key topics and skills. For readers curious to learn more about behind-the-scenes details, chapters 3 and 4 contain conceptual non-mathematical explanations of Monero's privacy features and blockchain. Later chapters dive into complex technical details for understanding, developing, and integrating Monero.

The first chapter (Introduction to cryptocurrencies & Monero) is an general-audience non-technical introduction covering key ideas and concepts about blockchains and cryptocurrencies (appropriate both for newcomers and current users wishing to read more about Monero's principles). We'll cover the history and basics of cryptocurrencies, and describe how using blockchain technology resolves several problems present in the traditional mainstream financial systems, especially banking services. Unfortunately, there are privacy weaknesses endemic to most cryptocurrencies - we'll discuss the personal implications of these drawbacks, and learn how Monero mitigates these risks and protects your sensitive financial information.

The second chapter (Getting started: receiving, storing and sending Monero) is your handy guide for all the practical skills and tools that you'll need to use Monero yourself! We'll explain some necessary lingo, and learn about the 'pros and cons' of types of wallets. You'll learn how to make your first wallet, and you can even use the Mastering Monero example wallet for practice! 
In the third chapter (How Monero works), we'll discuss Monero's four main privacy technologies: RingCT, ring signatures, one-time (stealth) addresses, and Kovri. These are friendly explanations with no use of math or code, so you can learn conceptually how each feature works, and what benefits they provide.

The fourth chapter (The Monero Network) conceptually describes how Monero's network and miners processes transactions onto the blockchain. We'll discuss miners' incentivization (block rewards + fees), and the services that miners provide (confirming transaction and securing the decentralized and trustless network). We'll also introduce the “hot topic” of specialized mining equipment, and describe the Monero community's relevant egalitarian philosophy and active countermeasures that have been taken to resist ASICs.

While the preceding chapters have focused on learning how to use and conceptualize Monero in practical and intuitive ways, the remainder of the book will dive deeply into the internals of Monero, its mathematics, and its code. If you choose to tackle these advanced topics, you will truly be “mastering” Monero!

The fifth chapter (A Deep Dive into Monero & Cryptography) leads a technical deep dive into the privacy technologies covered conceptually in chapter 3. This study moves past the analogies, into the actual mathematics and specifications of Monero's enhanced version of the CryptoNote protocol.

The sixth chapter (Community and Contributing) contains information for anybody that is interested in contributing their time and skills to help the Monero community. Whatever your strengths, there are opportunities to contribute - you could help with translations, outreach, code development, applications, or in many other ways.

The seventh chapter (Monero integration for developers) discusses payment option, and useful methods for conveying addresses through OpenAlias (human-readable) and the Monero URI (machine-readable). Developers for merchant payment options, learn about generating simplified addresses through OpenAlias. Developers will learn how to interact with the Monero blockchain via remote procedure calls (RPC) to the Monero daemon, and a Python implementation is included to teach how basic tasks are executed.

The eighth chapter (Wallet guide and troubleshooting tips) contains miscellaneous information for setting up a graphical (GUI) or terminal-based (CLI) wallet along with troubleshooting tips for common problems.
