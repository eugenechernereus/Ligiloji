# Ligiloji — Personal information manager

No account. No server. No database. Offline. One self-contained HTML file with encryption.

**Ligiloji** is a lightweight, browser application for organizing passwords, links, notes, designed to keep structured collections of text notes in a simple, convenient, portable format.

The application runs directly in any web browser and does not require a server or installation.

## Features

- 📁 Organize information into sections
- 🗂️ Create categories
- 🔗 Store and manage links, passwords, notes
- 🔎 Search through stored content
- ⬆️ Export data to JSON
- ⬇️ Import data from JSON
- 💾 Save the current application and data as an HTML file
- 🔐 Optional password-protected data
- 🎨 Silver and Gold visual themes
- 🗑️ Built-in trash handling
- 📄 Self-contained single-file architecture
- 🌐 Runs directly in a modern browser

## Getting Started

### 1. Download

Download `Ligiloji.html` from this repository, or start working right on the page [Ligiloji](https://eugenechernereus.github.io/Ligiloji/Ligiloji.html)

### 2. Open

Open the file directly in a web browser.

### 3. Use

The architecture has a nested structure.

Create sections, categories add notes.

## Search

The search works by name and login within the selected category.

To use the global search, select "Catalog".

## Data

The application can save the current state as an HTML file.

Existing files cannot be changed from inside the application.

To save the encrypted data, enter the password when saving and a new name.

The encryption password must be entered every time you save. You can also change your password in the same way.

Data can be exported to JSON and imported back into Ligiloji.

**Be careful, the JSON format is not encrypted and is used to transfer between versions of the program or transform into other data formats.**

To create a new database, it is enough to clear all, add new data and save a new file.

Although the number of notes is not technically limited, it is not recommended to store more than 5,000 entries in a single file.

## Autobackup

When any changes are made, the browser temporarily saves them in ‘lockalstorage’. If the page is accidentally closed, the changes will be saved and can be restored the next time the application is opened (provided that the browser data has not been cleared).

Encrypted data also remains encrypted in the temporary storage.

When the file is saved, the temporary data is automatically cleared.

> The reliability of temporary saving depends on the settings of a specific browser and may be unstable.

**In the new versions, the autobackup has been replaced with manual saving via the “Temp save” button.**

## Deleting elements

When a section or category is deleted, it is removed along with all its contents, and there is no way to restore it.

When a note is deleted within a category, it is moved to the automatically created “Trash” category.

From the trash, the entry is restored to its original category.

To clear the trash, you need to delete it completely.

***

## Privacy

Users should nevertheless understand the security properties of their browser and their local files before storing sensitive information.

Password protection should not be interpreted as a guarantee of protection against all forms of access to the HTML file or its contents.

## Project Status

Ligiloji is an actively developed project.

The current implementation is an early-stage release and its architecture, interface and functionality may change as development continues.

## Versioning

Released versions are identified using Git tags following semantic versioning.

Example:

```text
v0.1.1
v0.1.2
```

The repository history is the authoritative source for development changes.

The single-file architecture is intentional at the current stage of development.

The project may be modularized into separate HTML, CSS and JavaScript files in a future version.

## Contributing

Ligiloji is currently maintained as an author-controlled project.

Public visibility of this repository does not grant permission to modify, redistribute or commercially exploit the source code.

If you have a bug report, suggestion or feature idea, you may open a GitHub Issue.

Permission to contribute code or other material to the project may be granted separately by the copyright holder.

## License

The source code is publicly visible on GitHub, but it is not released under an open-source license.

See LICENSE for the full terms.

## Copyright

Ligiloji is proprietary software.

Ligiloji, its source code, original interface, documentation and original project materials are protected by applicable copyright laws.

Copyright © 2026 Eugene Chernereus.

All rights reserved.

## Contact

For licensing, commercial use, collaboration or other permissions, please contact the copyright holder through the GitHub repository.


