# git-training

Małe repozytorium treningowe do nauki **Git + DevOps**.

## 📦 Cel projektu

- Ćwiczenie podstaw Git: `init`, `add`, `commit`, `branch`, `merge`, `remote`
- Integracja z GitHub (push, pull, praca na zdalnym repo)
- Przygotowanie do dalszej nauki: Docker, CI/CD, Kubernetes

## ▶️ Wymagania

- Zainstalowany **Git**
- Konto na **GitHub**
- (opcjonalnie) terminal Bash / WSL / Linux

## 🚀 Podstawowy workflow

Przykładowy przepływ pracy w tym repo:

```bash
# sklonowanie repo (z innej maszyny)
git clone https://github.com/Hsurazynski/git-training.git
cd git-training

# utworzenie gałęzi funkcyjnej
git checkout -b feature-nowa-funkcja

# praca nad plikami
echo "Nowa zmiana" >> notes.txt

# dodanie i commit
git add notes.txt
git commit -m "Dodano nową linię w notes.txt"

# wysłanie zmian na GitHub
git push -u origin feature-nowa-funkcja

