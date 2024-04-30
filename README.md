# **Archiveren van data en surveys vanuit Limesurvey 3**

## Introductie 
Met de introductie van Limesurvey 5 in Januari 2024 kijken we stilaan naar het uitfaseren van Limesurvey 3, en daarvoor is het belangrijk dat we alle onderzoeksdata goed archiveren. Dit houdt zowel de resultaten van het onderzoek in, maar ook de survey-structuur zelf! Om je hierbij te helpen is dit stappenplan opgesteld, die je stap-voor-stap uitlegt hoe je je data uit Limesurvey haalt en upload in een repository, zoals het Open Science Framework (OSF). Vorig jaar hebben we de oefening gemaakt waarbij we van iedereen een OSF-account vroegen, waardoor je reeds een account zou moeten hebben. Maar indien je nog geen OSF-account hebt, dan kan je die eenvoudig en snel aanmaken via <https://osf.io/>. Kort samengevat zijn de volgende stappen nodig:
1.	Gebruik je OSF-account om een repository aan te maken, dit zal je moeten doen voor elke studie apart.
2.	In deze repository maak je enkele mappen aan, voor de data en de surveystructuur apart. 
3.	Je downloadt de gegevens vanuit Limesurvey 3.
4.	Deze moet je vervolgens uploaden in de repository die je aangemaakt hebt.
Het is vervolgens aan te raden om mede-onderzoekers even te laten controleren of alles correct is, en vervolgens kan je veilig je survey verwijderen uit Limesurvey 3! Dit klinkt wellicht allemaal wat indrukwekkend, maar hieronder wordt elke stap verder uitgelegd!

