#Lektion 1: Katt-och-råtta-lek

Vi ska skapa ett spel där katten ska försöka ta råttan. Du kontrollerar råttan med muspekaren och
försöker undvika att bli fångad av katten. Ju längre du håller dig ifrån honom desto fler poäng får du,
men se till att inte åka fast för då förlorar du poängen!

##Delmoment 1: Katten följer muspekaren

Vi börjar med att göra så katt spriten följer efter muspekaren med ett beat i bakgrunden.

1. Logga in på http://scratch.mit.edu/
>*Om du inte har kollat på introduktionsvideon så fråga en vuxen om hjälp!*

2. Tryck på **Skapa** på hemsidan

3. Om språket inte är **Svenska**, tryck på **jordklotet** och scrolla ner tills du hittar **Svenska**.
![Välj språk](/lektion1/img/selectlanguage.png)

4. Klicka på scenen bredvid *spriten*.
Byt till fliken **Bakgrunder**.
Tryck på **”välj bakgrund från biblioteket”**.
Välj sedan **inomhus/hall**.

5. Högerklicka på *spriten* och tryck på **info**.
Byt sedan namn på *spriten* till vad du vill, vi ger katten namnet Felix.

6. Se till att katten bara pekar åt vänster-höger genom att klicka på den här knappen:
![Välj rotationsstil](/lektion1/img/rotationstyle.png)

*Detta ser till att katten inte vänder sig upp och ner!*.

7. Skapa sedan följande script:
![kodblock](/lektion1/img/codeblock1.png)

*Kan du läsa och se steg för steg vad detta script gör för något?*

###Testa ditt projekt
**Klicka på den gröna flaggan**
* Följer katten muspekaren?
* Ser det ut som att han går när han rör sig?
* Rör han sig i rätt hastighet?

Nu ska vi spara ditt projekt så att du alltid kan komma åt det om du tar en paus eller om du stänger
av datorn!

8. Ge den namnet **Lektion 1** så att du kan enkelt hitta den igen.

9. Klicka på **Arkiv** och sedan **Spara nu**.

![Spara](/lektion1/img/savenow.png)

Du kan enkelt hitta den igen genom att gå till **dina grejor**, men om du vill kan du även **ladda ner** den
till din dator!

##Delmoment 2: Katten jagar råttan

Nu vill vi att katten ska jaga råttan istället för muspekaren.

10. Skapa en ny *sprite* genom att klicka på **”Välj sprite från biblioteket”**
Välj **djur/mouse1.**

11. Byt namn på *spriten* (se punkt 5 om du inte kommer ihåg hur man gör) till vad du vill, vi ger
råttan namnet Herbert.

12. Se till så att råttan bara pekar åt **vänster-höger** (se punkt 6 om du behöver hjälp).
. Klicka på förminska knappen och sedan på **råttan i scenen**, varje gång du trycker på råttan
blir den mindre.

![Förminska](/lektion1/img/makesmaller.png)

**6 musklickningar** borde göra den tillräckligt liten.

14. Ge råttan det här scriptet:
![kodblock](/lektion1/img/codeblock2.png)

*Vad gör detta script?*

###Testa ditt projekt
**Klicka på den gröna flaggan.**

Rör sig råttan med musmarkören?

Jagar katten råttan?

##Delmoment 3: Katten säger till när han har fångat råttan

Vi vill att katten ska veta när han har fångat råttan, och säga det till oss.

15. Ändra kattens *script* (det du skapade i punkt 6) så det ser ut så här:
![kodblock](/lektion1/img/codeblock2.png)
*Vad är det som sker nu i scriptet?*

###Testa ditt projekt
**Klicka på den gröna flaggan.**

Säger katten **Fångad!** när han har fångat råttan?

##Delmoment 4: Råttan blir ett spöke när han fångas
Istället för att katten säger någonting så vill vi att råttan ska förvandlas till ett spöke när han fångas.
16. Ändra i kattens script så att det skickar ut följande meddelande när han fångar råttan:
Vad händer nu om katten rör råttan?
17. Välj sedan klädseln fantasy/ghost2-a från biblioteket för råttan.
18. Tryck sedan på spökklädseln. Gör den lika liten som du gjorde råttklädseln i punkt 10 (6
musklickningar).
19. Byt namn på råttans klädslar så att råttklädseln heter ”levande” och spökklädseln heter
”död”.
20. Skapa ett nytt script till råttan för att förvandla honom till ett spöke när han blir fångad:
När sker detta script?
Testa ditt projekt
Klicka på den gröna flaggan.
* Blir råttan ett spöke när han fångas?
* Spelar katten de rätta ljuden när han ska?
* Står katten still tillräckligt länge för att råttan ska kunna ge sig iväg?
Detta kan du ändra genom att lägga ett ”vänta sekunder” block precis vid början av kattens
script.
##Delmoment 5: Räkna poäng
Nu lägger vi till ett poängsystem så vi vet hur bra vi är på att hålla råttan vid liv.
Vi börjar med att låta poängen vara 0 och höjer den med 1 varje sekund. Om katten fångar råttan
minskar vi poängen med -100.
21. Gå till blockgruppen Data
Skapa en variabel som heter ”poäng” för alla sprites.
22. På Scenen, skapa de här två scripten:
Vad händer i dessa script? Hur gör du om du vill att man förlorar mer/mindre poäng om man blir
fångad?
Hur gör du så att man får mer/mindre poäng per sekund?
Testa ditt projekt
Klicka på den gröna flaggan.
* Ökas poängen med 1 varje sekund?
* Minskas poängen med 100 när Herbert fångas?
* Vad händer när råttan fångas innan poängen har blivit hundra?
Ändra hur mycket poäng man förlorar om du tycker att det är för mycket!
* Nollställs poängen när du startar om spelet?
Glöm inte att spara ditt projekt
Kom ihåg att den ska heta Lektion 1 så att du enkelt kan hitta den igen!
Berätta och förklara!
Visa ditt spel för någon vuxen!
Sätt spelet till helskärm så att man kan visa det ordentligt!
Tryck på den blåa knappen ovanför scenen!
Berätta vad du har lärt dig. Svara på frågorna:
1. Hur gör man för att få en sprite att säga någonting?
2. Hur gör man ett poäng räknings system?
3. Kan du få en sprite att följa efter musen?
Bra jobbat, du är nu klar med hela lektion 1 och kan börja på lektion 2!