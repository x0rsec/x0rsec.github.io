---
layout: post
title: "KUJDES - Phishing"
categories: [lajme, analiza]
---

## Përmbledhje

Sektori bankar gjithmone ka qenë target nga sulmet e ndryshme kibernetike në veçanti nga **"Social Engineering - Phishing"** ku ka për qëllim vjedhjen e të
dhënave të ndjëshme, qofshin ato të individeve apo të bizneseve.


## Çka është Phishing

**Phishingu** është proces i perpjekjes për të marr informacione të ndjeshme, si emrat e përdoruresve, fjalëkalimet dhe detajet e kartës së kreditit.
Emailet që pretendojn se janë nga faqet zyrtare të ndonje entiteti bankare , social apo ndonjë kompani. Zakonisht, këto përdoren si karrem për të mashturar masën. Aktiviteti **Social Engineering** është formë e mashtrimit.


## Raiffeisen Phishing

Në bazë të analizave tona në javen e fundit kemi vërejtur një rritje të konsiderushme të Web-Faqeve të cilat jan duke u klonuar nga
faqja zyrtare e Bankes Raiffeisen.

## Analiza teknike

Para se të hyjm në analizen teknike duhet të keni të qartë se: Domain zyrtar i bankes Raiffeisen është **https://www.raiffeisen-kosovo.com/**

## Kujdes nga Emri

Si mund ta shihni dhe ju vetë, në fotot më posht të domain-it, duam te ju informojmë se domain është i regjistruar me daten 24.11.2019.

![image6]({{ site.baseurl }}/images/registrat.png){:.images}

Domain për momentin është aktiv dhe gjithashtu posedon SSL Certifikaten të leshuar nga Let's Encrypt, sikur ne foto me poshtë.


![image6]({{ site.baseurl }}/images/ssl.png){:.images}

## Permbajtja e Web Faqes

Faqja mashtruese është e klonuar nga faqja zyrtare e Raiffeisen Bank. versioni i faqes mashtruese duket te jetë version i viteve paraprake sepse versioni aktual i bankes eshte tjeter ne krahasim me faqen mashtruese. Shih foton me poshte te faqes mashtruese.

![image6]({{ site.baseurl }}/images/home.png){:.images}



## Keshillat për mbrojtje nga Phishing-u.


**-> Duhet të keni kujdes në cdo email qe ju vije , nese keni dyshime ju lutem mos e hape.*

**-> Mos klikoni cdo link qe e shihni ne permbajtjen e email-it.**

**-> Instaloni Filtra apo aplikacione speciale te cilat e bjen te mundur zbulimin e ketyre domainave addressave.**

**-> Nese keni dyshime per ndonje email te quditshem i cili ka ardhur ne posten tuaj ju lirisht mund te beni forward ne email adresen tone dhe
stafi jon e kontrollon , emaila eshte cert@xor.al**