## **Stap 1**:  Gebruik je OSF-account om een repository aan te maken, dit zal je moeten doen voor elke studie apart.
- Om in te loggen in OSF moet je gewoon naar de website gaan (<https://osf.io/>), en kies je rechtsboven de blauwe optie “Sign In”. Mocht je toch geen OSF-account hebben, dan kan je de groene optie “Sign Up” gebruiken en de stappen daar volgen. 
- Na het inloggen maak je voor iedere aparte studie je een nieuw project aan, hiervoor kies je rechtsboven de groene optie “Create new project”.

![Het venster als je inlogt op OSF.](/Images/Afbeelding1.png){width=600px}
  
!! Let er bij het maken van je project op dat je een server kiest binnen Europa, onder de optie “Storage location”.
  
![Kies zeker een Europese storage location.](/Images/Afbeelding2.png){width=600px}

!! Mocht je toch op een verkeerde storage zitten, dan kan je rechtsboven op je profiel klikken, en de locatie nog altijd aanpassen onder “Settings” en vervolgens “Account settings”. 

## **Stap 2**: In deze repository maak je enkele mappen aan, voor de data en de surveystructuur apart. 
- Om verschillende mappen aan te maken in je project, kan je onder “Files” de storage highlighten. Dan verschijnen er enkele opties om folders te maken, hierbij kies je vervolgens “Create Folder”.

![Mappen aanmaken in OSF.](/Images/Afbeelding3.png){width=600px}
 
- Vervolgens maken we twee folders aan, één voor de resultaten en één voor de operationalisatie van de studie, wat in dit geval de survey is. In andere woorden; de surveystructuur (.lss-bestand). Voor andere studies kunnen dit andere bestanden zijn, b.v., wanneer je gebruik maakte van Inquisit om je data te verzamelen.

![In dit voorbeeld hebben we een derde folder aangemaakt, getiteld “Scripts”. In deze folder kan je je analyse-scripts plaatsen, zoals een SPSS- of een R-bestand. .](/Images/Afbeelding4.png){width=600px}

## **Stap 3**: Je downloadt de gegevens vanuit Limesurvey 3.
- Vervolgens kunnen we de benodigde data uit Limesurvey 3 halen, daarvoor ga je naar ls3.ou.nl/admin. Let op dat je hier inlogt met een apart account voor Limesurvey 3, en dus **niet** via de centrale login die we ondertussen van Limesurvey 5 gewend zijn! Mocht je je inloggegevens vergeten zijn, dan kan je contact opnemen met Mat Heinen (<mat.heinen@ou.nl>) of eventueel met Nico van der Wiel (<nico.vanderwiel@ou.nl>). 
- Kies de enquête die je wil archiveren, en dan is het een kwestie van de data te downloaden, en te surveystructuur te downloaden. Om de surveystructuur te downloaden, kies je bij bovenaan het scherm voor de optie “Tonen/Exporteren”, waarna er zich een scherm toont met verschillende opties:

![Kies bovenaan voor "Tonen/Exporteren".](/Images/Afbeelding5.png){width=600px}

![Verschillende opties om te exporteren worden weergegeven.](/Images/Afbeelding6.png){width=600px}

- Hier kan je de surveystructuur vinden (.lss), maar met het oog op Open Science en het gebruik van FAIR data is het aangeraden om de structuur ook te downloaden als .lsa, .txt., .html, en als afdrukbare enquete. Dit zijn respectievelijk de eerste, twee, vijfde, zesde, en zevende opties. 
- Om vervolgens de resultaten te downloaden, kies je eerst rechts de optie voor “Responses” en vervolgens kan je bovenaan kiezen voor de optie “Exporteer gegevens”, en bij het daaropvolgende dropdown-menu opnieuw te kiezen voor “Exporteer gegevens”.

![ ](/Images/Afbeelding7.png){width=600px} 

- Vervolgens kan je de data eenvoudig downloaden in verschillende formaten. Let erop dat je de vragen exporteert als “Volledige vraag”, dan wordt zowel de vraagcode vanzelf als variablenaam meegegeven, en de vraag zelf als label.
 
![ ](//Images/Afbeelding8.png){width=600px}

 Met het oog opnieuw op Open Science en het gebruik van FAIR data raden we aan om de data te downloaden als .csv, Excel, beide R-bestanden, en als SPSS). 


- Om de data te downloaden als SPSS-bestand kies je in de vorige stap “Exporteer responsen naar SPSS” als optie: 
 
![ ](//Images/Afbeelding9.png){width=600px}

- In het volgende scherm kies je vervolgens beide bestanden.

![ ](/Images/Afbeelding10.png){width=600px}

## **Stap 4**: Deze moet je vervolgens uploaden in de repository die je aangemaakt hebt.
- Tenslotte is het een kwestie van de vers gedownloade bestand up te loaden in de map die we aangemaakt hebben in OSF. Hiervoor kan je de bestanden gewoon drag-and-droppen. Je krijgt vervolgens een bevestiging dat het gelukt is!

![ ](/Images/Afbeelding11.png){width=600px} 

- Je kan vervolgens hetzelfde doen voor de resultaten:
 
![ ](/Images/Afbeelding12.png){width=600px}

En daarmee ben je rond! Je bestanden staan nu veilig op OSF. De enige stap die nog rest is, als jij en je co-auteurs alles hebben gecontroleerd, de bestanden ook toegankelijk te maken voor anderen. Dit doe je door rechtsboven je project openbaar te zetten “Make public”.

![Publiek maken van je project.](/Images/Afbeelding13.png){width=600px}

Je kunt je repository alleen op openbaar zetten als de data geanonimiseerd zijn. Vaak zijn ze dat al vanaf het begin omdat we meestal proberen om geen persoonsgegevens te verzamelen, maar soms is het verzamelen van persoonsgegevens onvermijdelijk en moet je de data eerst anonimiseren. Als je twijfelt over of je dataset persoonsgegevens bevat (i.e. identificeerbaar is) of geanonimiseerd is, raadpleeg dat de data steward via een mailtje naar <datasteward@ou.nl>. Voor wat meer achtergrondinformatie over open data kun je <https://guide.opens.science/open-data.html> raadplegen.
Als de data zijn gecontroleerd en indien mogelijk openbaar zijn gemaakt, dan kan je je studie veilig uit Limesurvey 3 verwijderen. Dit doe je door te kiezen voor de optie “Verwijder enquete”, die bovenaan terug te vinden is bij “Hulpmiddelen”. 

![ ](/Images/Afbeelding14.png){width=600px}

Tenslotte is het nog een kwestie van dit proces te herhalen tot je overzicht van studies in LimeSurvey helemaal leeg is! 
