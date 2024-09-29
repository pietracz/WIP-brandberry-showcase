# Brandberry Showcase

Brandberry ist ein Webdesign Studio, welches gebrauch vom "Productized Service" macht - eine Abomodel für eine Dienstleistung.

## Einleitung

Die Website ist ein Multipager, dessen Design und Planung in Figma und Miro erfolgt ist. Auf Code-Ebene haben wir uns im Frontend für Next.js mit TypeScript und Styled Components entschieden, im Backend für Node.js und MySQL.

Das Design ist weiterhin ein fließender Prozess und spielt bei der Gestaltung des Produktes - der Dienstleistung - eine tragende Rolle. Bei dem Design achten wir darauf, dass wir uns so gut es geht an die 60-30-10-Verteilung halten, um eine angenehme Wahrnehmung zu gewährleisten.

Grundsätzlich ist das Styling über CSS und/oder Tailwind möglich, wir wollen aber dem Ansatz des "Atomic Design" und des "Clean Code" folgen, was natürlich React-Komponenten entgegenkommt.

Aus diesem Grund definieren wir lediglich Variablen über eine globals.css und erstellen den Rest des Stylings in der Komponente selbst.

Im Backend verfolgen wir einen ähnlichen Ansatz. Next.js macht es grundsätzlich möglich, dass API-Calls über die Anwendung selber gemacht werden können, was aber die Skalierbarkeit erschwert.

Darum setzen wir hier auf die Modularisierung, trennen das Frontend vom Backend, wodurch die REST-API über eine Node.js Instanz stattfindet und Anfragen von der Next.js App an die MySQL-Datenbank weiterleitet und verarbeitet.

## Table of contents

[Homepage](https://github.com/pietracz/brandberry-showcase/tree/main/Homepage)<br>
[About](https://github.com/pietracz/brandberry-showcase/tree/main/About)<br>
[Services](https://github.com/pietracz/brandberry-showcase/tree/main/Services)<br>
[Contact](https://github.com/pietracz/brandberry-showcase/tree/main/Contact)<br>
