## Contributing to GPT Codex-Obscura

Thank you for your interest in contributing to **GPT Codex-Obscura**.
This project is structured to maintain high quality, consistency, and long-term sustainability.

Please follow the guidelines below to ensure smooth collaboration.


---


## 📌 Code of Conduct
All contributors are expected to follow the [Contributor Covenant Code of Conduct] (https://www.contributor-covenant.org/).  
Be respectful, constructive, and collaborative.


---


## 🚀 Getting Started

1. **Fork the Repository**  
   - Click **Fork** at the top-right of this repo to create your own copy.

2. **Clone Your Fork**
   git clone https://github.com/SvilarT/GPT-Codex-Obscura.git
   cd GPT-Codex-Obscura

3. **Create a Branch**
   git checkout -b feature/your-feature-name


---


## 📂 Repository Structure

docs/ → Documentation source (Markdown files, organized by Volumes/Annexes)

docs/assets/ → Images, logos, stylesheets

.github/workflows/ → CI/CD pipelines (lint, build, release)

mkdocs.yml → Site configuration

Root files: README.md, CONTRIBUTING.md, LICENSE, SECURITY.md


---


## ✍️ Writing Guidelines

* Write content in Markdown (.md).

* Use clear headings and consistent formatting.

* Follow the quad-layer model (Recruit → Operator → Blacklayer → Specter) where applicable.

* Keep language professional, concise, and accurate.


---


## ✅ Submitting Changes

1. Ensure your branch is up-to-date with main:

git pull origin main


2. Commit with descriptive messages:

git commit -m "Add: Volume II draft (Operator layer)"


3. Push your branch:

git push origin feature/your-feature-name


4. Open a Pull Request:

* Provide a clear description of changes.

* Link related issues using Closes #issue_number.


---


## 🔍 Testing & Validation

* CI must pass before merge (Markdown lint, build tests).

* Validate MkDocs site builds without errors:

mkdocs serve

* For PDF release testing:

make pdf


---


## 🏷️ Issues & Labels

* bug → Defects in docs or build pipelines

* enhancement → Feature requests or improvements

* documentation → Content additions or corrections

* discussion → Open questions or proposals


---


## 🤝 Community Standards

* Be open to feedback.

* Document your assumptions.

* Write contributions as if they will be read years from now.


---


Thank you for helping strengthen GPT Codex-Obscura.
Your contributions ensure the Codex remains a living, evolving artifact.