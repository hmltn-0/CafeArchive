# NCategory Cafe Archiver

## Description

NCategory Cafe Archiver is a tool designed to periodically crawl and archive the [NCategory Cafe website](https://golem.ph.utexas.edu/category/). Its primary purpose is to preserve the content as a backup, ensuring that the information remains accessible even if the original site becomes unavailable. This can be considered a mirror of the NCategory Cafe website, providing a reliable copy of the online content.

For more information, refer to the site configuration in `config.json`.


## Installation

1. Clone the repository:
```sh
git clone https://github.com/hmltn-0/ncafe-archiver.git
cd ncafe-archiver
```

2. Create and activate a virtual environment:
```sh
python3 -m venv venv
source venv/bin/activate
```

3. Install the required packages:
```sh
pip install -r requirements.txt
```

4. (Optional) Run tests to ensure the setup is correct:
```sh
pytest
```

## Usage

## Contributing

If you are interested in contributing, please check our [Issues](https://github.com/hmltn-0/ncafe-archiver/issues) for tasks and bugs that need assistance. You can also check out our [GitHub Projects](https://github.com/hmltn-0/ncafe-archiver/projects) to see an overview of ongoing development.

We use different branches for various development efforts. Here are the main branches and their purposes:

- `main`: The stable version of the project.
- `develop`: The development branch where the latest features and bug fixes are integrated.
- `feature/*`: Feature branches for new features (e.g., `feature/readme-update`).
- `bugfix/*`: Bug fix branches for resolving issues (e.g., `bugfix/issue-123`).

## License
