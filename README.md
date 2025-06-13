
# Kita Manager

A Flask web application for managing static blogs powered by Zola and GitHub Pages.

## Features

- GitHub authentication using personal access tokens
- Create new blogs from a template repository
- Manage blog configuration (config.toml)
- Create, edit, and delete blog posts
- Automatic GitHub Actions setup for deployment
- Support for blog customization including:
  - Site metadata
  - Author profile
  - Social links
  - Navigation menu
  - Footer information
  - Syntax highlighting
  - Math and diagram support
  - Comments system

## Requirements

- Python 3.6+
- Flask
- requests
- toml
- PyNaCl (optional, for GitHub Actions secret setup)

## Setup

1. Clone the repository
```bash
git clone https://github.com/Daradege/kitamanager.git
cd kitamanager
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the application
```bash
python -m flask run --host=0.0.0.0 --port=5000
```

4. Access the application at `http://localhost:5000`

## Usage

1. Generate a GitHub personal access token with repo scope
2. Log in to the application using your token
3. Create a new blog or select an existing repository
4. Manage your blog content through the web interface

## License

MIT License
