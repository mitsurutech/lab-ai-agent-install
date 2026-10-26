# Coding-Agent selbst installieren, Lab: opencode einrichten und mit einem Modell verbinden, an einem kleinen Projekt mit Tests

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [日本語](README.ja.md) | [Deutsch](README.de.md)

[![check](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml/badge.svg)](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml)

Ein fertiges Lab für den Unterricht von der [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning), auf der Schulen, Colleges und Hochschulen jedem Lernenden eigene Datenbanken, Container und ein Terminal im Browser bereitstellen. Es ist ein Lab, in dem noch nichts installiert ist: Sie installieren opencode, einen quelloffenen KI-Agenten, sagen ihm, wo sein Modell liegt, und nutzen ihn dann an einem kleinen Projekt mit Tests.

## Auf der Plattform nutzen

**Dieses Lab läuft nur auf der Plattform.** Sein Agent erreicht ein Modell und einen Paket-Proxy, die die Plattform neben der Kopie jedes Lernenden bereitstellt, deshalb startet `compose.yaml` nicht auf einem eigenen Rechner. Jede lernende Person erhält eine private Kopie ohne Zugang zum Internet.

**Zum Ausprobieren:** Öffnen Sie die [Container-Seite](https://mitsurutech.co.uk/container), suchen Sie dieses Lab unter **Sample labs** und klicken Sie auf Start. Dafür ist ein kostenloses Konto nötig.

**Als Aufgabe für eine Klasse stellen:**

1. Legen Sie in Ihrem Modul eine Aufgabe vom Typ **Lab** an und wählen Sie **In a GitHub repository**.
2. Geben Sie `https://github.com/mitsurutech/lab-ai-agent-install` mit dem Branch `main` an. Die Compose-Datei ist die Standarddatei, `compose.yaml`. Forken Sie das Repository zuerst, wenn Sie etwas ändern möchten.
3. Veröffentlichen Sie die Aufgabe. Die Kopie jeder lernenden Person beginnt mit dem Commit, den Sie veröffentlicht haben, eine spätere Änderung hier verändert also kein bereits gestelltes Lab.

Die [Seite zu diesem Lab](https://mitsurutech.co.uk/help/lab-ai-agent-install) im Hilfehandbuch und die [Anleitung zu Container-Labs](https://mitsurutech.co.uk/help/labs) beantworten die übrigen Fragen. Die passende Grundlagenlektion heißt **AI Coding Agent Basics**. Noch kein Konto für Ihre Einrichtung? [Das erste Jahr ist kostenlos](https://mitsurutech.co.uk/pricing) für bis zu 50 Lernende, und die [Registrierung](https://mitsurutech.co.uk/signup) braucht nur eine E-Mail-Adresse.

## Was Sie wissen sollten

Der Kommentar am Anfang von `compose.yaml` beschreibt, wie das Lab gestartet wird und was der Agent darf. Der Agent fragt nach, bevor er eine Datei ändert oder einen Befehl ausführt: Lesen Sie, was er vorhat, und antworten Sie nur mit Ja, wenn Sie es verstehen. **Nichts wird gespeichert**: Beim Beenden des Labs gehen alle Dateien verloren, Lernende laden ihre Arbeit also herunter, bevor sie das Lab beenden. Was ein Assistent antwortet, unterscheidet sich von Lauf zu Lauf, deshalb wird hier kein Ergebnis zugesichert.

## Lizenz

Dieses Werk steht unter der Lizenz [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Sie dürfen es für Lernen und Lehren weitergeben und bearbeiten, wenn Sie Mitsuru Technologies Ltd nennen, es nicht kommerziell nutzen und alles, was Sie daraus machen, unter derselben Lizenz weitergeben. Der vollständige Text steht in der Datei `LICENSE`.

## Über uns

Entwickelt von [Mitsuru Technologies](https://mitsurutech.co.uk) für die [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning): Python, Java, Go, Node, SQL und Linux im Browser für Schulen und Colleges, mit Container-Labs, aus GitHub bereitgestellten Web-Apps und Quizzen, die sich selbst auswerten. Code ohne Konto ausprobieren können Sie im [Playground](https://mitsurutech.co.uk/playground).

Weitere Labs vom selben Ort: [lab-ai-agent](https://github.com/mitsurutech/lab-ai-agent), [lab-quantum-sim](https://github.com/mitsurutech/lab-quantum-sim), [lab-jupyter-data](https://github.com/mitsurutech/lab-jupyter-data) und [lab-git-gitea](https://github.com/mitsurutech/lab-git-gitea).
