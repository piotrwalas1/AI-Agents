# 🤖 AI Agents - Automatyzacja Procesu QA (Google Drive -> AI -> Jira)

## 📖 Opis Projektu
Innowacyjny projekt wykorzystujący **Agentów AI** do automatyzacji powtarzalnych zadań w procesie testowym. System automatycznie pobiera plik z dokumentacją projektową z Dysku Google, przetwarza ją na profesjonalne przypadki testowe przy użyciu modeli LLM i samodzielnie raportuje je do **Jira**.

---

## 🏗️ Architektura i Przepływ (Workflow)
Projekt demonstruje pełny cykl automatyzacji "Low-Code/No-Code" z wykorzystaniem sztucznej inteligencji.

### 🔍 Etapy Procesu

1. Google Drive → monitoruje wskazany folder na Dysku Google i uruchamia przepływ, gdy pojawi się nowy plik PDF z wymaganiami projektowymi.

2.Google Drive → pobiera zawartość nowo dodanego pliku PDF.

3.Tools → scala dane tekstowe z pliku PDF w jeden ciąg, tak aby Gemini mógł je łatwo przetworzyć.

4.Gemini → analizuje wymagania projektowe i generuje na ich podstawie przypadki testowe.

5.JSON → przekształca wygenerowany przez Gemini tekst w strukturę JSON, aby dane mogły być przetwarzane dalej.

6.Flow Control → Iterator → rozdziela poszczególne przypadki testowe z JSON-a, aby można je było utworzyć jako osobne zgłoszenia.

7.Jira Cloud → tworzy w Jirze osobne zgłoszenie (issue) dla każdego przypadku testowego.

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

  <li><a href="https://youtu.be/OTUNZPEidOU">Przepływ film</a></li>
  <p align="center">
  <img src="https://github.com/piotrwalas1/PORTFOLIO/blob/main/make%20przeplyw.jpg" width="600" title="Schemat automatyzacji">
</p>

---

## 🚀 Dlaczego ten projekt jest ważny?
* **Oszczędność czasu:** Redukcja czasu potrzebnego na pisanie dokumentacji testowej o 70-80%.
* **Eliminacja błędów:** AI dba o spójność formatu każdego przypadku testowego wysyłanego do Jira.
* **Nowoczesne QA:** Pokazanie praktycznego zastosowania AI w codziennej pracy Testera Oprogramowania.

---


