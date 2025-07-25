Todo App - Aplikacja do zarządzania zadaniami
Prosta aplikacja webowa do zarządzania listą zadań, składająca się z backendu w Spring Boot i frontendu w React.

🚀 Funkcjonalności
✅ Dodawanie nowych zadań
✅ Oznaczanie zadań jako wykonane/niewykonane
✅ Edycja istniejących zadań
✅ Usuwanie zadań
✅ Filtrowanie zadań (wszystkie / wykonane / niewykonane)
✅ Czyszczenie wykonanych zadań

🛠️ Technologie
-Backend:

Java 21
Spring Boot 3.5.4
Spring Data JPA
Baza danych H2 (w pamięci)
Maven

-Frontend:

React 19
Axios (komunikacja z API)
CSS (stylizacja)


🚀 Instrukcja uruchomienia
-Backend (Spring Boot)
Przejdź do folderu backend:
  cd todo-backend
Uruchom aplikację:
  ./mvnw spring-boot:run
Backend będzie dostępny na: http://localhost:8080
Konsola bazy H2: http://localhost:8080/h2-console
  JDBC URL: jdbc:h2:mem:testdb
  Username: sa
  Password: (puste)
  
-Frontend (React)
Przejdź do folderu frontend:
  cd todo-frontend
Zainstaluj zależności:
  npm install
Uruchom aplikację:
  npm start
Frontend będzie dostępny na: http://localhost:3000

📡 API Endpointy
GET /api/tasks - Pobierz wszystkie zadania
POST /api/tasks - Utwórz nowe zadanie
PUT /api/tasks/{id} - Edytuj zadanie
DELETE /api/tasks/{id} - Usuń zadanie
PATCH /api/tasks/{id}/toggle - Przełącz status zadania

🎯 Jak używać aplikacji
-Uruchom backend (port 8080)
-Uruchom frontend (port 3000)
-Otwórz przeglądarkę na http://localhost:3000
-Kliknij "Dodaj nowe zadanie" żeby dodać zadanie
-Użyj przycisków przy zadaniach do edycji, usuwania, oznaczania jako wykonane
-Filtruj zadania używając przycisków filtrów

