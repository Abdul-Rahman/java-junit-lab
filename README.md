# Java JUnit Lab for GitHub Codespaces
# Asst. Prof. Engr. Abdul Rahman Mahmood
This repository demonstrates a simple Software Quality Engineering lab using **JUnit 5** and **JaCoCo** coverage in GitHub Codespaces.

## How to Run

1. Open in GitHub Codespaces (Code → Codespaces → Create codespace on main)
2. In the terminal run:
   ```bash
   mvn -q test
   ```
3. Fix the rounding bug in `Calculator.multiply()` and rerun tests.
4. Run coverage:
   ```bash
   mvn -q test jacoco:report
   ```
5. Open `target/site/jacoco/index.html` to view the coverage report.
