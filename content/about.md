---
Title: OM
Description: En sida om vilka tekniker jag använder
---

Om-sida
==========================

Denna sida är byggd med ett Pico ramverk som är ett CMS(Content Management System), detta för att smidigare kunna bygga en webbplats utan att lägga ner för mycket tid på att koda en webbplats helt från början. Med pico använder man sig av filer för att bygga en sida istället för en databas vilket också kallas för "flat-file". 

Dem olika sidorna på webbplatsen är skrivna i markdown filer som sedan parsas till HTML. Grunden till sidan är kodat med HTML, och twig används för att hantera layouten. Sedan stylas sidan med hjälp av CSS och vi använder oss av SASS för att kunna skapa olika moduler där vi kan dela upp vår CSS kod samt skapa olika variabler för att sedan importera modulerna.

Sidan har även gjorts responsiv med hjälp av media queries som gör att sidan ska vara lätt att använda både små och stora skärmar.

Design-mässigt så har några tekniker implementerats för att göra sidan mer behaglig och läsbar, och det är bland annat att lägga till vertikal rytm i texten genom att ändra på textstorlek samt radavstånd.