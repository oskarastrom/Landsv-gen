# Landsv-gen
Koden till Gymnasiearbetet "Landsvägen"
För att köra programmet:
1. Starta Julia-applicationen (nedladdning på https://julialang.org/)
2. Ladda ned filen LandsvagenComplete.jl
3. Lokalisera var filen ligger i julia-terminalen, detta kan du göra genom att skriva readdir(), vilket visar de filer och mappar som finns där du befinner dig nu. Använd sedan cd("fil/mappnamn") för att ta dig framåt tills du ser filen i readdir(). Om du råkar gå in i fel mapp kan du använda cd() utan något fil/mappnamn för att gå ett steg bakåt.
4. När filen är upphittad använder du kommandot include("LandsvagenComplete")
5. Nu är programmet i terminalen.
6. För att starta programmet (genom att generera matrislistan av storlek 10) skriver du: list10 = greedStartUp(). Detta behöver du bara göra varje gång programmet startas och tar ungefär 10 min beroende på datorn.
7. Medan programmet startar kan du börja anteckna landsvägen som ska analyseras. Detta gör du genom att skriva upp korten från vänster till höger som: deck = [[1,6], [3,12], [2,5], [2,12], [4,2],...[3,10]] för de 52 korten i din landsväg. OBS! Den första siffran i varje kort är färgen och den andra valören.
8. Om du inte har en kortlek eller bara vill prova programmet utan att anteckna en landsväg på detta vis kan du skapa en slumpmässigt blandad kortlek på denna form genom kommandot: deck = newDeck()
9. För att använda programmet på denna landsväg som då är sparad under variabeln "deck" skriver du kommandot: fullGreed(deck)
10. Efter ca 3 min (beroende på tid) ger programmet sitt svar.
