# Brandberry Showcase

Brandberry ist ein fiktives Startup, welches Unternehmen maßgeschneiderte Webdesign-Lösungen bietet.
Clienten werden ab der ersten Idee bis zur fertigen Website begleitet. Der Workflow beinhaltet einen agilen Ansatz und einen transparenten Projektverlauf, welcher eine effiziente Zusammenarbeit garantiert.
Darüber hinaus ist der Workflow so konzipiert, dass das erste Ergebnis - abhängig vom Umfang der Anfrage - nach 48 Stunden ausgeliefert wird.

Diese Website und künftige Anfragen werden unter Verwendung folgender Technologien erstellt:

Frontend:

- React(Next.js+TypeScript)
- CSS Modules (Next.js Feature)
- Lenis

Backend:

- Node.js(Express, mysql2)
- MySQL

## Projekt-Erläuterung

Die Website ist ein Multipager, dessen Design und Planung in Figma und Miro erfolgt ist. Auf Code-Ebene haben wir uns im Frontend für Next.js mit TypeScript entschieden, im Backend für Node.js und MySQL.

Das Design ist weiterhin ein fließender Prozess und spielt bei der Vermarktung des Produktes - der Dienstleistung - eine tragende Rolle. Es wird darauf geachtet, dass sich das Design an verschiedene Bildschirmgrößen anpasst und somit auf allen Geräten ein optimales Erlebnis bietet. Wir haben uns bei der Gestaltung besonders auf die Usability fokussiert, um eine optimale Nutzererfahrung zu gewährleisten. Das Design ist nicht nur schön, sondern auch funktional und unterstützt den Nutzer bei jeder Interaktion.

Grundsätzlich ist das Styling über viele Wege möglich, wir wollen mit unserem Ansatz "Atomic Design" und "Clean Code" folgen.
Aus diesem Grund definieren wir lediglich Variablen über eine globals.css und erstellen den Rest des Stylings in einem, zur Komponente, dazugehörigen Modul.

Im Backend verfolgen wir einen ähnlichen Ansatz. Next.js macht es grundsätzlich möglich, dass API-Calls über die Anwendung selber gemacht werden können, was aber die Skalierbarkeit erschwert.
Darum setzen wir hier auf die Modularisierung, trennen das Frontend vom Backend, wodurch die REST-API über eine Node.js Instanz stattfindet und Anfragen von der Next.js App an die MySQL-Datenbank weiterleitet und verarbeitet.

## Design

Das Layout der Website ist bewusst minimalistisch gehalten, um die Aufmerksamkeit auf die Inhalte zu lenken. Durch eine klare Struktur und eine intuitive Navigation wird ein angenehmes Benutzererlebnis gewährleistet. Die Anordnung der Elemente ist sorgfältig durchdacht und sorgt für einen harmonischen Gesamteindruck.

Die Wahl der Schriftarten unterstreicht den modernen Charakter der Website. Sora als Headline-Schriftart verleiht den Überschriften eine starke Präsenz und sorgt für eine klare Hierarchie. Figtree als Paragraphenschriftart sorgt für eine angenehme Lesbarkeit und einen fließenden Textfluss. Die Kombination dieser beiden Schriftarten schafft eine ausgewogene und ästhetisch ansprechende Typografie.

Die Farbpalette der Website ist geprägt von den kräftigen Tönen Dark Amouranth (#9C0843) und Royal Purple (#1C1469). Diese Farben werden sowohl einzeln als als auch in harmonischen Verläufen eingesetzt, um eine dynamische und lebendige Atmosphäre zu schaffen. Durch die Anwendung der 60-30-10-Regel haben wir sichergestellt, dass die Farben in einem ausgewogenen Verhältnis zueinander stehen und die Inhalte optimal zur Geltung bringen. Die Verwendung dieser Farben im Dark Mode erzeugt einen modernen und stilvollen Kontrast.

Der Dark Mode ist nicht nur ein aktueller Trend, sondern bietet auch praktische Vorteile. Er schont die Augen, reduziert die Belastung durch blaues Licht und schafft eine angenehme Atmosphäre, insbesondere bei längerer Nutzung. Die dunkle Farbgebung unterstreicht die Eleganz des Designs und lässt die Inhalte besonders gut zur Geltung kommen.

## Ordnerstruktur

Hierbei handelt es sich um eine vorläufige Ordnerstruktur.

```
Brandberry
+---.next
\---node_modules
|
+---public
\---src
|    \---app
|        |   favicon.ico
|        |   globals.css     /* Hier werden alle Variablen definiert, die später in den Komponenten verwendet werden */
|        |   layout.tsx     /* Die layout.tsx und die page.tsx dienen lediglich einem redirect, um das Hauptverzeichnis sauber zu halten */
|        |   page.tsx
|        |
|        +---about
|        |   |   layout.tsx     /* Jede standard Route beinhaltet eine layout.tsx, um die parallelen Routen einzureihen*/
|        |   |
|        |   +---@hero
|        |   |       page.tsx     /* Jede parallele Route beinhaltet eine page.tsx */
|        |   |
|        |   |
|        |   +---@skills
|        |   |
|        |   +---@statement
|        |   |
|        |   \---@team
|        |
|        +---home
|        |
|        +---services
|        |
|        +---_components     /* Hier werden alle Komponenten definiert */
|        |
|        \---_lib     /* Dieser Ordner beinhaltet Skripte, um z.B. styled-components nutzbar zu machen */
|
|   .eslintrc.json
|   .gitignore
|   next-env.d.ts
|   next.config.mjs
|   package-lock.json
|   package.json
|   README.md
|   tsconfig.json
```

## Potenzielle Server-Struktur auf AWS

<img src="./assets/server-structure.png">
