# Bachelorarbeit
Dieses Repository enthält verwendete Dateien aus meiner Bachelorarbeit.

## Erläuterung
Invoke-Mimikatz.ps1 führt Mimikatz Version 2.0 vollständig im RAM aus ohne Spuren auf der Festplatte zu hinterlassen. Dieses Skript wird von einer Vielzahl an Antivirensoftwares als unerwünschte Software erkannt.

![grafik](https://user-images.githubusercontent.com/18469848/115963619-63648280-a520-11eb-86ea-8ea521af9de7.png)
https://www.virustotal.com/gui/file/a4667f4b2dc64288c5f2fe22c1bcacaa6d2ebf28c9e5fb7824ec2a78b9ebc46b/detection

Um eine Entdeckung durch Antivirenengines zu entgehen, wurde auf Xencrypt (https://github.com/the-xentropy/xencrypt) zurückgegriffen. Die veränderte Mimikatz Version, Invoke-Mimikatz-Obfuscated.ps1, wird weitaus weniger erkannt.

![grafik](https://user-images.githubusercontent.com/18469848/115963510-e507e080-a51f-11eb-9f03-36b6144424e5.png)
https://www.virustotal.com/gui/file/82358d6cda9c9157b2f333bf7a8aa229ab626ddece0b57dbb42880278c4fa682/detection

Bei der revil1.ps1 Datei handelt es sich um ein Sample der REvil (Sodinokbi) Ransomware. 

### Ich übernehme keine Haftung für Schäden. Führen Sie die Dateien nur in einer virtuellen Umgebung aus!
