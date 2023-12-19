# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation

`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

## erstellen von einen neuen element 2.3.1
 
`PUT /newitem/{itemdId}`: gibt neues element in die liste.
**Parameter**: `itemId` - Einzigartige Id des Elements

## 2.3.2 Löschen von Elementen
`DELETE /allitems`: Löscht alle ELEMENTE

`DELETE /itembyid/{itemdId}`: Löscht das ausggewählte ELEMENT.
**Parameter**: `itemId` - Einzigartige Id des Elements

## 2.3.3 Aktualisieren von daten 
`POST /allitems`: aktualisert alle ELEMENTE

`POST /itembyid/{itemdId}`: Aktualisiert nur das ausgewählte Element.
**Parameter**: `itemId` - Einzigartige Id des Elements

