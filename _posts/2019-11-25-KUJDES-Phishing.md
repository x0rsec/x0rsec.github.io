---
layout: post
title: "KUJDES - Phishing"
categories: [lajme, analiza]
---

## Përmbledhje

Sektori bankar gjithmone ka qenë target nga sulmet e ndryshme kibernetike në veqanti nga **"Social Engineering - Phishing"** ku ka per qellim vjedhjen e te
dhënave të ndjeshme qofshin të individeve apo dhe te bizneseve.


## Cka është Phishing

**Phishingu** është proces i perpjekjes për të marr informacione të ndjeshme si emrat e përdoruresve apo fjalëkalimet dhe detajet e kartës së kreditit.
Emailet qe pretendojn se janë nga faqet zyrtare të ndonje entitetim bankare , sociale apo ndonje kompanie zakonisht përdoren si karrem për joshur publikun
për te mos dyshuar ne origjinen apo ne përmbatjen e emailes që te duket sa ma reale, aktiviteti **Social Engineering** është formë e mashtrimit.


## Raiffeisen Phishing

Në bazë të analizave tona ne javen e fundit kemi vërejtur një rritje të konsiderushme të WEB-Faqeve të cilat jan duke e clonuar ( kopjuar) nga
faqja zyrtare e Bankes Raiffeisen dhe është duke u tentuar qe permes metodes te cilen e kemi cekur me siper **Phishing** të ju mashtroj qe te marr qasje te
pa autorizuar ne informacionet e ndjeshme tua personale dhe bankare.

## Analiza teknike

Para se te hyjm ne analizen teknike duhet ta keni te qart se: Domain zyrtar i bankes Raiffeisen eshte **https://www.raiffeisen-kosovo.com/**

## Kujdes nga Emri

Siq mund te shiheni edhe ne fotot me posht qe domain te cilen do te mundohemi te ju tregojm se nuk i perket Bankes Raiffeisen por eshte nje domain i regjistruar me daten 24.11.2019  eshte nje domain po thuajse gati identik me emrin zyrtar te Bankes Reiffeisen.

![image6]({{ site.baseurl }}/images/registrat.png){:.images}

Domain per momentin eshte aktiv dhe gjithashtu posedon SSL Certifikate te leshuar nga Let's Encrypt. Mund te shihetne foto me posht.


![image6]({{ site.baseurl }}/images/ssl.png){:.images}

## Permbajtja e Web Faqes

Sic e kam cek edhe me lart se faqja eshte e klonuar nga faqja zyrtare e Raiffeisen Bank e 1 apo 2 viteve te meparshme sepse versioni i fundit i faqes zyrtare te Bankes eshte po thuajse tjeter ne krahasim me faqen mashtruese. Shih foton me poshte te faqes mashtruese.

![image6]({{ site.baseurl }}/images/home.png){:.images}



## Keshillat per mbrojtje nga Phishingut.


**-> Duhet te keni kujdes ne cdo email ce ju vije ne emer te BANKES apo ndonje Entiteti tjeter , nese keni dyshime ju lutem kontaktoni banken.**

**-> Mos klikoni cdo link qe e shihni ne permbajtjen e email-it.**

**-> Instaloni Filtra apo aplikacione speciale te cilat e bjen te mundur zbulimin e ketyre domainave addressave.**

**-> Nese keni dyshime per ndonje email te quditshem i cili ka ardhur ne posten tuaj ju lirisht mund te beni forward ne email adresen tone dhe
stafi jon e kontrollon , emaila eshte cert@xor.al**
