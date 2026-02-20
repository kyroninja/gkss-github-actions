# Contributing

Thanks for taking the time to contribute! This is a demo project, but contributions are welcome.

## Getting started

```bash
git clone https://github.com/kyroninja/gkss-github-actions
cd demo-flask-site
python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
pip install pytest
python app.py                 # Visit http://localhost:5000
```

## Making changes

1. **Fork** the repo and create a branch from `main`
2. Branch naming: `fix/short-description` or `feat/short-description`
3. Make your changes
4. Run tests — they must pass before opening a PR
5. Open a pull request using the provided template

## Running tests

```bash
pytest test_app.py -v
```

## Reporting bugs

Open an issue using the **Bug report** template. Include steps to reproduce and any relevant logs.

## Suggesting features

Open an issue using the **Feature request** template.

## Code style

- Follow [PEP 8](https://peps.python.org/pep-0008/)
- Keep functions small and focused
- Add a test if you're adding behaviour

## Questions?

Open a blank issue and ask — no question is too small.
