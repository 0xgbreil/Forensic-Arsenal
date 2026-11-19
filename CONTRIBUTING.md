# Contributing to Forensic Arsenal

Thanks for helping keep this directory accurate and useful.

## What belongs here

- Reputable, widely used, actively maintained DFIR tools.
- Tools with an **official** website, repository, or verified download page.
- Tools that fit an existing category. Do not create a category for a single tool unless several more are planned.

## What does not belong here

- Cracked, pirated, or unverified download mirrors.
- Duplicate entries (a tool lives in one primary category).
- Tools with no clear forensic or incident response use.

## How to add a tool

1. Fork the repository and edit `README.md`.
2. Add one row to the correct table, keeping the existing column order:

   ```markdown
   | Tool | Description | Platform | Type | Link |
   |------|-------------|----------|------|------|
   | ToolName | One concise sentence on what it does. | Windows / Linux | CLI | [Official](https://example.com) |
   ```

3. Use only facts you have confirmed from the official source (supported platforms, interface type). If you are unsure, leave it out rather than guess.
4. Label the link `Official`, `GitHub`, or `Download`. If the link is third-party, say so in the PR description.
5. Open a pull request titled `Add <ToolName> to <Category>` and confirm the link works.

## Reporting broken links or suggesting tools

Use the issue forms: **Report a broken link** or **Suggest a new tool**.

## Style

- One sentence per description, no marketing language.
- Keep alphabetical or logical order within a table where practical.
- Do not claim a tool is free, open source, or maintained unless the official source says so.
