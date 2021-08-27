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
- Reflection er lidt magisk nogle gange (
  - kunne ikke finde ud af bind
- Webassembly er sværere at have indsigt i (måske mangler jeg bare at lære det)
  - Fejlbeskeder er ikke altid lige beskrivende
  ![image](https://user-images.githubusercontent.com/8692680/131094273-e3fe348f-fad9-45ff-8146-840c051ca7fb.png)

- Smertefuld debug
  - Skal kompileres til det og browser skal startes med ikke standard flag
  - Mangler understøttelse i Rider (ikke mere)
- Bugs?
  - Raceconditions af publish med compression
- Miljøvariabel som styrer miljø skal sættes i header (undersøg igen)
