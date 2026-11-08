# DevEx: A Software Development Work Simulation Platform
You have been appointed as a Junior Developer at a Startup Company! DevEx is a gamified software development work simulation platform designed to bridge the gap between the academe and tech industry by allowing aspiring software developers to experience simulated workplace scenarios related to their field in a risk-free environment.

## Authors
1. Arquillano, Izeah D.
2. Esquejo, Roxane K-Anne D.
3. Narte, Ma. Victoria C.
4. Remolacio, Alexandra Geane M.  

## Key Features  
* **Simulated Workplace Scenarios:** Catalog of scenarios with company contexts, project requirements, task assignments, and descriptions.
* **In-Browser Coding:** Much like Leetcode. For now, it only integrates C#/.NET as it is part of our course learnings.
* **Simulated Team Collaboration:** Scripted events from Project Manager, Senior Developer, and QA Tester personas, status report posting, and simulated pull request code reviews.
* **Task Evaluation & Feedback:** Automated grading against test results, correctness, code quality checks, scoring, and revision/resubmission history.
* **Learning Progress:** Dashboards summarizing completed/in-progress simulations, skill performance metrics, and completion summaries.
  
## Branch Structure
* `main`: Production-ready stable release.
* `dev`: Integration branch for ongoing sprint development.
* `feature/<initials>-<short-description>`: Task and user story branches.

## Getting Started
1. **Clone the repository:**
```bash
   git clone https://github.com/your-username/devex.git
   cd devex
   ```

2. **Checkout the development branch:**
```bash
   git checkout dev
   ```

3. **Restore .NET dependencies & build:**
```bash
   dotnet restore
   dotnet build
   ```

4. **Run tests:**
```bash
   dotnet test
   ```
