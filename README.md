This repository contains a README file sample for Daytona Samples and the MIT License.

It can be used as a template to create sample repositories that can be added into [Daytona](https://github.com/daytonaio/daytona).

Once you finish your sample and it gets merged, you can open a PR in the Daytona repo and submit the sample into the [index file](https://github.com/daytonaio/daytona/blob/main/hack/samples/index.json).

# Sample <Python/FastAPI>

- A sample of a FastAPI application using PDM and Daytona

- Generated from [copier-pdm](https://github.com/pawamoy/copier-pdm)

- Check out [Copier PDM Documentation](https://pawamoy.github.io/copier-pdm/) for more usage details

---

## 🚀 Getting Started  

### Open Using Daytona  

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).  
2. **Create the Workspace**:  

   ```bash  
   daytona create https://github.com/JackTheMico/copier-pdm-fastapi 
   ```  

3. **Open the IDE**:

   This is optional, the create command will automatically open the VSCode IDE.

   ```bash
   daytona code copier-pdm-fastapi
   ```

4. **Start the FastAPI with reload enabled**:  

   You will need to wait the pyenv and pdm finish installing before the below command.
   ![image](https://github.com/user-attachments/assets/503bcf3b-1cf8-4b1b-ac60-3610d3d5f29f)


   ```bash  
   pdm run make devstart
   ```  

---

## ✨ Features  

- Fast build your FastAPI application using PDM and Daytona
- Pre-configured VSCode IDE and extensions.
- Support for Insiders versions of projects (e.g. see [@pawamoy's insiders](https://pawamoy.github.io/insiders/))
- [PDM]() setup, with pre-defined pyproject.toml
- Documentation built with MkDocs (Material theme and "autodoc" mkdocstrings plugin)
- Pre-configured tools for code formatting, quality analysis and testing:
  - black,
  - blacken-docs,
  - ruff,
  - mypy,
  - safety
- Tests run with pytest and plugins, with coverage support
- Cross-platform tasks with duty
- Support for GitHub workflows
- Python 3.8 or above
- Auto-generated CHANGELOG.md from git commits (using Angular message style)
- All licenses from choosealicense.com
- Makefile for convenience
