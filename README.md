# Pitanje 1:
Kad smo dodali class library kao referencu u Bin/Debugu se pojavila datoteka s .dll ekstenzijom. Ukoliko istu maknemo iz projekta program više neće ispravno raditi već će baciti FileNotFoundException jer ne može pronaći sve svoje reference. Da bi aplikacija bila uporabljiva, treba imati datoteke: KonzolnaAplikacija.exe i ClassLibrary1.dll.

# Pitanje 2:
Nakon što se string izmijeni te se ponovo pokrene konzolna aplikacija, aplikacija će koristiti novu verziju. Razlog tomu je taj što prilikom pokretanja builda konzolne aplikacije se pokreće build i class library projekta.

# Pitanje 3:
Build proces je završio sasvim normalno, a u packages direktoriju se ponovo našao NodaTime direktorij.