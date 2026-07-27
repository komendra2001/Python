# Python Mastery Roadmap — Beginner → Job-Ready Professional

Companion file: **Python_Projects_and_Interview_Prep.md** (200 projects, 100 interview Qs, 100 coding problems, LeetCode/HackerRank/Codewars/Project Euler tracks).

**Table legend:** ⏱ Time | 🎯 Difficulty | 🔑 Prereq
**Recurring channel/site links:** [Corey Schafer](https://www.youtube.com/@coreyms) · [freeCodeCamp](https://www.youtube.com/@freecodecamp) · [mCoding](https://www.youtube.com/@mCoding) · [ArjanCodes](https://www.youtube.com/@ArjanCodes) · [NeetCode](https://www.youtube.com/@NeetCode) · [Real Python](https://realpython.com) · [Exercism](https://exercism.org/tracks/python) · [Codewars](https://www.codewars.com) · [HackerRank](https://www.hackerrank.com/domains/python)

---

## STAGE 1 — FUNDAMENTALS

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Install + VS Code/PyCharm setup | [Corey Schafer – setup](https://www.youtube.com/@coreyms) | [python.org/downloads](https://www.python.org/downloads/) | Run "Hello World" | 30m | Easy |
| Running programs (REPL vs script) | [freeCodeCamp full course](https://www.youtube.com/@freecodecamp) | [docs.python.org/3/tutorial](https://docs.python.org/3/tutorial/) | — | 30m | Easy |
| Variables & data types | [Corey Schafer – Variables](https://www.youtube.com/@coreyms) | [Built-in types](https://docs.python.org/3/library/stdtypes.html) | [Exercism Python track](https://exercism.org/tracks/python) | 1h | Easy |
| Input/output, f-strings | [Corey Schafer – Formatting](https://www.youtube.com/@coreyms) | [PEP 498](https://peps.python.org/pep-0498/) | [Codewars 8kyu](https://www.codewars.com/kata/search/python?difficulty%5B%5D=8) | 1h | Easy |
| Operators & type conversion | [freeCodeCamp](https://www.youtube.com/@freecodecamp) | [Expressions](https://docs.python.org/3/reference/expressions.html) | [HackerRank 10 Days of Python](https://www.hackerrank.com/domains/tutorials/10-days-of-python) | 1h | Easy |
| Strings & string methods | [Corey Schafer – Strings](https://www.youtube.com/@coreyms) | [str methods](https://docs.python.org/3/library/stdtypes.html#string-methods) | [Codewars string kata](https://www.codewars.com/kata/search/python?q=strings) | 2h | Easy |
| Comments, basic debugging | [freeCodeCamp](https://www.youtube.com/@freecodecamp) | [pdb docs](https://docs.python.org/3/library/pdb.html) | Debug 3 broken scripts | 1h | Easy |
| Basic math ops | [Corey Schafer channel](https://www.youtube.com/@coreyms) | [math module](https://docs.python.org/3/library/math.html) | Build a calculator | 1h | Easy |

**Book:** [Automate the Boring Stuff](https://automatetheboringstuff.com/) (free, Al Sweigart).
**Stage total:** ~8h | **Mini project:** BMI/tip calculator | **Mistakes:** `=` vs `==`, `input()` returns str, indentation errors.

---

## STAGE 2 — CONTROL FLOW

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| if/elif/else, nesting | [Corey Schafer – If Statements](https://www.youtube.com/@coreyms) | [Compound statements](https://docs.python.org/3/reference/compound_stmts.html) | [Codewars 8kyu](https://www.codewars.com/kata/search/python?difficulty%5B%5D=8) | 1h | Easy |
| match-case (3.10+) | [mCoding – match](https://www.youtube.com/@mCoding) | [PEP 636](https://peps.python.org/pep-0636/) | Refactor an if-chain to match-case | 1h | Med |
| for/while, range, enumerate | [Corey Schafer – Loops](https://www.youtube.com/@coreyms) | [Loop constructs](https://docs.python.org/3/tutorial/controlflow.html) | [HackerRank](https://www.hackerrank.com/domains/python) | 2h | Easy |
| break/continue/pass | [freeCodeCamp](https://www.youtube.com/@freecodecamp) | same | Build FizzBuzz | 1h | Easy |
| Loop patterns | — | — | Print patterns/pyramids | 2h | Med |

**Stage total:** ~7h | **Mini project:** Number-guessing game | **Challenge:** Text hangman | **Compare:** `for` (known count) vs `while` (condition-based).

---

## STAGE 3 — FUNCTIONS

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| def, parameters, return | [Corey Schafer – Functions](https://www.youtube.com/@coreyms) | [Defining functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions) | [Codewars](https://www.codewars.com/kata/search/python) | 2h | Easy |
| Scope (LEGB) | [mCoding – scope](https://www.youtube.com/@mCoding) | [Scopes & namespaces](https://docs.python.org/3/tutorial/classes.html#python-scopes-and-namespaces) | Predict-output quizzes | 1h | Med |
| Default/keyword args, *args/**kwargs | [Corey Schafer](https://www.youtube.com/@coreyms) | [More on functions](https://docs.python.org/3/tutorial/controlflow.html#more-on-defining-functions) | Build a flexible logger function | 2h | Med |
| Lambda functions | [Corey Schafer – Lambda](https://www.youtube.com/@coreyms) | [Lambda expr](https://docs.python.org/3/reference/expressions.html#lambda) | Sort dicts using lambda | 1h | Med |
| Recursion | [NeetCode – recursion](https://www.youtube.com/@NeetCode) | — | [Exercism](https://exercism.org/tracks/python) recursion exercises | 3h | Med-Hard |
| Docstrings & type hints | [Real Python – Type Checking](https://realpython.com/python-type-checking/) | [typing](https://docs.python.org/3/library/typing.html), [PEP 257](https://peps.python.org/pep-0257/) | Add type hints to Stage 1–2 code | 1h | Med |

**Stage total:** ~10h | **Compare:** recursion vs iteration | **Mini project:** temperature converter | **Challenge:** recursive maze solver.

---

## STAGE 4 — DATA STRUCTURES

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Lists & methods | [Corey Schafer – Lists](https://www.youtube.com/@coreyms) | [Lists](https://docs.python.org/3/tutorial/datastructures.html) | [HackerRank](https://www.hackerrank.com/domains/python) | 2h | Easy |
| Tuples | [Corey Schafer – Tuples](https://www.youtube.com/@coreyms) | same | — | 1h | Easy |
| Sets | [Corey Schafer – Sets](https://www.youtube.com/@coreyms) | [Sets](https://docs.python.org/3/tutorial/datastructures.html#sets) | Dedup problems | 1h | Easy |
| Dictionaries | [Corey Schafer – Dicts](https://www.youtube.com/@coreyms) | [Dicts](https://docs.python.org/3/tutorial/datastructures.html#dictionaries) | Word-frequency counter | 2h | Easy-Med |
| Comprehensions | [Corey Schafer – Comprehensions](https://www.youtube.com/@coreyms) | [Comprehensions](https://docs.python.org/3/tutorial/datastructures.html#list-comprehensions) | Rewrite 10 loops as comprehensions | 2h | Med |
| Nested structures, sort/search | [Real Python – Sorting](https://realpython.com/python-sort/) | [sorted()](https://docs.python.org/3/library/functions.html#sorted) | Sort dicts, nested JSON | 2h | Med |
| `collections` module | [mCoding – collections](https://www.youtube.com/@mCoding) | [collections](https://docs.python.org/3/library/collections.html) | Rebuild script using Counter | 2h | Med |

**Compare:** List (mutable, ordered) · Tuple (immutable) · Set (unique, unordered) · Dict (key-value).
**Stage total:** ~12h | **Mini project:** Contact book | **Challenge:** Word-frequency analyzer.

---

## STAGE 5 — FILE HANDLING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Read/write, `with` | [Corey Schafer – File Objects](https://www.youtube.com/@coreyms) | [File I/O](https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files) | Log parser | 2h | Easy |
| CSV | [Corey Schafer – CSV](https://www.youtube.com/@coreyms) | [csv](https://docs.python.org/3/library/csv.html) | Parse a real CSV export | 1h | Easy |
| JSON | [Corey Schafer – JSON](https://www.youtube.com/@coreyms) | [json](https://docs.python.org/3/library/json.html) | Save/load app config | 1h | Easy |
| Pickle | [Real Python – Pickle](https://realpython.com/python-pickle-module/) | [pickle](https://docs.python.org/3/library/pickle.html) | Serialize a custom object | 1h | Med |
| Pathlib | [mCoding – pathlib](https://www.youtube.com/@mCoding) | [pathlib](https://docs.python.org/3/library/pathlib.html) | Rewrite `os.path` code | 1h | Med |
| Directories, compression | [Real Python – zipfile](https://realpython.com/python-zipfile/) | [shutil](https://docs.python.org/3/library/shutil.html), [zipfile](https://docs.python.org/3/library/zipfile.html) | Batch-rename + zip a folder | 2h | Med |

**Stage total:** ~8h | **Mini project:** Bulk file renamer | **Challenge:** Folder backup + zip automation.

---

## STAGE 6 — EXCEPTION HANDLING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| try/except/else/finally | [Corey Schafer](https://www.youtube.com/@coreyms) | [Errors & exceptions](https://docs.python.org/3/tutorial/errors.html) | Handle 5 common errors | 2h | Easy-Med |
| raise, assertions | [Real Python – assert](https://realpython.com/python-assert-statement/) | [raise](https://docs.python.org/3/reference/simple_stmts.html#raise) | Input validator with asserts | 1h | Med |
| Custom exceptions | [mCoding – exceptions](https://www.youtube.com/@mCoding) | [User-defined exceptions](https://docs.python.org/3/tutorial/errors.html#user-defined-exceptions) | `InsufficientFundsError` | 1h | Med |
| Logging basics | [Corey Schafer – Logging](https://www.youtube.com/@coreyms) | [logging](https://docs.python.org/3/library/logging.html) | Replace all prints with logging | 2h | Med |

**Mistake:** bare `except:` hides bugs. **Stage total:** ~6h | **Mini project:** Robust upload validator | **Challenge:** Custom exception hierarchy for a bank app.

---

## STAGE 7 — OBJECT-ORIENTED PROGRAMMING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Classes, `__init__` | [Corey Schafer OOP series](https://www.youtube.com/@coreyms) | [Classes](https://docs.python.org/3/tutorial/classes.html) | Build a `Car` class | 2h | Med |
| Instance vs class vars | Corey Schafer OOP pt.2 | same | — | 1h | Med |
| Methods, encapsulation | Corey Schafer OOP pt.3 | — | Private attrs + properties | 2h | Med |
| Inheritance & polymorphism | Corey Schafer OOP pt.4 | — | Animal → Dog/Cat hierarchy | 2h | Med |
| Abstraction (ABC) | [mCoding – ABC](https://www.youtube.com/@mCoding) | [abc module](https://docs.python.org/3/library/abc.html) | Abstract `Shape` class | 1h | Med-Hard |
| Composition vs inheritance | [ArjanCodes](https://www.youtube.com/@ArjanCodes) | — | Refactor inheritance-heavy design | 2h | Hard |
| Magic/dunder methods | [Corey Schafer – Magic Methods](https://www.youtube.com/@coreyms) | [Data model](https://docs.python.org/3/reference/datamodel.html) | `__str__`, `__eq__`, `__add__` on `Vector` | 2h | Hard |
| Dataclasses | [mCoding – dataclasses](https://www.youtube.com/@mCoding) | [dataclasses](https://docs.python.org/3/library/dataclasses.html) | Convert 3 classes to `@dataclass` | 1h | Med |

**Stage total:** ~13h | **Compare:** inheritance ("is-a") vs composition ("has-a") | **Mini project:** Library system | **Challenge:** Bank account system.

---

## STAGE 8 — MODULES & PACKAGES

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Import systems | [Real Python – Modules](https://realpython.com/python-modules-packages/) | [Modules](https://docs.python.org/3/tutorial/modules.html) | Split a script into modules | 1h | Easy |
| Creating packages | [Real Python – Packages](https://realpython.com/python-modules-packages/) | [Packages](https://docs.python.org/3/tutorial/modules.html#packages) | Make an installable package | 2h | Med |
| Virtual environments | [Corey Schafer – venv](https://www.youtube.com/@coreyms) | [venv](https://docs.python.org/3/library/venv.html) | Isolated envs for 2 projects | 1h | Easy |
| pip, requirements.txt | [Corey Schafer – pip](https://www.youtube.com/@coreyms) | [pip.pypa.io](https://pip.pypa.io/) | Freeze + recreate an environment | 1h | Easy |
| pyproject.toml | [Real Python](https://realpython.com/python-toml/) | [packaging.python.org](https://packaging.python.org/) | Package a CLI tool | 2h | Med |

**Tool tip:** [`uv`](https://docs.astral.sh/uv/) or [`poetry`](https://python-poetry.org/) over raw pip+venv.
**Stage total:** ~7h | **Mini project:** Publish a small internal utility as a package.

---

## STAGE 9 — INTERMEDIATE PYTHON

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Iterators & protocol | [Corey Schafer – Iterators](https://www.youtube.com/@coreyms) | [Iterators](https://docs.python.org/3/tutorial/classes.html#iterators) | Custom iterator class | 2h | Med |
| Generators & `yield` | [Corey Schafer – Generators](https://www.youtube.com/@coreyms) | [Generators](https://docs.python.org/3/tutorial/classes.html#generators) | Rewrite heavy function as generator | 2h | Med-Hard |
| Decorators & closures | [Corey Schafer – Decorators](https://www.youtube.com/@coreyms) | [Closures](https://docs.python.org/3/glossary.html#term-closure) | Timing/logging decorator | 3h | Hard |
| Context managers | [mCoding](https://www.youtube.com/@mCoding) | [Context managers](https://docs.python.org/3/reference/datamodel.html#context-managers) | Custom DB-connection context manager | 2h | Hard |
| Regular expressions | [Corey Schafer – Regex](https://www.youtube.com/@coreyms) | [re module](https://docs.python.org/3/library/re.html) | [regex101.com](https://regex101.com/) testing; validate emails/phone | 2h | Med |
| `itertools`/`functools` | [mCoding – itertools](https://www.youtube.com/@mCoding) | [itertools](https://docs.python.org/3/library/itertools.html), [functools](https://docs.python.org/3/library/functools.html) | Rewrite loops using `chain`, `groupby` | 2h | Hard |

**Stage total:** ~13h | **Compare:** generator (lazy) vs list (eager) | **Mini project:** `@retry` decorator | **Challenge:** Lazy data pipeline.

---

## STAGE 10 — ADVANCED PYTHON

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| asyncio | [mCoding – asyncio](https://www.youtube.com/@mCoding) | [asyncio](https://docs.python.org/3/library/asyncio.html) | Concurrent scraper with `aiohttp` | 4h | Hard |
| Threading | [Corey Schafer – Threading](https://www.youtube.com/@coreyms) | [threading](https://docs.python.org/3/library/threading.html) | Multi-threaded downloader | 3h | Hard |
| Multiprocessing | [Corey Schafer – Multiprocessing](https://www.youtube.com/@coreyms) | [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) | CPU-bound parallel task | 3h | Hard |
| Memory & GC | [mCoding](https://www.youtube.com/@mCoding) | [gc module](https://docs.python.org/3/library/gc.html) | Diagnose a memory leak | 2h | Hard |
| Profiling & optimization | [mCoding – profiling](https://www.youtube.com/@mCoding) | [cProfile](https://docs.python.org/3/library/profile.html) | Profile + speed up a slow script | 2h | Hard |
| Metaclasses & descriptors | [ArjanCodes](https://www.youtube.com/@ArjanCodes) | [Metaclasses](https://docs.python.org/3/reference/datamodel.html#metaclasses) | ORM-style descriptor | 3h | Very Hard |

**Stage total:** ~17h | **Compare:** threading (I/O, GIL-limited) vs multiprocessing (true parallel CPU) vs asyncio (I/O concurrency) | **Mini project:** Async scraper | **Challenge:** Thread-pool image resizer.

---

## STAGE 11 — DATA STRUCTURES & ALGORITHMS

| Topic | Free Resource | Docs/Ref | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Arrays, linked lists, stacks, queues | [NeetCode](https://www.youtube.com/@NeetCode) | *Grokking Algorithms* | [LeetCode Easy](https://leetcode.com/problemset/?difficulty=EASY) | 6h | Med |
| Trees, heaps | [NeetCode – Trees](https://www.youtube.com/@NeetCode) | — | [LeetCode tree tag](https://leetcode.com/tag/tree/) | 6h | Med-Hard |
| Graphs (BFS/DFS, Dijkstra) | [NeetCode – Graphs](https://www.youtube.com/@NeetCode) | — | [LeetCode graph tag](https://leetcode.com/tag/graph/) | 8h | Hard |
| Hash tables | [NeetCode](https://www.youtube.com/@NeetCode) | — | Two-sum family problems | 2h | Med |
| Sorting/searching | [Abdul Bari](https://www.youtube.com/@abdul_bari) | — | Implement quicksort/mergesort/binary search | 4h | Med |
| Recursion & backtracking | [NeetCode – Backtracking](https://www.youtube.com/@NeetCode) | — | N-Queens, permutations | 4h | Hard |
| Dynamic programming | [NeetCode – DP](https://www.youtube.com/@NeetCode) | — | Climbing stairs → knapsack | 8h | Very Hard |
| Greedy algorithms | [NeetCode](https://www.youtube.com/@NeetCode) | — | Interval scheduling | 3h | Hard |
| Big-O complexity | [NeetCode – Big O](https://www.youtube.com/@NeetCode) | — | Analyze your own solutions | 2h | Med |

**Stage total:** ~43h — pace over weeks. Curated list: [NeetCode 150](https://neetcode.io/practice).

---

## STAGE 12 — TESTING & CODE QUALITY

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| unittest | [Corey Schafer](https://www.youtube.com/@coreyms) | [unittest](https://docs.python.org/3/library/unittest.html) | Test a calculator module | 2h | Med |
| pytest (industry standard) | [Real Python – pytest](https://realpython.com/pytest-python-testing/) | [docs.pytest.org](https://docs.pytest.org/) | Convert unittest suite to pytest | 2h | Med |
| Mocking | [Corey Schafer – Mocking](https://www.youtube.com/@coreyms) | [unittest.mock](https://docs.python.org/3/library/unittest.mock.html) | Mock an API call in tests | 2h | Med-Hard |
| Coverage | [coverage.readthedocs.io](https://coverage.readthedocs.io/) | same | Get a project to 90% coverage | 1h | Med |
| Linters/formatters | [Ruff docs](https://docs.astral.sh/ruff/) | [PEP 8](https://peps.python.org/pep-0008/) | Lint + format 3 old projects | 2h | Easy-Med |

**Stage total:** ~9h | **Mini project:** Tested + linted calculator package | **Challenge:** CI-ready tests for a past project.

---

## STAGE 13 — DATABASES

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| SQL fundamentals | [freeCodeCamp SQL](https://www.youtube.com/@freecodecamp) | [sqlite.org/docs](https://www.sqlite.org/docs.html) | [SQLZoo](https://sqlzoo.net/) · [Mode SQL tutorial](https://mode.com/sql-tutorial/) | 4h | Med |
| SQLite | [Corey Schafer – SQLite3](https://www.youtube.com/@coreyms) | [sqlite3](https://docs.python.org/3/library/sqlite3.html) | Build a CRUD CLI app | 3h | Med |
| MySQL / PostgreSQL | [freeCodeCamp PostgreSQL](https://www.youtube.com/@freecodecamp) | [psycopg.org](https://www.psycopg.org/) | Connect Python to Postgres | 3h | Med-Hard |
| SQLAlchemy / ORM | [Real Python – SQLAlchemy](https://realpython.com/tutorials/databases/) | [docs.sqlalchemy.org](https://docs.sqlalchemy.org/) | Rebuild CRUD app with ORM | 4h | Hard |
| Database design | [freeCodeCamp DB design](https://www.youtube.com/@freecodecamp) | — | Schema for a bookstore app | 3h | Med |

**Stage total:** ~17h | **Mini project:** Todo-app with SQLite | **Challenge:** Full CRUD API + PostgreSQL + SQLAlchemy.

---

## STAGE 14 — APIs & NETWORKING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| HTTP, REST principles | [freeCodeCamp – APIs](https://www.youtube.com/@freecodecamp) | [MDN HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) | — | 2h | Med |
| `requests` library | [Corey Schafer – requests](https://www.youtube.com/@coreyms) | [requests.readthedocs.io](https://requests.readthedocs.io/) | Consume a public API | 2h | Med |
| JSON handling | Real Python (Stage 5 link) | [json](https://docs.python.org/3/library/json.html) | Parse nested API responses | 1h | Easy |
| Auth: OAuth, JWT | [freeCodeCamp – JWT](https://www.youtube.com/@freecodecamp) | [jwt.io/introduction](https://jwt.io/introduction) | Token-based auth flow | 3h | Hard |
| FastAPI | [Official tutorial](https://fastapi.tiangolo.com/tutorial/) | [fastapi.tiangolo.com](https://fastapi.tiangolo.com/) | Build a CRUD API | 5h | Med-Hard |
| WebSockets | [FastAPI WS guide](https://fastapi.tiangolo.com/advanced/websockets/) | same | Live chat backend | 4h | Hard |

**Stage total:** ~17h | **Mini project:** Weather CLI | **Challenge:** JWT-authenticated FastAPI + WebSocket feed.

---

## STAGE 15 — WEB DEVELOPMENT

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Flask | [Corey Schafer Flask series](https://www.youtube.com/@coreyms) | [flask.palletsprojects.com](https://flask.palletsprojects.com/) | Build a blog app | 8h | Med |
| Django | [freeCodeCamp Django](https://www.youtube.com/@freecodecamp) | [djangoproject.com](https://www.djangoproject.com/) | Full CRUD site w/ auth | 12h | Med-Hard |
| FastAPI (web angle) | [Official tutorial](https://fastapi.tiangolo.com/tutorial/) | same as Stage 14 | API-first web app | 6h | Med-Hard |
| Templates (Jinja2) | Corey Schafer (same channel) | [jinja.palletsprojects.com](https://jinja.palletsprojects.com/) | Template a multi-page site | 2h | Easy-Med |
| Auth & sessions | Corey Schafer Flask-Login series | [Flask-Login](https://flask-login.readthedocs.io/) | Add login/signup to blog | 4h | Hard |

**Stage total:** ~32h | **Compare:** Flask (minimal) vs Django (batteries-included) vs FastAPI (async/API-centric) | **Mini project:** Personal blog | **Challenge:** Django e-commerce site.

---

## STAGE 16 — AUTOMATION & SCRIPTING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Selenium | [Corey Schafer – Selenium](https://www.youtube.com/@coreyms) | [selenium.dev/documentation](https://www.selenium.dev/documentation/) | Automate login + form fill | 3h | Med |
| BeautifulSoup | [Corey Schafer – Scraping](https://www.youtube.com/@coreyms) | [crummy.com/BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) | Scrape a news site | 2h | Med |
| OpenPyXL, pandas automation | [Corey Schafer – OpenPyXL](https://www.youtube.com/@coreyms) | [openpyxl.readthedocs.io](https://openpyxl.readthedocs.io/) | Auto-generate Excel reports | 3h | Med |
| Email automation | [Real Python – smtplib](https://realpython.com/python-send-email/) | [smtplib](https://docs.python.org/3/library/smtplib.html) | Auto-send a report via email | 1h | Med |
| PDF automation | [pypdf.readthedocs.io](https://pypdf.readthedocs.io/) | same | Merge/split/extract PDFs | 2h | Med |
| Task scheduling | [schedule.readthedocs.io](https://schedule.readthedocs.io/) | same | Schedule report script daily | 1h | Easy-Med |

**Stage total:** ~12h | **Mini project:** Automated Excel report emailer | **Challenge:** Scrape → clean → email pipeline, scheduled.

---

## STAGE 17 — DATA SCIENCE

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| NumPy | [Keith Galli](https://www.youtube.com/@KeithGalli) | [numpy.org/doc](https://numpy.org/doc/) | [Kaggle Learn](https://www.kaggle.com/learn) | 4h | Med |
| Pandas | [Corey Schafer Pandas series](https://www.youtube.com/@coreyms) | [pandas.pydata.org/docs](https://pandas.pydata.org/docs/) | Clean a [Kaggle dataset](https://www.kaggle.com/datasets) | 8h | Med |
| Matplotlib/Seaborn/Plotly | [Corey Schafer Matplotlib series](https://www.youtube.com/@coreyms) | [matplotlib.org/stable](https://matplotlib.org/stable/) | Visualize a dataset 5 ways | 4h | Med |
| Data cleaning & EDA | [Kaggle – Data Cleaning](https://www.kaggle.com/learn/data-cleaning) | — | Full EDA on a messy CSV | 5h | Med-Hard |

**Stage total:** ~21h | **Mini project:** EDA + visualization | **Challenge:** Cleaning pipeline for 100K-row dataset.

---

## STAGE 18 — MACHINE LEARNING

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Scikit-learn fundamentals | [freeCodeCamp – ML](https://www.youtube.com/@freecodecamp) | [scikit-learn.org/stable](https://scikit-learn.org/stable/) | [Kaggle Titanic](https://www.kaggle.com/c/titanic) | 8h | Hard |
| Regression, classification, clustering | [StatQuest](https://www.youtube.com/@statquest) | same | [Kaggle competitions](https://www.kaggle.com/competitions) | 10h | Hard |
| Model evaluation, feature engineering | [Kaggle – Intermediate ML](https://www.kaggle.com/learn/intermediate-machine-learning) | — | Improve a baseline model | 6h | Hard |
| TensorFlow / PyTorch intro | [PyTorch tutorials](https://pytorch.org/tutorials/) · [TensorFlow tutorials](https://www.tensorflow.org/tutorials) | same | Simple image classifier | 10h | Very Hard |

**Stage total:** ~34h | **Mini project:** Titanic predictor | **Challenge:** CNN image classifier.

---

## STAGE 19 — DEVOPS & DEPLOYMENT

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Git & GitHub | [freeCodeCamp Git](https://www.youtube.com/@freecodecamp) | [git-scm.com/doc](https://git-scm.com/doc) | Contribute to your own past projects | 4h | Easy-Med |
| Linux basics | [freeCodeCamp Linux](https://www.youtube.com/@freecodecamp) | — | Basic shell scripting | 3h | Med |
| Docker | [freeCodeCamp Docker](https://www.youtube.com/@freecodecamp) | [docs.docker.com](https://docs.docker.com/) | Containerize a Flask/FastAPI app | 4h | Med-Hard |
| CI/CD | [GitHub Actions docs](https://docs.github.com/en/actions) | same | Test-on-push pipeline | 3h | Hard |
| Deployment | [Render docs](https://render.com/docs) · [Railway docs](https://docs.railway.app/) | respective docs | Deploy 2 different apps | 4h | Med |
| Env vars, logging, monitoring | [python-dotenv](https://pypi.org/project/python-dotenv/) | [os.environ](https://docs.python.org/3/library/os.html#os.environ) | Externalize secrets | 1h | Easy |

**Stage total:** ~19h | **Mini project:** Deploy Flask app to Render with CI | **Challenge:** Dockerized app + CI/CD to a cloud host.

---

## STAGE 20 — PROFESSIONAL PYTHON DEVELOPMENT

| Topic | Free Resource | Docs | Practice | ⏱ | 🎯 |
|---|---|---|---|---|---|
| Design patterns | [ArjanCodes – Design Patterns](https://www.youtube.com/@ArjanCodes) | — | Refactor using Factory/Strategy pattern | 6h | Hard |
| SOLID principles | [ArjanCodes – SOLID](https://www.youtube.com/@ArjanCodes) | — | Refactor a God-class | 4h | Hard |
| Clean code & architecture | [ArjanCodes – Clean Code](https://www.youtube.com/@ArjanCodes) | *Clean Code* (book) | Review your own Stage 7 project | 4h | Hard |
| System design basics | [ByteByteGo](https://www.youtube.com/@ByteByteGo) | — | Design a URL shortener on paper | 4h | Hard |
| Security best practices | [OWASP Top 10](https://owasp.org/www-project-top-ten/) | same | Audit a past web project | 3h | Hard |
| Packaging & PyPI | [Official PyPA guide](https://packaging.python.org/) | same | Publish a small utility package | 2h | Med |
| Code reviews & Agile | — | — | Peer-review a PR (great GSoC practice) | 2h | Med |

**Stage total:** ~25h

---

## ROADMAPS

**30-Day Beginner:** Wk1 Fundamentals → Wk2 Control Flow + Functions → Wk3 Data Structures → Wk4 File/Exception Handling + capstone (CLI contact book).
**90-Day Intermediate:** Days 1–30 above → 31–50 OOP + Modules → 51–70 Intermediate Python → 71–90 Testing + start Databases; capstone: tested, packaged CLI + SQLite.
**180-Day Professional:** 1–90 above → 91–120 Advanced Python + start DSA → 121–150 APIs + Web Dev → 151–180 Deploy full app w/ CI/CD; start applying to internships.
**1-Year Mastery:** Months 1–6 above → 7–8 finish DSA → 9–10 specialize (Data Science/ML or backend/DevOps) → 11–12 portfolio polish, open-source, mock interviews, applications.

**Daily schedules:** 30min = 15 concept+15 practice | 1hr = 20 concept+30 practice+10 review | 2hr = 30 concept+60 coding+30 DSA | 4hr = 45 concept+90 project+60 DSA+45 review.
**At 8–10 hr/week:** ~1.5hr/day, 6 days/week — use the 1–2hr split, biased toward 2hr on weekends.

---

## DOMAIN QUICK MAP
Automation → St.16 | Web Dev → St.15 | Data Science → St.17 | ML/AI → St.18 | Cybersecurity → St.20 + [`scapy`](https://scapy.net/)/[`cryptography`](https://cryptography.io/) | DevOps/Cloud → St.19 | Finance → pandas + [`yfinance`](https://pypi.org/project/yfinance/) | Game Dev → [`pygame`](https://www.pygame.org/docs/) | Desktop → [`tkinter`](https://docs.python.org/3/library/tkinter.html)/[`PySide`](https://doc.qt.io/qtforpython/)

---

## TOOLS
| Category | Recommendation |
|---|---|
| IDE | [VS Code](https://code.visualstudio.com/) or [PyCharm](https://www.jetbrains.com/pycharm/) |
| Debugger | Built-in VS Code debugger; [`pdb`](https://docs.python.org/3/library/pdb.html) |
| Linter/Formatter | [Ruff](https://docs.astral.sh/ruff/) + [Black](https://black.readthedocs.io/) |
| Type checker | [mypy](https://mypy.readthedocs.io/) |
| Package manager | [`uv`](https://docs.astral.sh/uv/) or [`poetry`](https://python-poetry.org/) |
| Must-know stdlib | `os`,`sys`,`json`,`re`,`datetime`,`collections`,`itertools`,`functools`,`pathlib`,`logging`,`argparse`,`unittest` |
| Must-know 3rd-party | `requests`,`pandas`,`numpy`,`pytest`,`SQLAlchemy`,`FastAPI`/`Flask` |

---

## CERTIFICATIONS
[PCEP](https://pythoninstitute.org/pcep) — entry point, endorsed by Cisco/Stanford/WGU, ~$59, free prep via [Python Essentials 1 on Edube](https://edube.org/study/pe1).
[PCAP](https://pythoninstitute.org/pcap) — ~$295, for moving past junior roles, best paired with a portfolio.
[Google/IBM Professional Certificates](https://www.coursera.org/) — ~$49/month, broader data/ML-adjacent credential.
**Reality check:** a cert complements experience, doesn't replace it — projects matter more.

---

## CAREER: RESUME, PORTFOLIO, JOBS
- **GitHub:** pin 4–6 best projects with real READMEs.
- **Resume:** lead with impact, not a syntax list.
- **Freelancing:** 3 portfolio pieces → [Upwork](https://www.upwork.com/)/[Fiverr](https://www.fiverr.com/) targeting "Python automation" → recurring clients.
- **Remote jobs:** target automation/backend roles → 6 months consistent GitHub activity → apply broadly.
- **Open source:** [goodfirstissue.dev](https://goodfirstissue.dev/) → docs/tests before code → overlaps with GSoC prep.
- **Salaries:** check [Levels.fyi](https://www.levels.fyi/) or [Glassdoor](https://www.glassdoor.com/) for your region — figures shift too often to fix here.

