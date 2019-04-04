<style> span.sb {
    border: 1px solid lightgray;
    border-radius: 5px;
    background: lightgray;
    padding: 2px 5px 4px 5px;
    font-style: normal;
    display: inline-block;
  } span.sb img {
    position: relative;
    width: 24px;
    height: 25px;
    margin: 0 2px 0 0 !important;
    top: 5px;
  }</style>

# Programmera en rymdfarkost

Nu ska du få bygga ett spel i Scratch där en rymdfarkost ska försöka fånga en cirkel i rymden.


<a href="https://scratch.mit.edu/projects/299972562/editor/" target="_blank">Klicka här för att öppna Scratch-uppgiften</a>

Vi har redan gjort en rymdbakgrund och lagt ut en rymdfarkost so du ska styra. Även alla block som behövs ligger framme.

> Om du undrar _hur_ eller _varför_ det fungerar eller om du har andra frågor kan du prata med någon av volontärerna.


### 1 – Nu programmerar vi!

1. För att rymdraketen ska åka framåt behöver vi använda blocket <span class="sb">gå 2 steg</span> och sätta den efter blocket <span class="sb">när ![flagga](flagga.png) klickas på</span>.

2. Tryck på flaggan för att testa så att rymdfarkosten rör sig framåt varje gång du trycker.

### 2 – Åk framåt

Nu ska vi få rymdfarkosten att gå 2 steg hela tiden - för alltid.

1. Vi får flytta <span class="sb">gå 2 steg</span> till blocket <span class="sb">för alltid</span> och stoppa in det där.
2. Sen drar vi <span class="sb">för alltid > gå 2 steg</span> till start-blocket <span class="sb">när ![flagga](flagga.png)klickas på</span>.

### 3 – Starta från början

När vi trycker på den gröna flaggan så börjar inte rymdfarkosten om från början. Vi måste säga till den att den ska gå till en position när den gröna flaggan klickas på.

1. Lägg blocket <span class="sb">gå till x:-115 y:-74</span> mellan <span class="sb">när ![flagga](flagga.png)klickas på</span> och <span class="sb">för alltid</span>.

    ![Skript 3](skript-03.png)

> Tryck på flaggan några gånger och se hur rymdfarkosten alltid börjar på samma position.

### 4 – Styr rymdfarkosten

Nu ska vi styra rymdfarkosten genom att trycka på piltangenterna på tangentbordet.

1. När vänsterpil trycks ned vill vi att skalbaggen ska vända åt vänster. Dra blocket <span class="sb">vänd vänster 15 grader</span> till blocket <span class="sb">när vänsterpil trycks ned</span>.

    ![När vänsterpil vänd åt vänster](skript-04a.png)

    > Starta spelet och tryck på vänsterpilen på tangentbordet flera gånger. Svänger rymdfarkosten åt vänster?

2. Gör samma sak med <span class="sb">när högerpil trycks ned</span> och <span class="sb">vänd höger 15 grader</span>.

### 5 – Kolla om rymdfarkosten rör vid cirkeln

Efter att vi gått framåt 2 steg så ska vi kolla om vi <span class="sb">rör vid Cirkel</span>.

1. Sätt in blocket <span class="sb">rör vid Cirkel</span> på den tomma rutan av <span class="sb">om <> då</span>-blocket.  
2. Dra även in <span class="sb">Vi lyckades ta cirkeln!</span> in i <span class="sb">om <> då</span> och sen även <span class="sb">stoppa alla</span>.  
3. Slutligen flyttar vi hela <span class="sb">om <> då</span>-blocket och lägger det efter <span class="sb">gå 2 steg</span>.

> Starta spelet igen. Säger din rymdfarkost något när du lyckas ta cirkeln?

### 6 – Kolla om rymdfarkosten rör vid satelliten Mats

På samma sätt som förra steget. Om vi rör vid satelliten Mats så ska vi säga _Åh nej! Vi krockade med satelliten Mats!_.

1. Sätt in blocket <span class="sb">rör vid Satelliten Mats</span> på den tomma rutan av <span class="sb">om <> då</span>-blocket.  
2. Dra även in <span class="sb">Åh nej! Vi krockade med satelliten Mats!</span> in i <span class="sb">om <> då</span> och sen även <span class="sb">stoppa alla</span>.  
3. Slutligen flyttar vi hela <span class="sb">om <> då</span>-blocket och lägger det efter <span class="sb">gå 2 steg</span>.

> Hur hela skriptet ser ut kan du se på nästa sida, men _försök gärna själv först_.

## Ett färdigt spel

Så här ser hela skriptet ut när det är färdigt. Det behöver inte vara exakt likadant på alla ställen så länge det fungerar som du vill.

### Fortsättning

Du kan fortsätta programmera hemma eller i skolan. Det finns mer att göra och fler utmaningar hittar du på [kodboken.se](https://kodboken.se).
