# Brandberry

Brandberry ist eine Agentur, die sich auf die Entwicklung und dem Design von Webanwendungen spezialisiert hat. Clienten werden von der ersten Idee bis zur fertigen Lösung begleitet. Bei unserer Arbeit achten wir darauf, dass der Client so schnell wie möglich launchen kann - dies erreichen wir durch einen ausgeklügelten Workflow, bei dem wir auf Effizienz und Qualität achten.

### Was macht den Workflow so Effizient?

#### Kommunikation

Der Workflow ist so konzipiert, dass wir auf Overengineering verzichten - nach dem Motto "Simple is best". Der Client hat die Möglichkeit, sobald seine Zahlung hinterlegt ist, auf ein Ticket-System zuzugreifen. In diesem System hat er die Möglichkeit, seine Anforderungen an sein Projekt zu beschreiben. 
Anschließend taucht dieses Ticket im Admin-Dashboard auf und wird von uns bearbeitet. 

Mit dem Ticket-System wollen wir die Kommunikation zwischen uns und dem Client auf das notwendigste reduzieren. Meetings erfordern in erster Linie einen Zeitaufwand, durch das Ticket-System schmälern wir diesen Zeitaufwand, sodass wir und der Client sich auf das Wesentliche konzentrieren können - die Arbeit. 

Side-Note: Das soll natürlich nicht heißen, dass wir kein initiales Meeting wollen. Am Ende vertraut uns der Kunde sein Geld und zukünftigen Webauftritt an. Natürlich werden wir, wenn der Wunsch besteht, ein Initial-Meeting organisieren, um Anforderungen zu diskutieren und zu klären. 

#### Design- und Code-Bibliotheken

Wir haben uns zur Aufgabe gemacht, ein Design- und Code-Bibliotheken-System zu entwickeln. Dazu gehört natürlich, dass wir uns Inspiration suchen - die finden wir auf z.B.: 

