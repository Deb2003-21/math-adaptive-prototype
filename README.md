# Math Adaptive Prototype

A prototype for an adaptive mathematics learning system — an exploratory project that demonstrates an adaptive exercise delivery and tracking approach. This repository contains source code (under `src/`), a written project report (`report.pdf`), and a requirements file (`requirment.txt`).

Quick summary:
- Purpose: Demonstrate a prototype for adaptive math practice that adjusts to learner performance.
- Included deliverable: A technical/academic project report at `report.pdf` documenting motivation, design, implementation, and results.
- Languages / stack: See `requirment.txt` for Python dependencies (if your prototype is implemented in Python). Adjust as needed for your actual stack.

Table of contents
- Installation
- Usage
- Project structure
- How it works (high-level)
- Running & testing
- Notes & next steps
- Contributing
- License

---

## Installation

1. Clone the repository:
   git clone https://github.com/Deb2003-21/math-adaptive-prototype.git
   cd math-adaptive-prototype

2. Install dependencies:
   - The repository contains `requirment.txt` (note: filename contains a typo). If this file lists Python packages, install with:
     pip install -r requirment.txt
   - Recommended: rename `requirment.txt` → `requirements.txt` for standard tooling.

3. If the project uses a virtual environment:
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   .venv\Scripts\activate      # Windows

Adjust the installation steps to match the actual language and environment used by the prototype.

---

## Usage

- Inspect the `src/` directory for the application entry point (for example `src/main.py`, `src/app.py`, or similar). Run the prototype with the appropriate interpreter or command:
  python src/main.py

- Consult `report.pdf` for details on how the prototype was designed, expected inputs, and evaluation results.

(If your project exposes a web UI or API, add explicit run instructions and endpoint information here.)

---

## Project structure

- report.pdf — Project report describing objectives, design, implementation, and evaluation.
- requirment.txt — Dependency list (consider renaming to `requirements.txt`).
- src/ — Source code for the prototype.
- README.md — This file (overview and usage).
- (Add: tests/, data/, notebooks/ as applicable)

---

## How it works (high-level)

This prototype aims to adapt problem selection and difficulty based on learner interactions. Typical components:
- Item pool: a set of math problems classified by topic and difficulty.
- Student model: tracks student performance and estimates skill levels per topic.
- Adaptation engine: selects next items to match the estimated skill and learning goals.
- Logging & analytics: records attempts and outcomes for evaluation (described in `report.pdf`).

Refer to `report.pdf` for the concrete algorithms, data formats, and evaluation methodology used in this project.

---

## Running & testing

- Unit tests (if present) should live under `tests/`. Run with:
  pytest

- Manual testing:
  - Prepare any required data files (describe location in repo).
  - Execute the main application and perform sample runs as described in the report.

---

## Notes & next steps

- Rename `requirment.txt` → `requirements.txt` for consistency with Python tooling.
- Add a clear entrypoint in `src/` (if not present) with usage examples and sample data.
- Add a LICENSE file and CONTRIBUTING.md if you plan to share or collaborate.
- Add a short summary of how to reproduce results from the report (scripts, data, and commands).

---

## Contributing

Contributions, bug reports, and improvements are welcome. Suggested workflow:
- Fork the repo
- Create a feature branch
- Add tests (when applicable)
- Open a pull request with a clear description of changes

---

## License

Add a LICENSE file to make the project's licensing clear. If this is for coursework and you do not plan to publish, note that in the README.

---

Acknowledgements
- See `report.pdf` for full references, design decisions, and evaluation results.
