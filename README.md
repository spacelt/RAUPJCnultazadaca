# JMBAG
0036475359
# Pitanje 1:
Stvorene su dvije datoteke od kojih je jedna koju koristi VS, a jedna koja nam
je važna za rad našeg programa, a to je asemblij ClassLibrary1.dll.
Dogodi se iznimka i program se ruši. Zato što CLR pri prevođenju konzole u
IL gleda osvisnosti i vidi da mu treba ClassLibrary1.dll bez koje ne može
funkcionirati.
Šaljem: KonzolaAplikacija + ClassLibrary1.dll
# Pitanje 2:
Koristila je staru verziju class library asemblija zato što nismo
preveli naš novi C# kod u IL te time dobili novi .dll asemblij.
# Pitanje 3: 
Pero: Hello World
# Pitanje 4:
Sada imamo i PeroClassLibrary.dll asemblij u direktoriju.
# Pitanje 5:
I dalje radi zato što se identican asemblij nalazi u bin/debug direktoriju konzola
aplikacije.
Traži se upravo u tom bin/debug direktoriju konzola aplikacije.
# Pitanje 6:
Pri build procesu opet je dohvacen NodaTime paket. Opet ga imamo
u packages direktoriju.
