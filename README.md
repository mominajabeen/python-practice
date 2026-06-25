# python-practice

A repository for tracking my progress, learning core concepts, and building projects with Python and FastAPI.

## 🚀 Projects & Modules

* **01-hello-world**: Basic FastAPI setup and introduction to ASGI servers.
* **02-path-and-query-params**: Exploring data extraction via required path elements and optional query parameters.

## 🛠️ How to Run Locally
### 1. Clone the repository

git clone [https://github.com/mominajabeen/python-practice.git](https://github.com/mominajabeen/python-practice.git)
cd python-practice

```bash
python -m venv .venv
   source .venv/Scripts/activate  # On Windows
   pip install "fastapi[standard]"
```
```bash
### Run a specific module:
python -m uvicorn 01-hello-world.main:app --reload
```