- [Dribbble](https://dribbble.com/)
- [Behance](https://www.behance.net/)
- [Mobbin](https://www.pinterest.com/)
- [Awwwards](https://www.awwwards.com/)

In unserer Design- und Code-Bibliothek befinden sich sauber ausgearbeitete Komponenten und Sektionen, die wiederverwendet werden können, um somit, schnell und effizient, eine qualitativ hochwertige Anwendung zu entwickeln.

Diese Bibliotheken werden über die Zeit wachsen und werden mehr Vielfalt und Kombinationsmöglichkeiten bieten.

#### Geschwindigkeit

Durch die oben genannten Herangehensweisen haben wir die Möglichkeit, schneller in die Feedback-Schleife zu gelangen, dadurch kann der Client schneller Ergebnisse sehen und wir können besser und schneller auf die Wünsche eingehen.

Außerdem beinhaltet der Worklflow Automatismen, die es uns ermöglicht, schell und einfach Schritte auszuführen, die sich von Projekt zu Projekt wiederholen - dazu gehören Schritte wie: 

- Projekt erstellen
- Abhängigkeiten installieren oder aktualisieren
- Infrastruktur einrichten
- Anwendung deployen

Der Automatismus wird derzeit durch ein Python-Script realisiert. Dieses Script erstellt eine grundlegende Projektstruktur, füllt Vorlagen mit dynamisch angegebenen Werten und integriert diese in das Projekt. Danach wird das Projekt-Repository auf GitHub erstellt und mit dem Projekt auf dem Hostsystem synchronisiert. Anschließend wird das Projekt mittels eines Workflows gepusht, was das Deployment über Terraform und Ansible initiiert.

### Warum Code und nicht No-Code?

#### Flexibilität

Dadurch, dass die Code-Basis in unserer Hand liegt, ist es uns möglich maßgeschneiderte Lösungen zu entwickeln, sollten unsere Bibliotheken mal ein Szenario nicht abdecken. Außerdem, sollte der Client nur kleine Änderungen an der Anwendung vornehmen wollen, ist es einfach diese anzupassen.

#### Skalierbarkeit 

Anwendungen können durch die Verwendung von CICD-Pipelines einfach skalierbar gemacht werden. Sollte sich auch hier Anforderungen ändern, sind diese genauso flexibel anzupassen.

#### Performance 

Die richtige Auswahl an Technologien kann dazu führen, dass eine Anwendung sehr performant ist. Ein Zuwachs in der Performanz kann unter anderem dadurch erzeugt werden, dass die Anwendung größtenteils serverseitig zur Verfügung gestellt wird und nur die Anwendungslogik, die die Interaktion mit dem Benutzer erfordert, auf Seiten des Client ausgeführt wird.

## Umsetzung

Bei der Umsetzung von Brandberry ist zu beachten, dass es drei Teilbereiche gibt:

- Planung
- Design
- Entwicklung

### Planung

Hier ist zu erwähnen, dass der Worklfow, den wir oben erklärt haben, bei der Planung zum tragen kam, bzw. überhaupt erst durch den Entstehungsprozess von Brandberry entstanden ist.
Wichtig ist, dass während der Team-Meetings schnell Entscheidungen getroffen werden und die Umsetzung daraufhin so schnell wie möglich stattfindet. Das ermöglicht uns auch hier eine schnelle Validierung der Anforderungen und ob wir auf dem richtigen Weg sind oder Anpassungen vornehmen müssen.

Verwendete Tools:

- [Figma](https://www.figma.com/)
- [Miro](https://miro.com/)
- [Google Chat](https://chat.google.com/)
- [Google Kalender](https://calendar.google.com/)
- [Google Meet](https://meet.google.com/)

### Design

Das Design spielt bei jedem Produkt eine tragende Rolle. Die Wahl der richtigen Farben, Schriftarten, Abstände und Anordnungen sind dafür zuständig, dass der Benutzer sich intuitiv durch die Anwendung bewegen kann und das Erlebnis so gut wie möglich optimiert ist.

In der Regel wird ein Design durch eine primäre, eine sekundäre, eine helle und dunkle Farbe, die dazugehörigen Kontraste, ein bis zwei Schriftarten, Größen und Abstände definiert.

#### Erläuterung:

Das Layout der Website ist bewusst minimalistisch gehalten, um die Aufmerksamkeit auf die Inhalte zu lenken. Durch eine klare Struktur und eine intuitive Navigation wird ein angenehmes Benutzererlebnis gewährleistet. Die Anordnung der Elemente ist sorgfältig durchdacht und sorgt für einen harmonischen Gesamteindruck.

Die Wahl der Schriftarten unterstreicht den modernen Charakter der Website. Sora als Headline-Schriftart verleiht den Überschriften eine starke Präsenz und sorgt für eine klare Hierarchie. Figtree als Paragraphenschriftart sorgt für eine angenehme Lesbarkeit und einen fließenden Textfluss. Die Kombination dieser beiden Schriftarten schafft eine ausgewogene und ästhetisch ansprechende Typografie.

Die Farbpalette der Website ist geprägt von den kräftigen Tönen Dark Amouranth (#9C0843) und Royal Purple (#1C1469). Diese Farben werden sowohl einzeln als als auch in harmonischen Verläufen eingesetzt, um eine dynamische und lebendige Atmosphäre zu schaffen. Durch die Anwendung der 60-30-10-Regel haben wir sichergestellt, dass die Farben in einem ausgewogenen Verhältnis zueinander stehen und die Inhalte optimal zur Geltung bringen. Die Verwendung dieser Farben im Dark Mode erzeugt einen modernen und stilvollen Kontrast.

Der Dark Mode ist nicht nur ein aktueller Trend, sondern bietet auch praktische Vorteile. Er schont die Augen, reduziert die Belastung durch blaues Licht und schafft eine angenehme Atmosphäre, insbesondere bei längerer Nutzung. Die dunkle Farbgebung unterstreicht die Eleganz des Designs und lässt die Inhalte besonders gut zur Geltung kommen.

#### Verwendete Tools: 

- [Figma](https://www.figma.com/)

### Entwicklung

Die Entwicklung ist am Ende der Kleber, der die Planung und das Design verbindet, um ein qualtitativ hochwertiges und interaktives Produkt zu erzeugen. 
Durch das Verwenden der richtigen Technologien und Techniken entstehen hier die Vorteile, die wir oben erläutert haben:

- Skalierbarkeit
- Flexibilität
- Performanz

#### Verwendete Technologien:

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Next-Auth](https://next-auth.js.org/)
- [Zod](https://zod.dev/)

#### Warum Next.js?

Next.js bietet uns viele Vorteile, der wichtigste ist das Server-Side-Rendering (SSR). Dadurch können performante Anwendungen mit geringen Ladezeiten entwickelt werden. Durch das SSR ergibt sich auch ein weiterer Vorteil: Die Anwendung wird, bevor sie von einem Clienten angefordert wird, zur Verfügung gestellt und kann somit von Search-Engine-Crawler erreicht werden. Das bedeutet, dass wir einen größeren Hebel haben, wenn es um SEO-Optimierung geht.

Darüber hinaus ist die Bereitstellung auf der Server-Side eine gute Sicherheitsmaßnahme. Eine Anwendung erfordert grundsätzlich auch die Interaktion des Client, diese Interaktion wird auf der Client-Side durchgeführt, kann aber an Server-Actions gebunden sein und vermeidet somit, dass sensible Informationen an den Client geschickt werden.

#### Warum TypeScript?

Grundlegend lässt sich sagen, dass TypeScript eine gute Wahl ist, wenn eine Anwendung entwickelt werden soll, die aus robusten und sicheren Code besteht. 
Die Typensicherheit ermöglicht uns schneller Fehler zu erkennen und verbessert somit die Qualität der Anwendung.

#### Warum Prisma?

Prisma ist ein ORM (Object-Relational-Mapping) Tool, das uns dabei hilft, mit unserer Datenbank zu kommunizieren.
Der Hauptgrund, warum wir Prisma verwenden, ist, dass uns hier eine Typensicherheit geboten wird und wie in TypeScript erwähnt, es die Qulität der Anwendung verbessert.

Außerdem können wir Prisma innerhalb von Server-Komponenten verwenden und vermeiden somit die Verwendung von einem Hook, was wiederum dazu führen würde, dass eine Komponente auf der Client-Side gerendert werden muss. Das könnte u.a. mit Entrypoint-Dateien gelöst werden, würde aber an manchen Stellen die Komplexität der Anwendung erhöhen.

Hierbei ist aber auch wichtig zu erwähnen, dass sich ein Nachteil abbildet:
Sollten Anfragen an die Datenbank eine sehr komplexe Logik haben, kann es zu einer geringeren Performance kommen.

#### Warum PostgreSQL?

Wir haben uns für PostgreSQL entschieden, weil es die umfangreichste Unterstützung für die Funktionen bietet, die wir mit Prisma nutzen möchten. PostgreSQL ist nicht nur kostenfrei, sondern kann auch in Containern gehostet werden, was die Skalierbarkeit unseres Backends erleichtert.

Zusätzlich haben wir uns für einen PaaS-Anbieter entschieden, der sowohl Next.js als auch PostgreSQL unterstützt, nämlich Vercel. Dies ermöglicht es uns, die Entwicklung zu beschleunigen, indem wir uns auf den Code konzentrieren können, ohne eine eigene Infrastruktur aufbauen zu müssen oder uns um eine zusätzliche Pipeline-Logik kümmern zu müssen.

#### Warum Next-Auth und Zod?

Next-Auth ermöglicht uns die nahtlose Authentifizierung unserer Nutzer. Während wir uns in die Authentifizierungslogik eingearbeitet haben, wurde klar, dass wir sowohl Credentials als auch OAuth verwenden können – in unserem Fall nutzen wir Google und Credentials.

Für die Authentifizierungsstrategie haben wir uns für JWT entschieden, um die Datenbank zu entlasten. Nutzer- und Sitzungsdaten werden in einem Token gespeichert, der in einem Cookie abgelegt wird. Dies erlaubt es uns, dynamische Routen zu reduzieren, die Routenabstraktion zu vereinfachen und sensible Nutzerdaten aus den URLs fernzuhalten.

Zod ist ein Tool zur Schema-Validierung, das uns dabei hilft, die über Formulare erhaltenen Daten zu überprüfen. Wenn die Daten nicht den in Zod definierten Anforderungen entsprechen, wird ein Fehler generiert, der dynamisch auf der Client-Seite angezeigt werden kann.
