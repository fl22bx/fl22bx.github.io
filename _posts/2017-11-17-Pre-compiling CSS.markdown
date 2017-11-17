---
title: Pre-Compiling CSS
date: 2017-11-17
categories: Examination 1, 1dv022
---
#Vad jag tycker om Pre-compiling 
Det är väldigt skönt att kunna dela upp CSS koden i olika block, att ha en huvudfil där man definierar variabler som man sen utnyttja i koden. I och med detta är det enkelt att ändta på stilen. Vill jag ändra en färg ändrar jag bara i variablerna som sen ändrar allt det som jag vill ändra.

Det kändes som jag inte behövde skriva lika mycket kod som i vanlig CSS och framförallt blev det väldigt mycket enklare att få en överblick över vad jag  hade gjort och vad som gjorde vad i koden. Variablerna gjorde det superenkelt att arbeta och få en överblick över arbetet.

En annan styrka som Sass har är att man kan utnyttja kod som man redan har skrivit, genom att använda @include så kan man skriva kod med exempelvis Mixin och utnyttja denna kod på flertalställen, dett unerlättar då man inte behöver skriva om samma kod flera gånger. Vill man sedan ändra stilen på sidan blir det enkelt att bara ändra i denna kod och sen gäller denna ändring på samtliga ställen.

#Jämfört med 'vanlig' CSS
Skillnaden mellan detta och vanlig CSS enligt mig är att det blir mycket mer lättarbetat, Vanlig CSS tyckte jag var svårt att få en överblick av, det blev svårt att navigera runt koden och man kunde inte riktigt få en helhetsblick över vad som faktiskt hände. 

#Vilka tekniker jag använde
Jag använde mig av teknikerna MixIn, Nesting som gjorde det väldigt enkelt och se vilket element man faktiskt arbetade med. samt variabler och uträkningar. 

#Fördelar och Nackdelar
Fördelarna är som jag redan sagt att det blir lättarbetat men får fler verktyg som gör det möjligt att anpassa sidan så som man vill ha den.

nackdelarna är i detta skedde enligt mig väldigt få, en av dem kan vara att det försvårar debuggingen samt att man lägger till ytterliggare verktyg i verktygslådan som man behöver kunna.