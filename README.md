# Smart Shopping

<h1 align="center">Final Project (Back-end) - Post Full-Stack</h1>

## Introduction
Facing the complexity of daily expenses is a common reality. We present Smart Shopping, an integrated platform that simplifies expense management.
Our application offers effective tracking, intuitive categorization, and real-time insight into spending, empowering users to make informed financial decisions and save time on shopping.

## Objective
We simplify users' lives with a single platform to create and manage shopping lists.
Smart Shopping offers expense tracking, keeping the budget on track. With an intuitive interface, categorize your expenses and get an instant view of your consumption habits.
Save time, gain clarity on monthly expenses, and find the best deals to save money.

## Tool
The choice of FastAPI in Python for the web service was motivated by its ease and speed in creating APIs, allowing flexible integration with various technologies. The adoption of SQLAlchemy complements FastAPI by offering an abstraction layer for simplified interaction with relational databases, ensuring a cohesive and efficient implementation of the service. This combination not only enhances development agility but also provides the robustness and flexibility needed to deal with the challenges of the modern web environment.

### Creators:

- [Daniel Bernado](https://github.com/Brnards)
- [Gabriel Dantas](https://github.com/dantas2009)

### Prerequisites
Before installing the project, ensure you have the following installed on your system:
- [Python](https://www.python.org/): Version 3.10 or higher

### Steps
1. Clone the repository to your local machine:

```bash
git clone https://github.com/dantas2009/senac-back-end.git
```

2. Navigate to the project directory:

```bash
cd senac-back-end
```

3. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

4. Activate the virtual environment :

4.1 For Windows:
```bash
venv\Scripts\activate
```
4.2 For macOS and Linux:
```bash
source venv/bin/activate
```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

6. Start the server:

```bash
uvicorn main:app --reload
```
