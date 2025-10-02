# Sudoku Solver using Turing Machine
Proiect realizat pentru cursul **Analiza Algoritmilor**, în care am implementat o rezolvare de Sudoku pe baza modelului **Mașină Turing**.

## Descriere
- Scopul proiectului este de a demonstra cum poate fi formalizat și rezolvat un joc de tip Sudoku folosind o **mașină Turing**.  
- Sudoku-ul este mapat pe o bandă a mașinii, fiecare celulă fiind reprezentată de un simbol.  
- Tranzițiile mașinii verifică validitatea mutărilor (rânduri, coloane, regiuni 3x3) și aplică pașii necesari pentru completarea grilei.  
- Proiectul servește atât ca **aplicație practică a conceptelor teoretice de calculabilitate**, cât și ca **exercițiu de analiză a complexității**.  

## Structura proiectului
- `turing_machine.py` – implementarea simulatorului de mașină Turing  
- `sudoku_input.txt` – input cu grila de Sudoku inițială  
- `sudoku_tm.json` – definiția formală a mașinii Turing (stări, alfabet, tranziții)  
- `README.md` – documentația proiectului  

## Cum rulezi proiectul
1. Instalează Python 3.  
2. Rulează simulatorul cu inputul Sudoku:  
   ```bash
   python turing_machine.py sudoku_input.txt sudoku_tm.json
