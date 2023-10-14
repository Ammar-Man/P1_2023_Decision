# 1- Rekommendationssystem (25p)
### Gör en slutsats, vilket presterade bättre och reflektera över varför.

Båda metoderna, kollaborativ filtrering (Collaborative Filtering) och innehållsbaserad filtrering (Content-based Filtering), har sina styrkor och svagheter. Slutsatsen om vilken metod som presterar bättre beror på flera faktorer inklusive tillgänglig data, användningskontext och användarens preferenser.

Kollaborativ filtrering (Collaborative Filtering):

Styrkor:

Användarorienterad: Baserar rekommendationer på användarens beteende och preferenser.
Upptäcker mönster: Kan upptäcka komplexa mönster och relationer mellan användare och objekt.
Kräver inte produktinformation: Fungerar bra även när detaljerad produktinformation saknas.

Svagheter:

Kall startproblem: Kan vara utmanande när det inte finns tillräckligt med data om användaren eller objekten (ny användare eller objekt).
Datakrävande: Kräver stora mängder data för att producera precisa rekommendationer.


Innehållsbaserad filtrering (Content-based Filtering):

Styrkor:

Objektorienterad: Baserar rekommendationer på egenskaper hos objekten själva, inte beroende av andra användares beteende.
Övervinner kall startproblem: Kan producera rekommendationer för nya objekt baserat på deras egenskaper.
Transparens: Mer transparent och förklarbar, eftersom rekommendationerna baseras på objektens egenskaper.

Svagheter:

Begränsad i upptäckande: Kan vara mindre effektiv i att upptäcka nya objekt eller oväntade preferenser hos användare.
Beroende av korrekt metadata: Kvaliteten på rekommendationerna är starkt beroende av kvaliteten och relevansen hos objektens metadata.

Reflektion:

Valet mellan kollaborativ filtrering och innehållsbaserad filtrering beror på användningsfallet och tillgänglig data. Om du har tillgång till riklig och relevanta användardata, och om målet är att rekommendera objekt baserat på liknande användares beteende, kan kollaborativ filtrering vara ett starkt val. Å andra sidan, om du har detaljerad metadata om objekten och vill rekommendera objekt baserat på deras egenskaper, kan innehållsbaserad filtrering vara mer lämplig.

I det här fallet verkar båda metoderna ha presterat bra och genererat relevanta rekommendationer. Valet mellan metoderna bör övervägas baserat på framtida behov, användarens preferenser och tillgängliga resurser. Ibland kan en hybridapproach som kombinerar både kollaborativ filtrering och innehållsbaserad filtrering ge ännu bättre resultat genom att balansera deras respektive styrkor och svagheter.



# 2- Hybrid rekommendationssystem (15p)
Ett hybridt rekommendationssystem som använder användarens 'betyg' från databasen för att generera resultat som påverkas av andra användares 'videobetyg'. Trots att databasen innehåller över 100 000 'betyg', visar resultaten ingen signifikant påverkan när vi tar bort 150 av användarens samarbetsfilter. Detta tyder på att förändringen inte har någon effekt.

# 3- Teoretiskt rekommendationssystem (10p)

Min reflektionsställning visar en grundlig förståelse för både kollaborativ filtrering och innehållsbaserad filtrering samt deras styrkor och svagheter. Jag har tydligt identifierat de olika aspekterna av varje metod och hur de passar olika användningsfall beroende på tillgänglig data och användarbehov.

När det gäller Spotifys RecSys tävlingssystem, verkar det som att deras tillvägagångssätt var mycket inriktat på att använda kollaborativ filtrering, särskilt användarbaserad närmaste-granne-metod (kNN) för att beräkna likheter och föreslå låtar. Deras användning av olika heuristiska metoder och tekniker som amplifikation, normalisering, och viktningsstrategier visar deras engagemang för att förbättra rekommendationskvaliteten.

När jag jämför mitt system med Spotify's RecSys-tillvägagångssätt finns det några likheter och områden som  båda fokuserar på:

Användning av Kollaborativ Filtrering: Både mitt system och Spotifys RecSys-system använder en form av kollaborativ filtrering. Jag använder användarbaserade metoder för att förstå användarpreferenser och rekommendera låtar baserat på likheter mellan användares beteenden.

Optimering av Rekommendationer: Både systemen utforskar olika metoder för att optimera kvaliteten på rekommendationerna. Jag använder heuristiska metoder, viktningsstrategier och andra tekniker för att förbättra träffsäkerheten och användarupplevelsen.

Effektiv Datahantering: Både systemen involverar omfattande datahantering. Jag bearbetar och normaliserar data, applicerar specifika villkor och manipulerar data för att skapa relevanta rekommendationer.

Fokus på Resurseffektivitet: Spotify's RecSys-tillvägagångssätt betonar minimala beräkningsresurser och visar att noggrannhet och relevans inte alltid kräver enorma datamängder eller komplexa algoritmer.

När det gäller utvecklingsmöjligheter finns det alltid utrymme för förbättring och innovation inom rekommendationssystem. En möjlig väg framåt kan vara att utforska hybridmetoder som kombinerar både kollaborativ filtrering och innehållsbaserad filtrering. Genom att integrera dessa två metoder kan man utnyttja fördelarna med båda och minimera deras nackdelar, vilket kan leda till ännu mer precisa och relevanta rekommendationer.

Men efter min hybridmetod sätt så var den ingen ändring så kansek jag må finna ett bättre sätt för hybridmetoder.

Dessutom, med tanke på mitt datahanteringsförmågor, kan jag också överväga att utforska tekniker inom djupinlärning och neurala nätverk. Dessa tekniker kan hjälpa till att extrahera komplexa mönster och relationer från data, vilket kan förbättra noggrannheten i mitt rekommendationer.

Sammanfattningsvis har både mitt system och Spotify's RecSys-tillvägagångssätt sina styrkor och har visat bra resultat. Genom att fortsätta experimentera och integrera olika metoder kan jag ytterligare förbättra mitt rekommendationssystem och skapa en ännu bättre noggrannhet.