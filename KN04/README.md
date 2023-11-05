# KN04
## A
### S3 Bucket
![bucket](https://github.com/duyminh-nguyen/TBZ_m346_mingu/assets/112622227/38e2e0ff-1dd1-450b-8af7-f1488deaf940)

### Image
![image](https://github.com/duyminh-nguyen/TBZ_m346_mingu/assets/112622227/f6d9de6b-68f8-483a-b64d-ce9f4b70c891)

## B
### image (info.php)
![imgB](https://github.com/duyminh-nguyen/TBZ_m346_mingu/assets/112622227/5f5d5e01-57e1-453e-9d8f-17210578ebb2)

## C
### 2nd Volume
![C](https://github.com/duyminh-nguyen/TBZ_m346_mingu/assets/112622227/3b8db2f4-642d-4679-ab7a-fbb21cc11109)

## D
| Name           	| Typ  	| Persistenz 	|
|----------------	|------	|------------	|
| EBS Root       	| Hot  	| Nein       	|
| EBS 2nd Volume 	| Hot  	| Ja         	|
| S3             	| Warm 	| Ja         	|

#### EBS Root:
"Hot" aufgrund des schnellen Zugriffs, da es für das Betriebssystem und Anwendungen verwendet wird.
"Nein" zur Persistenz, da Daten bei einem Neustart gelöscht werden, um den ursprünglichen Zustand wiederherzustellen.

#### EBS 2nd Volume:
"Hot" aufgrund des häufigen Datenzugriffs für Anwendungs- und Datenbankdaten.
"Ja" zur Persistenz, da Daten nach einem Neustart erhalten bleiben.

#### S3:
"Warm" aufgrund des geringeren Datenzugriffs, der oft für langfristige Datenspeicherung und Archivierung genutzt wird.
"Ja" zur Persistenz, da Daten in S3 dauerhaft erhalten bleiben.
