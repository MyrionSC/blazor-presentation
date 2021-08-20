Intro
- RazorPages vs BlazorServer vs BlazorWASM

Pros
- Forenet model på FE og BE
- Samlet validering (test)
- Refactor
- C#, LINQ
- Eksisterer parameter på objekt?
- Compiletime typechecking (kan du kalde denne metode på denne type?)
- cshtml kompilerer til flot html i min mening
- Roslyn giver mulighed for nice udviklingsværktøjer
  - Rider ctrl+click på url

Cons
- Ikke moden 
  - mangler biblioteker
  - ikke meget dokumentation
  - Mangler udviklingsværktøjer
    - fx. Hot reload kommer først med dotnet 6
- Webassembly er sværere at have indsigt i (måske mangler jeg bare at lære det)
- Smertefuld debug
  - Skal kompileres til det og browser skal startes med ikke standard flag
  - Mangler understøttelse i Rider
- Bugs?
  - Raceconditions af publish med compression
- Miljøvariabel som styrer miljø skal sættes i header (undersøg igen)
