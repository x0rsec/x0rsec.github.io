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

## Përmbajtja e Web Faqes

Faqja mashtruese është e klonuar nga faqja zyrtare e Raiffeisen Bank. versioni i faqes mashtruese duket të jetë version i viteve paraprake sepse versioni aktual i bankes është tjeter në krahasim me faqen mashtruese. Shih foton më poshte te faqes mashtruese.

![image6]({{ site.baseurl }}/images/home.png){:.images}



## Këshillat për mbrojtje nga Phishing-u.


-> Duhet të keni kujdes në cdo email qe ju vije , nese keni dyshime ju lutem mos e hape.

-> Mos klikoni çdo link qe e shihni ne permbajtjen të email-it.

-> Instaloni filtra **"Anti Phishing"** neper browseret e juaj.



Për çfar do këshilla na kontaktoni në email **cert@xor.al**
