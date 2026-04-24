This repository is for Spencer Marcu, an American singer-songwriter. Do not assume the presence of a Node.js application, Azure Web Apps deployment, or npm-based build/test scripts unless the corresponding files are present in the repository.

## Repository Structure
- `README.md` – Project overview and general documentation
- `.github/` – Repository automation and Copilot-related configuration

## Development Guidelines

### Tech Stack
- Determine the tech stack from the files actually present in the repository
- Do not infer runtimes, frameworks, or deployment targets that are not checked in

### Build & Test
- Only suggest build, test, or deployment commands when the necessary project files and scripts exist
- If no build or test configuration is present, say so explicitly instead of assuming standard commands

### Coding Conventions
- Follow the conventions used by the files already in the repository
- Keep changes minimal and scoped to the requested task
- Document any new scripts, workflows, or setup steps clearly when they are added

### GitHub Actions
- Review workflow files before making assumptions about CI/CD behavior
- If a workflow references missing application files or unsupported steps, update the documentation to match the repository contents

## Notes for Copilot
- Base recommendations on the files that actually exist in the repository
- Prefer small, focused pull requests
- Update `README.md` and these instructions when setup or repository structure changes
