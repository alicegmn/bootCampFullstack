# bootCampFullstack

Alice Eriksson

Praktisk Examination – FJSX24 Boot Camp för Fullstack utvecklare

Instruktioner för hur man öppnar och navigerar på webbplatsen:
1. Gå till repot på GitHub: https://github.com/alicegmn/bootCampFullstack
2. Klicka på "Open with GitHub Desktop" för att ladda ner filerna och öppna upp dem  i GitHub desktop lokalt på din dator.
3. Klicka sedan på Open with VS code för att öppna projektet i VS code.
(4. Det finns också andra sätt. Som att öppna det direkt genom terminalen på din dator eller i VS code. Vill du bara titta på sidan kan du ladda ner Zip-filen, packa upp den och öppna index.html i din webbläsare.)

Kortfattad teknisk beskrivning av hur jag uppfyller kraven.
- Semantiska HTML-element används genomgående, t.ex. <header>, <nav>, <main>, <section>, <article>, och <footer>. Men också <form>, <address>, <button>, <img> och så vidare.
- Webbplatsen innehåller en hemsida (index.html) och flera undersidor (vinskolan.html, vinbarer.html, events.html, logga-in.html). Dock är endast index.html och vinbarer.html "klara" fullständiga sidor.
- En konsekvent navigationsmeny som är responsiv med hjälp av media queries med hambrugermeny på stora skärmar, finns med i headern på alla sidor.
– Responsiv design med Flexbox i nav-bar, footer och formuläret på Logga in sidan. Grid används för t.ex vinbarer-container och .vinskolan-container. Samt hela layouten på sidan vinbarer.html.
– Media queries används för att anpassa layouten för olika skärmstorlekar.
– Jag har försökr organisera min CSS i en logisk struktur från toppen till botten och media queries längst ner, och beskrivande klassnamn + id:n och mobile first.
– Webbplatsen är responsiv för mobila enheter, surfplattor och datorskärmar genom användning av media queries, flex, grid och clamp.
– Clamp används för att hantera textstorlekar, t.ex. font-size: clamp(14px, 2vw, 24px); för paragrafer.
– Alt-attribut används för bilder.
– Korrekt rubrikstruktur implementeras med <h1> till <h3>.
– Färgkontrast mellan text och bakgrund är tillräcklig.
– Beskrivande länkar och knappar används, t.ex. aria-label för sociala medier-ikoner.
– Chrome DevTools har använts för att testa responsivitet och debugga HTML/CSS-problem.
– Wave och/eller Lighthouse har använts för att förbättra tillgängligheten, men detta framgår inte direkt av koden.
– GitHub repo har använts för versionshantering, med en developer branch och en main branch som mergade in till när jag var klar med sidan.