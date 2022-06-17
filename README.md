# Lab-1plus

Tema pentru primele laboratoare. Termene de predare: incepand cu saptamana 2. Urmariti cursul si anunturile de pe teams pentru urmatoarele termene si alte functionalitati care se vor cere pe parcurs.

### Pentru saptamana 2: 
Scrieti o aplicatie .NET REST API pentru time tracking. Vor fi suportate functionalitatile:

1. Adaugarea unei activitati: `Nume`, `Descriere`, `Data`, `Numar ore`.
2. Show all, Edit, Delete activitati (`CRUD`).
3. Filtrare activitati dupa `Data` si dupa `Numar ore`.

### Pentru saptamana 3:

Implementati o aplicatie Angular care va suporta operatiile de mai sus comunicand cu serverul de .NET REST API.

### Pentru saptamana 4:

1. Adaugati `SQL Server` aplicatiei de backend.
2. Adaugati Angular Material aplicatiei de frontend, pentru toate componentele.

### Pentru saptamana 5:

1. Adaugati inca un model in aplicatie: `SubActivity`: `Description`, `Numar ore`, `Dificultate`. Rulati migrarile necesare si creati functionalitatile CRUD pe controller / controllere.
2. Implementati pe Frontend CRUD folosind Reactive Forms. Vor exista pagina separate pentru: afisare activitati, adaugare activitate, detalii activitate, editare activitate. Subactivitatile sa apara in pagina de Details pentru o activitate.
3. **Bonus 2p**: in formularul de Adaugare activitate sa pot adauga, fara refresh, oricate subactivitati vreau. Ar trebui sa exista campuri pentru atributele unei subactivitati si butoane care genereaza sau sterg dinamic campurile formularului pentru subactivitati. Vezi finalul cursului 4 si codul aferent pentru exemple.


### Pentru saptamana 6:
1. Adaugati un model `User` cu campurile `Username`, `Password`, `IsConfirmed` si alte `3` campuri optionale. Parola trebuie sa fie hashed.
2. Implementati register si authenticate folosind JWT Tokens in endpoint-urile: `/api/token/register`, `api/token/confirm/<username>`, `api/token/login`.
3. Asociati fiecare `Activity` cu un `User`.

### Pentru saptamana 7:
1. Adaugati `Register` si `Login` pe frontend, folosind `HttpInterceptor`: autentificare doar cu username si password.
2. Daca tokenul expira sau daca userul nu este logat cand acceseaza o pagina, ar trebui redirectat catre pagina de login.
3. Daca userul face login dupa o redirectare, dupa login ar trebui redirectat catre pagina accesata initial.
