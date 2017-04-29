# Landsv-gen
För att köra programmet:
1. Starta Julia-applicationen (nedladdning på https://julialang.org/)
2. Kopiera texten som finns i filen LandsvagenComplete.jl i denna GitHub.
3. Nu är programmet i terminalen.
4. För att starta programmet (genom att generera matrislistan av storlek 10) skriver du: list10 = greedStartUp(). Detta behöver du bara göra varje gång programmet startas och tar ungefär 10 min beroende på datorn.
5. Medan programmet startar kan du börja anteckna landsvägen som ska analyseras. Detta gör du genom att skriva upp korten från vänster till höger som: deck = [[1,6], [3,12], [2,5], [2,12], [4,2],...[3,10]] för de 52 korten i din landsväg. OBS! Den första siffran i varje kort är färgen och den andra valören.
6. Om du inte har en kortlek eller bara vill prova programmet utan att anteckna en landsväg på detta vis kan du skapa en slumpmässigt blandad kortlek på denna form genom kommandot: deck = newDeck().
7. För att använda programmet på denna landsväg som då är sparad under variabeln "deck" skriver du kommandot: fullGreed(deck).
8. Efter ca 3 min (beroende på tid) ger programmet sitt svar.
