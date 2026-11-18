# Contributing to Bello

Thank you for wanting to contribute to Bello! You can help by fixing bugs, adding tests, improving documentation, or adding new features.

## Before You Start

- Check the [existing issues](https://github.com/Makson179/Bello/issues) before creating a new one.
- If you want to make a big change, open an issue first and discuss your idea.
- If you find a security problem, report it privately using [SECURITY.md](./SECURITY.md). Do not report it publicly.

## Setting Up the Project

Bello requires Python 3.11 or newer.

Follow these steps to set up the project:

```bash
git clone https://github.com/Makson179/Bello.git
cd Bello

python -m venv .venv

# Activate the virtual environment, then run:
python -m pip install -e ".[test]"

# Run tests
python -m pytest -q
```

Run tests while working on your changes. Before submitting a pull request, run all tests.

The project tests run on Python 3.11–3.14 and support Linux, macOS, and Windows.

## Pull Requests

Keep your changes simple and focused. Explain what you changed and why.

Please follow these guidelines:

- Add or update tests when fixing bugs or changing features.
- Update documentation if you change commands, settings, or workflows.
- Follow the existing code style.
- Avoid making unrelated changes.
- Mention any changes that affect security, permissions, sandboxing, workspace isolation, or recovery.
- Add tests for important security-related changes.
- Never include passwords, private information, or secrets in your code, logs, screenshots, or examples.

## Contributor License Agreement (CLA)

All contributors must sign the project's [CLA](./CLA.md).

When you open your first pull request, a bot will ask you to sign it. You only need to sign it once.

Thank you for helping make Bello better!
