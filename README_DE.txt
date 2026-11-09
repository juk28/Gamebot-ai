GAMEBOT IA – Android-Projekt (Prototyp 0.1)

Was enthalten ist:
- Startbildschirm mit den zwei gewünschten Modi:
  1. Mahjong Royale
  2. Block Puzzle
- Android-Bedienungshilfe als technische Grundlage für spätere Bildschirm-Eingaben.
- Einrichtungsschaltfläche, die die Android-Einstellungen für Bedienungshilfen öffnet.

WICHTIG – aktueller Entwicklungsstand:
Dies ist noch KEIN fertiger Auto-Spieler. Die Bilderkennung, Mahjong-Paar-Suche,
Block-Puzzle-Planung und die automatische Auswahl der Spielzüge sind noch nicht
implementiert. Die beiden Screenshots zeigen unterschiedliche Spiel-Layouts;
die Erkennung muss deshalb dynamisch und pro Spieltyp entwickelt und getestet werden.

So öffnest du das Projekt:
1. Auf einem Computer Android Studio installieren.
2. Android Studio > Open auswählen und den Ordner GamebotIA_Android öffnen.
3. Gradle-Synchronisierung abwarten.
4. Ein Android-Handy per USB verbinden oder einen Emulator starten.
5. Run drücken.

Die Bedienungshilfe darf nur aktiviert werden, wenn du Gamebot IA vertraust.
Sie kann – nach entsprechender Implementierung und Freigabe – Bildschirm-Inhalte
lesen und Eingaben ausführen. Starte Automatisierung nur bei Spielen, bei denen
die Regeln des Spiels dies erlauben. Beachte außerdem die Nutzungsbedingungen
des jeweiligen Spiels.

Nächster Entwicklungsschritt:
- Mahjong: sichtbare, freie Steine erkennen, identische Paare finden und
  Zugmöglichkeiten berücksichtigen.
- Block Puzzle: Rastergröße und belegte Felder erkennen, die drei Formen
  auslesen und eine Platzierung planen, die Reihen/Spalten löscht.
