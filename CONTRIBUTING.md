# Contribution Guidelines

## Project
University Academic Services Portal — Java Swing

## 1. Branching
Create a feature branch from the latest `main` branch before making changes.

Use these naming conventions:
- `feature/course-registration`
- `feature/fee-payment`
- `feature/examination-results`
- `feature/hostel-applications`
- `feature/library-services`
- `fix/bug-description`

## 2. Coding standards
- Use meaningful Java class, method, and variable names.
- Follow standard Java naming conventions.
- Implement each academic service as a separate panel.
- Use CardLayout to switch between service panels within the main window.
- Validate inputs and handle errors appropriately.
- Keep navigation logic separate from individual service logic.

## 3. Commits
Write clear commit messages describing the change, for example:
- `feat: add course registration panel`
- `fix: validate fee payment input`
- `test: verify library panel navigation`

## 4. Pull requests
- Open a pull request into `main` for each feature or fix.
- Describe the change and link the related Jira issue.
- Request review from the appropriate maintainer.
- Address review comments and resolve conversations.
- Ensure required checks pass before merging.

## 5. Security
Never commit real student records, passwords, access tokens, or sensitive payment information.

## 6. Testing
Test the affected service panel and confirm that navigation between all five panels continues to work.

## 7. Merging
Merge only after the required reviews and checks have passed.
