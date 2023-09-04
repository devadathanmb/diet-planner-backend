# Diet Planner Application

## Table of Contents

- [About the Project](#about-the-project)
- [Getting Started](#getting-started)
- [License](#license)

## About the Project

Diet Planner Application is a project developed as part of the [KTU](https://ktu.edu.in/) (APJ Abdul Kalam Technological University) **mini project (CSD 334)** curriculum.

**Please Note**: This repository contains the RESTful API for the project. The frontend code for the application resides in a separate repository, which can be found [here](https://github.com/Rishi4137/DietPlannerApp).

The project is a diet planner application that generates a diet plan for the user from the meals that the user inputs by using **Linear Programming**.

## Getting Started

### Using docker

1. Clone the repo

```bash
git clone https://github.com/devadathanmb/diet-planner-backned.git
```

2. Build the docker image

```bash
cd diet-planner-backend && docker build -t diet-planner-backend .
```

3. Run the docker container

```bash
docker run diet-planner-backend
```

### Without docker

1. Clone the repo

```bash
git clone https://github.com/devadathanmb/diet-planner-backned.git
```

2. Navigate to project directory

```bash
cd diet-planner-backend
```

3. Create a Virtual Environment (optional but recommended)

```bash
# Create a virtual environment (replace 'venv' with your preferred name)
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate

# On macOS and Linux
source venv/bin/activate
```

4. Install required dependencies

```bash
pip install -r requirements.txt
```

5. Run the app using

```bash
python app.py
```

## Team members

1. Devadathan M B
2. Rishi Raj K
3. Asif J
4. Eldose Joy

## License

This project is licensed under the **GPL 3.0** License - see the [LICENSE](./LICENSE.md) file for details.
