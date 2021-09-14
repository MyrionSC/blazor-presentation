Intro
- RazorPages vs BlazorServer vs BlazorWASM
- VanDa

Demo
- Statistik
  - Components
    - Parametre
    - EventCallback
  - JS interop (plotly)
  - Intellisense
    - Enum i parameter

Pros
- Forenet model på FE og BE
- Samlet validering af model
- Refactor
- C#, LINQ
- Eksisterer parameter på objekt?
- Compiletime typechecking (kan du kalde denne metode på denne type?)
- cshtml kompilerer til flot html i min mening
- UI og backend i samme repo giver mulighed for mere integration
  - Rider ctrl+click på url
- God officiel dokumentation

Cons
- Ikke moden 
  - mangler biblioteker
  - ikke meget dokumentation
  - Mangler udviklingsværktøjer
    - fx. Hot reload kommer først med dotnet 6
- Reflection er lidt magisk nogle gange
  - kunne ikke finde ud af two way bind
  - 
- Webassembly er sværere at have indsigt i (måske mangler jeg bare at lære det)
  - Fejlbeskeder er ikke altid lige beskrivende
  ![image](https://user-images.githubusercontent.com/8692680/131094273-e3fe348f-fad9-45ff-8146-840c051ca7fb.png)
  - Mulighed for raceconditions hvis ikke påpasselig

- Smertefuld debug
  - Skal kompileres til det og browser skal startes med ikke standard flag
  - Mangler understøttelse i Rider (ikke mere)
  - Ingen debug i produktion
  ![image](https://user-images.githubusercontent.com/8692680/133121375-64eace43-a79c-47da-9ca3-b05d9542d8a1.png)
 
- Bugs?
  - Raceconditions af publish med compression

