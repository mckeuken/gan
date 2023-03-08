# GAN
**Achtergrond**

>De gemeente Amsterdam verzameld een groot aantal gegevens van hun burgers om de verschillende wettelijke taken uit te voeren. Deze taken richten zich onder andere op het zorgdomein (e.g., WMO, Jeugdzorg, publieke gezondheid zoals deze door de GGD wordt uitgevoerd). Doordat er verschillende zorgwetten zijn is het niet triviaal vanuit de privacy richtlijnen om persoonsgegevens vanuit verschillende zorgdomeinen binnen een persoon aan elkaar te koppelen. Hoewel er wel mogelijkheden zijn om dit te doen (e.g., microdata omgeving CBS, zicht en grip pilot vanuit de gemeente Amsterdam) zijn deze vaak omslachtig en duur.
Een andere uitdaging met het werken van persoonsgegevens is dat deze, zelfs binnen een enkele wet, niet zo maar gedeeld kunnen worden met andere interne of externe onderzoekers. Om dit mogelijk te maken zal er eerst (minimaal) een Data Protection Impact Assessment (DPIA) uitgevoerd moeten worden die gevolgd wordt door een Data Sharing Agreement (DSA). Dit process is op het moment van schrijven niet optimaal waardoor projecten langzaam van start kunnen gaan en andere kleine vraagstukken überhaupt niet opgepakt worden omdat het niet de tijdsinvestering van de DPIA niet waard is.

**Een alternatief**
>Vanuit de AI en data science domeinen zijn er methodes ontwikkeld die een gebruiker instaat stelt om aan de hand van persoonsgegevens synthetische data te creëren. Deze synthetische data bevat alle statistische kenmerken van de waargenomen persoonsgegevens, maar elk nieuw datapunt is dus niet gebaseerd op een individu. Een van de voordelen van synthetische data is dat het een aantal privacy processen mogelijk overbodig maakt waardoor het makkelijk wordt om data te combineren over wetten en te delen met interne en externe onderzoekers.

**Doel van dit notebook**
>Het doel van deze proof of concept (POC) notebook is om aan de hand van een veelgebruikt publiekelijke dataset het concept van synthetische data en een aantal kwaliteitscontroles te introduceren. Om daarna het gesprek met de privacy officier te kunnen voeren of:
synthetische data veelbelovend is voor de gemeente Amsterdam
aan welke kwaliteitseisen deze synthetische data moet voldoen voordat deze vrij gedeeld zou kunnen worden

