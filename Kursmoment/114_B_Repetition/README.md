Välkomna tillbaka till Technical Direction!

Vi förstår att vissa kanske hunnit glömma bort en del av det vi gick igenom sist, så idag är tanken att vi ska återbekanta oss med Houdini.

## Uppgift

### Bygg en trälåda

<img src="https://github.com/user-attachments/assets/57cfcaaa-a6c7-4a29-8bd3-21a2bc239d86" align="right" width="400">

- Utgå ifrån en box, så att du kan använda boxen för att enkelt och snabbt justera trälådans dimensioner

- Boxen ska inkludera:
    - Sidor av plankor och antalet plankor ska kunna styras med en parameter.
    - Ett yttre hölje, med en diagonal planka som går tvärs över varje sida.
 
> ### Tips:
> - Använd Triangulate SOP för att triangulera quads
> - PolyExtrude:s "Inset" parameter kan du använda för att ge en bredd till dina edges, och inaktivera "Output Front" för att ta bort allt utom de edgar du gett en bredd. På så sätt kan du få till det yttre höljet.


## Underlag
- [**Wiki - SOP**](https://github.com/Studio-Konkret/Technical-Direction/wiki/SOP)
- [**Wiki - UI**](https://github.com/Studio-Konkret/Technical-Direction/wiki/UI-&-Noder)
