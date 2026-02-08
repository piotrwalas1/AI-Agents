# 🤖 AI Agents - Automatyzacja Procesu QA (Google Drive -> AI -> Jira)

## 📖 Opis Projektu
Innowacyjny projekt wykorzystujący **Agentów AI** do automatyzacji powtarzalnych zadań w procesie testowym. System automatycznie pobiera plik z dokumentacją projektową z Dysku Google, przetwarza ją na profesjonalne przypadki testowe przy użyciu modeli LLM i samodzielnie raportuje je do **Jira**.

---

## 🏗️ Architektura i Przepływ (Workflow)
Projekt demonstruje pełny cykl automatyzacji "Low-Code/No-Code" z wykorzystaniem sztucznej inteligencji.

### 🔍 Etapy Procesu
| ID | Moduł | Cel i Funkcja |
| :--- | :--- | :--- |
| **Tc1** | Google Drive Agent | Automatyczne monitorowanie folderu i pobieranie plików z opisem wymagań. |
| **Tc2** | AI Reasoning | Analiza tekstu przez AI i generowanie przypadków testowych (ID, Kroki, Rezultaty). |
| **Tc3** | Jira Integration | Automatyczne tworzenie ticketów typu "Test Case" lub "Bug" w projekcie Jira. |
| **Tc4** | Data Transformation | Konwersja formatów danych (np. .txt / .docx na ustrukturyzowany JSON). |

### 🛠️ Wykorzystane Technologie
| Technologia | Zastosowanie |
| :--- | :--- |
| **AI Agents** | Autonomiczne podejmowanie decyzji o przesyłaniu danych. |
| **LLM (OpenAI/Claude)** | Silnik przetwarzający wymagania na język techniczny QA. |
| **Google Drive API** | Źródło dokumentacji wejściowej. |
| **Jira API / Zapier / Make** | Integracja z systemem zarządzania testami. |

---

## 📸 Evidence & Wyniki

<li><a href="https://github.com/piotrwalas1/PORTFOLIO/blob/main/finalny%20przeplyw.jpg">Test AI Agents – Proof of Concept - Stworzenie zespołu agentów AI do generowania przypadków testowych na podstawie dokumentacji projektowej. </a></li>
 <ul>
  <li><a href="https://youtu.be/OTUNZPEidOU">Przepływ film</a></li>

---

## 🚀 Dlaczego ten projekt jest ważny?
* **Oszczędność czasu:** Redukcja czasu potrzebnego na pisanie dokumentacji testowej o 70-80%.
* **Eliminacja błędów:** AI dba o spójność formatu każdego przypadku testowego wysyłanego do Jira.
* **Nowoczesne QA:** Pokazanie praktycznego zastosowania AI w codziennej pracy Testera Oprogramowania.

---


