# MCP-github-test

A Flask application demonstrating best practices.

## Features

- Modular Flask application structure
- Environment-based configuration
- Unit testing setup
- HTML templates with inheritance
- Basic error handling

## Setup

1. Clone the repository:
```bash
git clone https://github.com/iFirebrand/MCP-github-test.git
cd MCP-github-test
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python run.py
```

## Testing

Run tests using pytest:
```bash
pytest
```

## Project Structure

- `app/`: Application package
  - `__init__.py`: Application factory
  - `routes.py`: Route definitions
  - `models.py`: Data models
  - `templates/`: HTML templates
- `config.py`: Configuration classes
- `run.py`: Application entry point
- `tests/`: Test package

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request