# Git Shell Hausaufgabe

Dieses Repository enthält ein kleines Bash-Skript für einfache IT-Support-Aufgaben.

Geübte Git-Themen:
- git add
- git commit
- git push
- git branch
- git checkout
- git merge

Theoriefragen:

1.	Was ist ein Merge-Konflikt? Entsteht wenn Git zwei Änderungen nicht automatisch zusammenführen kann, z.B. wenn zwei Personen dieselbe Zeile in einer Datei unterschiedlich geändert haben.
2.	Warum entsteht ein Merge-Konflikt meistens dann, wenn zwei Branches dieselbe Stelle in derselben Datei verändert haben? Weil Git nicht weiß welches übernommen werden soll.
3.	Warum haben Sie in dieser Aufgabe keinen Merge-Konflikt bekommen? Weil wir in verschiedenen Branches gearbeitet haben. Es wurden neue Features getrennt voneinander erstellt.
4.	Was zeigt Git in einer Datei an, wenn ein Merge-Konflikt entsteht? Git markiert die betroffenen Stellen direkt in der Datei. Dabei sieht man zum Beispiel <<<<<<<, ======= und >>>>>>>. Damit erkennt man, welche Änderungen von den beiden Branches kommen.
5.	Welche Schritte muss man grundsätzlich durchführen, um einen Merge-Konflikt sauber zu lösen? Man öffnet die betroffene Datei und schaut sich beide Änderungen an und entscheidet welche übernommen werden soll oder kombiniert es. Anschließen entfernt man die Konfliktmarkierung, speichert + git add + git commit
6.	Warum sollte man nach dem Lösen eines Merge-Konflikts das Programm oder Skript noch einmal testen? Um Funktionalität zu sichern. Da beim zusammenführen Fehler entstanden sein können.
7.	Was macht git merge? Übernimmt die Änderungen eines anderen Branches in den aktuellen Branch. Beispiel: Fertiges Feature Branch in eine main Branch.
8.	Was macht git rebase?  Änderungen der eigenen Branch auf den Zustand eines aktuelleren Branches. Dadurch werden eigene Commits auf eine neue Grundlage gesetzt. 
9.	Was ist der wichtigste Unterschied zwischen merge und rebase? Merge führt zusammen und die bisherige Branch bleibt erhalten. Bei rebase werden die eigenen Commits neu angeordnet für eine geradere Historie.
10.	Warum bleibt bei merge oft besser sichtbar, wann ein Branch zusammengeführt wurde? Weil Git einen zusätzlichen Merge-Commit erstellt. Dadurch erkennt man wann und welche Branches zusammengeführt wurden.
11.	Warum kann rebase die Git-Historie sauberer aussehen lassen? Weil Commits hintereinander angeordnet werden und weniger zusätzlice Merge-Commits entstehen. 
12.	Warum sollte man mit rebase vorsichtig sein, wenn ein Branch bereits mit anderen geteilt wurde? Weil rebase die Commit-Historie verändert. Wenn andere Personen bereits mit diesem Branch arbeitenkann es zu Problemen kommen, weil ihre lokale Historie nicht mehr zur neuen passt.
13.	Wann würden Sie eher merge verwenden? Wenn mehrere Personen gemeinsam an einem Projekt arbeiten und Ihre Änderungen zusammenführen möchten. 
14.	Wann könnte rebase sinnvoll sein?Wenn ich meinen eigenen Branch auf den neuesten Stand bringen möchte bevor ich meine Änderungen übernehme. Dadurch bleibt die Git-Historie übersichtlicher

