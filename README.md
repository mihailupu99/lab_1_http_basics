# Raport LL_01 (Lucrare de laborator №1. Bazele HTTP)

## Descriere

Studierea principiilor de bază ale protocolului HTTP.

## Condiții

### Sarcina nr. 1. Analiza cererilor HTTP

1. Accesați site-ul http://sandbox.usm.md/login.
   ![Accesare website.](images/q1.png)
2. Deschideți fila Network în instrumentele pentru dezvoltatori ale browserului.
   ![Deschidere fila Network.](images/q2.png)
3. Introduceți date incorecte pentru autentificare (de exemplu, username: student, password: studentpass).
   ![Autentificare prin date incorecte.](images/q3.png)
4. Analizați cererile care au fost trimise către server.
   ![A fost trimisă o cerere de tip POST.](images/q4.png)
5. Răspundeți la următoarele întrebări:

- Ce metodă HTTP a fost utilizată pentru a trimite cererea?
  - _Pentru a trimite cererea de autentificare a fost utilizată metoda POST._
- Ce anteturi au fost trimise în cerere?
  - ![Anteturile trimise în cerere](images/q5b.png)
- Ce parametri au fost trimiși în cerere?
  - ![Parametrii trimiși în cerere, valorile pentru username și passowrd.](images/q5c.png)
- Ce cod de stare a fost returnat de server?
  - _A fost returnat codul de stare (401 Unauthorized)._
- Ce anteturi au fost trimise în răspuns?
  - ![Anteturile trimise în răspuns.](images/q5e.png)

6. Repetați pașii 3-5, introducând date corecte pentru autentificare (username: admin, password: password).
   ![Cerere de tip POST cu codul de stare 200 OK returnat.](images/q6.png)
