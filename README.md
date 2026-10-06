# IT Asset & License Management System (Microsoft Power Platform)

Biznesowy system ewidencji i zarządzania zasobami IT (sprzęt, licencje) zrealizowany w oparciu o ekosystem **Microsoft Power Platform** oraz relacyjną bazę **Microsoft Dataverse**. Rozwiązanie usprawnia rejestrację majątku IT oraz automatyzuje obieg powiadomień.

## Funkcjonalności

- **Ewidencja Zasobów (CRUD):** Zarządzanie bazą sprzętu i licencji poprzez dedykowaną aplikację biznesową (**Model-Driven App**).
- **Zarządzanie Danymi:** Typowane atrybuty biznesowe (kategorie sprzętu, statusy dostępności, wielowalutowość PLN, przypisanie pracownika).
- **Automatyzacja Procesów:** Zautomatyzowany obieg zdarzeniowy w **Power Automate** wysyłający sformatowane powiadomienia e-mail w momencie rejestracji nowego majątku IT w bazie.

## 📸 Zrzuty Ekranu Rozwiązania

### 1. Widok Aplikacji Biznesowej (Power Apps Model-Driven)
*Widok listy ewidencji zasobów z dynamicznym filtrowaniem i statusami:*
<img width="2880" height="1410" alt="orgb8570e6a crm4 dynamics com_main aspx_appid=9f956729-bfc1-f111-aaad-000d3ada809f pagetype=entitylist etn=jm_zasobyit viewid=d40684c9-b5d6-4c0e-81d5-696f4c0c73ff viewType=1039 (1)" src="https://github.com/user-attachments/assets/6fed8b26-d0da-4cfa-87a3-06e13f4c2c98" />

### 2. Architektura Przepływu Automatyzacji (Power Automate)
*Przepływ wyzwalany dodaniem wiersza do Dataverse z logiką powiadomień e-mail:*
<img width="2880" height="1410" alt="make powerapps com_environments_8727a6de-a679-e2ef-9d9e-b984a1623c4e_logicflows (1)" src="https://github.com/user-attachments/assets/3d691a8d-c622-43dc-bc75-14389a7552c2" />
<img width="2880" height="1410" alt="make powerapps com_environments_8727a6de-a679-e2ef-9d9e-b984a1623c4e_logicflows" src="https://github.com/user-attachments/assets/7ae69df6-1c1d-48fb-a2bd-a16143b97174" />

