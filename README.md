# FastReact: REACT + FASTAPI Monorepo
This project is a mono-repo template for bootstrapping a react frontend app and a python fastapi backend app all orchestrated using yarn workspace

# Requirements
- Python 3.7 + (Pyenv is recommended for installation of Python3 and PIP3)
- Pip 3
- Node JS 16+

## Local Development Setup
- React Frontend Dependencies are managed through yarn (not NPM) as we rely on yarn workspace for managing the entire monorepo
- Python Backend Dependencies is managed through pipenv
- Entire Monorepo is managed through yarn workspace

### Step by Step Setup
1. clone the repo `git clone https://github.com/tosinamuda/fastreact`
2. change your directory to fastreact: ```cd fastreact```
3. Run ```yarn``` to install all the dependencies 
4. Run ```yarn dev``` to run a development environment
5. Run ```yarn start``` to start a production-ready environment
