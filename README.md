# NamePending
## Concept
NamePending is a University library management platform designed to optimize the process of renting and returning books, providing a REST API Microservice & a Webapp Interface for both administrating and managing books and rents, making it possible to integrate in other environnements, and developing native desktop/phone apps.

## Needs Analysis
- A student/professor interface for managing rented books, showing delays and warnings, and offering the possibility to extend delays.
- An admin/staff interface for both assigning books to students/professors, adding books to the inventory, and check logs and events.
- Possibility of creating a student/professor account without staff intervention.
- Guest access is also possible to check for availability of a book/piece of work.
- Importing and Exporting Data in a CSV/SQLite format.
- A simple and advanced search interface (FTS5 for partial matches).
- Getting book infos from the ISBN13 using public APIs (OPTIONAL).
- Possibility of scanning a books codebar to autofill its infos (OPTIONAL).

## Project Components

### Backend: Mellow
#### Team members
- MOUHOUS Mathya: Designing the RESTFUL API endpoints
- AIT MEDDOUR Fouâd-Eddine: Implementation of the API endpoints
#### Stack
- [BCHS](https://learnbchs.org): The backbone of the server, BCHS is not a software per-say, but merely a concept/idea. It prioritizes security and sandboxing over speed.
- [kcgi](https://github.com/kristapsdz/kcgi): "kcgi is an open source CGI and FastCGI library for C/C++ web applications. It's minimal, secure, auditable, and fits within your BCHS software stack"[^1]
 
- [sqlbox](https://github.com/kristapsdz/sqlbox)
- [SQLiteV3](https://www.sqlite.org/)
### Frontend: NamePending
#### Team members
- SAHI Imene
- SOLTANA Melissa
#### Stack



## Sources & Citations
[^1] : Kristaps DZONSONS at https://github.com/kristapsdz/kcgi