# Proiect_Web 
### Acesta este README-ul asociat repository-ului realizat la Laboratorul 5 <br>
### Proiectul acest proiect are ca scop invatarea utilizarii platformei git <br>


# Managementul Codului cu Git, GitHub si VSCode
## Laboratorul 5

Proiect realizat in cadrul laboratorului 5 pentru invatarea fluxului de lucru cu sistemul de control al versiunilor Git, platforma GitHub si editorul Visual Studio Code.

---

## Informatii student

* **Nume:** Cocirla Emanuel
* **Grupa:** 3111Da
* **Specializare:** Calculatoare Dual

---

## Descrierea proiectului

In cadrul acestui laborator am parcurs urmatorii pasi principali:

1. Configurarile initiale pentru Git (nume utilizator, email si salvarea credentialelor).
2. Gestionarea repozitoriului local (initializare, verificare status, adaugare fisiere in Staging si creare commit-uri).
3. Conectarea repozitoriului local cu cel la distanta creat pe GitHub.
4. Utilizarea extensiei de Source Control din VSCode pentru gestionarea modificarilor si sincronizare.
5. Crearea documentatiei proiectului in format Markdown.

---

## Comenzi Git utilizate

```bash
# Configurare utilizator
git config --global user.name "Nume Prenume"
git config --global user.email "email@domeniu.com"

# Lucrul cu repozitoriul local
git init
git status
git add .
git commit -m "Incarcare fisiere laborator"

# Legarea la repozitoriul de pe GitHub si trimiterea codului
git remote add origin
git branch -M main
git push -u origin main
