<style> span.sb {
    border: 1px solid lightgray;
    border-radius: 5px;
    background: lightgray;
    padding: 2px 5px 4px 5px;
    font-style: normal;
    display: inline-block;
  } span.sb img {
    position: relative;
    margin: 0 2px 0 0 !important;
    top: 5px;
  }</style>

# Programmera en rymdfarkost

Nu ska du få bygga ett spel i Scratch där en rymdfarkost ska försöka fånga en cirkel i rymden.


<a href="https://scratch.mit.edu/projects/299972562/editor/" target="_blank">https://scratch.mit.edu/projects/299972562/editor/</a>

Vi har redan gjort en rymdbakgrund och lagt ut en rymdfarkost so du ska styra. Även alla block som behövs ligger framme.

> Om du undrar _hur_ eller _varför_ det fungerar eller om du har andra frågor kan du prata med någon av volontärerna.


### 1 – Nu programmerar vi!

1. För att rymdraketen ska åka framåt behöver vi använda blocket <span class="sb">gå 2 steg</span> och sätta den efter blocket <span class="sb">när ![flagga](flagga.png) klickas på</span>.

2. Tryck på flaggan för att testa så att rymdfarkosten rör sig framåt varje gång du trycker.

### 2 – Åk framåt

Nu ska vi få rymdfarkosten att gå 2 steg hela tiden - för alltid.

1. Vi får flytta <i class="sb">gå 2 steg</i> till blocket <i class="sb">för alltid</i> och stoppa in det där.
2. Sen drar vi <i class="sb">för alltid > gå 2 steg</i> till start-blocket <i class="sb">när ![flagga](flagga.png)klickas på</i>.

### 3 – Starta från början

När vi trycker på den gröna flaggan så börjar inte rymdfarkosten om från början. Vi måste säga till den att den ska gå till en position när den gröna flaggan klickas på.

1. Lägg blocket <i class="sb">gå till x:-115 y:-74</i> mellan <i class="sb">när ![flagga](flagga.png)klickas på</i> och <i class="sb">för alltid</i>.

    ![Skript 3](skript-03.png)

> Tryck på flaggan några gånger och se hur rymdfarkosten alltid börjar på samma position.

### 4 – Styr rymdfarkosten

Nu ska vi styra rymdfarkosten genom att trycka på piltangenterna på tangentbordet.

1. När vänsterpil trycks ned vill vi att skalbaggen ska vända åt vänster. Dra blocket <i class="sb">vänd vänster 15 grader</i> till blocket <i class="sb">när vänsterpil trycks ned</i>.

    ![När vänsterpil vänd åt vänster](skript-04a.png)

    > Starta spelet och tryck på vänsterpilen på tangentbordet flera gånger. Svänger rymdfarkosten åt vänster?

2. Gör samma sak med <i class="sb">när högerpil trycks ned</i> och <i class="sb">vänd höger 15 grader</i>.

### 5 – Kolla om rymdfarkosten rör vid cirkeln

Efter att vi gått framåt 2 steg så ska vi kolla om vi <span class="sb">rör vid Cirkel</span>.

1. Sätt in blocket <i class="sb">rör vid Cirkel</i> på den tomma rutan av <i class="sb">om <> då</i>-blocket.  
2. Dra även in <i class="sb">Vi lyckades ta cirkeln!</i> in i <i class="sb">om <> då</i> och sen även <i class="sb">stoppa alla</i>.  
3. Slutligen flyttar vi hela <i class="sb">om <> då</i>-blocket och lägger det efter <i class="sb">gå 2 steg</i>.

> Starta spelet igen. Säger din rymdfarkost något när du lyckas ta cirkeln?

### 6 – Kolla om rymdfarkosten rör vid satelliten Mats

På samma sätt som förra steget. Om vi rör vid satelliten Mats så ska vi säga _Åh nej! Vi krockade med satelliten Mats!_.

1. Sätt in blocket <i class="sb">rör vid Satelliten Mats</i> på den tomma rutan av <i class="sb">om <> då</i>-blocket.  
2. Dra även in <i class="sb">Åh nej! Vi krockade med satelliten Mats!</i> in i <i class="sb">om <> då</i> och sen även <i class="sb">stoppa alla</i>.  
3. Slutligen flyttar vi hela <i class="sb">om <> då</i>-blocket och lägger det efter <i class="sb">gå 2 steg</i>.

> Hur hela skriptet ser ut kan du se på nästa sida, men _försök gärna själv först_.

## Ett färdigt spel

### Fortsättning

Du kan fortsätta programmera hemma eller i skolan. Det finns mer att göra och fler utmaningar hittar du på [kodboken.se](https://kodboken.se).
