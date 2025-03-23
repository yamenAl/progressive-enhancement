

# Progressive Enhancement

Een oefening in het ontwerpen en bouwen van websites volgens het principe van Progressive Enhancement

In het college _S09W2-01-Progressive-Enhancement_ wordt behandeld wat Progressive Enhancement is.



## Doel van deze opdracht

Één van de mooiste [principes](https://www.w3.org/DesignIssues/Principles.html) van het web is dat iedereen met een computer en een browser het web kan gebruiken. [Het web is voor iedereen](https://www.youtube.com/watch?v=UMNFehJIi0E). 

Maar het web is geen gecontroleerde (programmeer) omgeving, je kan er gerust van uit gaan dat niemand precies hetzelfde te zien krijgt als wat jij in je browser ziet. Er zijn technische beperkingen, zoals afmetingen van de browser, type van de browser, versie van de browser, combinatie van browser extensies, grootte van het apparaat, manier van interactie, kwaliteit van de hardware, kwaliteit van het netwerk en er zijn mensen, allemaal verschillende mensen ...

Het doel van deze opdracht is te leren hoe je een website kan ontwerpen en maken met behulp van _Progressive Enhancement_ zodat het voor iedereen toegankelijk is.

### Progressive enhancement
Progressive Enhancement is een _(coding) strategy_ waarmee je er voor kan zorgen dat je website het altijd doet. 

1) Bepaal eerst de _core functionality_ van wat je gaat maken
2) Bouw die functionaliteit met de _simpelste techniek_ (meestal HTML, met een klein beetje Mobile First CSS voor de huisstijl)
3) Voeg daarna _extra enhancements_ toe met CSS en client-side JS, om de User Experience te verbeteren! (de leukste stap, waar veel frontenders meteen heen springen)

![image](https://github.com/fdnd-task/progressive-enhancement/assets/1391509/f6d0490b-6748-4fc8-8a63-d33d2f2d0b68)
<br><small>_The skateboard may be a little slower, but it doesn’t stop the user getting to where they want to go. So, if the user’s browser doesn’t support JavaScript or modern CSS then it doesn’t break_ - Andy Bell
</small>



## Aanpak

Voor deze opdracht ga je een aantal UI componenten ontwerpen, bouwen en testen in verschillende lagen, volgens het principe van _Progressive Enhancement_. 

Fork deze leertaak en ga aan de slag met de [files die klaar staan](https://fdnd-task.github.io/progressive-enhancement/).

Voor elk component staat een HTML-file klaar met een demo video van het eindresultaat. 
In de HTML van elk component staan wat hints en content die je nodig hebt.

### UI componenten

Maak minimaal 3 van onderstaande user interface componenten: 

- [Veelgestelde vragen](https://fdnd-task.github.io/progressive-enhancement/faq.html)
- [Switch control](https://fdnd-task.github.io/progressive-enhancement/switch.html)
- [Mobiel menu](https://fdnd-task.github.io/progressive-enhancement/menu.html)
- [Rating](https://fdnd-task.github.io/progressive-enhancement/rating.html)
- [Favorieten picker](https://fdnd-task.github.io/progressive-enhancement/pickers.html)
- [Carrousel](https://fdnd-task.github.io/progressive-enhancement/carrousel.html)
- [File upload met preview](https://fdnd-task.github.io/progressive-enhancement/file.html)
- [Tabbladen](https://fdnd-task.github.io/progressive-enhancement/tabs.html)

#### voor sprint 11

Voor sprint 11 is het het interessantst om componenten uit je ontwerp voor de leertaak in sprint 11 te gebruiken. 
Je mag ook componenten uit bovenstaande lijst gebruiken.
Het is een individuele opdracht - dus elke teamlid werkt eigen componenten uit (of maakt een substantieel andere uitwerking van dezelfde component).

Ieder teamlid werkt minimaal 2 componenten uit.

### Aanpak (per component)

1. Maak een _issue_ met als titel de UI component.
2. Beschrijf in de _description_ eigen woorden wat dit component is, en wat de _core functionaliteit_ is. Gebruik de demo video om een idee te krijgen.
3. Schets het component en de interactie 
4. Laag 1: Onderzoek welke HTML je voor de _core functionaliteit_ nodig hebt, maak hiervan een breakdownschets, en codeer je HTML (gebruik de hints en content in de code die klaarstaat, MDN en CanIUse).
5. Test deze HTML versie op verschillende browsers en devices.
6. Laag 2: Voeg CSS toe, aan de hand van MDN, CanIUse en `@supports`.
7. Test deze “enhanced” versie op verschillende browsers en devices.
8. Laag 3 en verder: Voeg eventueel meer CSS & JS toe, aan de hand van MDN, CanIUse, `@supports` en feature detection.
9. Test deze “enhanced” versie(s) op verschillende browsers en devices.
10. Documenteer je experiment stap voor stap in het _issue_.

#### voor sprint 11
11. In sprint 11 is het doel pleasurable (ga lekker los).
12. Documenteer je experiment.

### Bronnen bouwfase

* [Can I Use...](https://caniuse.com/)
* [Styling & Customizing File Inputs the Smart Way](https://tympanus.net/codrops/2015/09/15/styling-customizing-file-inputs-smart-way/)
* [It All Starts with a Humble `<textarea>`](https://24ways.org/2019/it-all-starts-with-a-humble-textarea/)
* [Making a Better Custom Select Element](https://24ways.org/2019/making-a-better-custom-select-element/)
* [Progressive Enhancement and Data Visualizations](https://css-tricks.com/progressive-enhancement-data-visualizations/)



## Criteria

Deze opdracht is done als:

- [ ] Je hebt minstens drie user interface componente uitgewerkt en gedocumenteerd in een _issue_
- [ ] De breakdownschetsen zijn opgenomen in het issue
- [ ] Bij elke schets staat een korte uitleg van de code
- [ ] Je werk is te bekijken via GitHub Pages
