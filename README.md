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


## License

TO BE DETERMINED 


## Project Components

### Backend: Mellow
#### Team members
- [MOUHOUS Mathya](https://github.com/MathyazSnoozin): Designing the RESTFUL API endpoints
- [AIT MEDDOUR Fouâd-Eddine](https://github.com/Paranoid-Pufferfish): Implementation of the API endpoints
#### Stack
- [BCHS](https://learnbchs.org): The backbone of the server, BCHS is not a software per-say, but merely a concept/idea. It prioritizes security and sandboxing over speed.
- [kcgi](https://github.com/kristapsdz/kcgi): "kcgi is an open source CGI and FastCGI library for C/C++ web applications. It's minimal, secure, auditable, and fits within your BCHS software stack"[¹](#1)
- [sqlbox](https://github.com/kristapsdz/sqlbox): "sqlbox is an open source C/C++ secure database access library at this time limited to sqlite3 databases"[²](#2)
- [SQLiteV3](https://www.sqlite.org/): "SQLite is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day"[³](#3)
- [OpenBSD](http://openbsd.org/): "The OpenBSD project produces a FREE, multi-platform 4.4BSD-based UNIX-like operating system. Our efforts emphasize portability, standardization, correctness, proactive security and integrated cryptography"[⁴](#4)
### Frontend: NamePending
#### Team members
- [SAHI Imene](https://github.com/ImeneeSh)
- [SOLTANA Melissa](https://github.com/melissa60)
#### Stack



## Sources & Citations
- [1] : Kristaps DZONSONS: https://github.com/kristapsdz/kcgi <a id='1'></a>
- [2] : Kristaps DZONSONS: https://github.com/kristapsdz/sqlbox <a id='2'></a>
- [3] : Richard Hipp: https://www.sqlite.org <a id='3'></a>
- [4] : https://openbsd.org <a id='4'></a> 