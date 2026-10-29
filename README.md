# swe-transcribe
Det här en en verktygslåda för olika transkriberingsscenarior.
Några försök att skapa ett gäng verktyg för att göra transkriberingslösningar av svenska lokalt på ens egna dator.
I offentliga organisationer så kämpar vi med att det finns så mycket som hamnar under någon sorts sekretess ifall vi ska ha det som arbetsmaterial. Inga personuppgifter ska delas till tredje land. Våra datorer är kapabla att använda ai lokalt och jag är helt säker på att det inte behöver vara så svårt för slutanvändaren att det ska vara lätt att göra rätt.

Jag har vibecodat med hjälp av gemini grunden av ett antal verktyg de fungerar hjälpligt och behöver poleras.
De flesta använder med Kungliga bibliotekets svenska whispermodell som scripten hjälper dig att ladda ner och optimera automatiskt på din dator vid första körningen.
Några verktyg har jag kopplat till ollama för att kunna göra efterarbetningar lokalt på datorn, kanske ska det beroendet byggas bort i vissa av scripten men det är smidigt att ha.

* **Edda Classic (Diktafonen):** Det robusta arbetsverktyget. Du pratar till punkt, trycker stopp, och systemet bearbetar hela ljudfilen i ett svep. _Målgrupp: Långa, ostörda journalanteckningar och utläggningar med perfekt grammatik._

* **Edda Stream (Snabbharen):** Tvåstegsraketen för realtid. Ger omedelbar respons på skärmen (via en liten modell) och djupreviderar automatiskt meningen med perfekt interpunktion så fort du tar ett andetag (via den stora modellen). _Målgrupp: Den som vill tänka högt och se texten växa fram levande på skärmen._

* **Saga (Den röstaktiverade):** Handsfree-assistenten. Lyssnar ständigt men aktiveras bara av din röst (VAD), och skriver ut hela meningar när du tystnar. _Målgrupp: Snabba inhopp och chatt-liknande interaktioner där man inte vill trycka på knappar._

* **Harald Desktop (Analysbänken):** Den lokala, sekretessäkra motsvarigheten till ChatGPT. Tar emot inklistrad text, pratar med lokala Ollama-modeller och sparar allt i en raderbar DuckDB-databas. _Målgrupp: Efterbearbetning, sammanfattningar och action-points av transkriberat material._
