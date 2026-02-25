# Liptis

AL extension project for Microsoft Dynamics 365 Business Central.

## Cursor Cloud specific instructions

### Project State

This is a freshly initialized repository with no source code. It contains only a `README.md` and a `.gitignore` configured for AL (Application Language) projects.

### Tech Stack

- **Language:** AL (Application Language) for Dynamics 365 Business Central
- **Runtime:** Microsoft Dynamics 365 Business Central (Docker container or cloud sandbox)

### Development Notes

- AL projects are typically developed in VS Code with the **AL Language** extension.
- Compilation and deployment require a Business Central server (Docker container via `bccontainerhelper` or a cloud sandbox).
- There are currently no dependencies to install, no build scripts, and no automated tests.
- The `.gitignore` is pre-configured to exclude AL build artifacts (`.alcache/`, `.alpackages/`, `*.app`, etc.).
