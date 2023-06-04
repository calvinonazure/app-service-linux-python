## App Service Linux Python

### Prerequisites

The following prerequisites are required to use this application. Please ensure that you have them all installed locally.

- [Azure Developer CLI](https://aka.ms/azd-install)
- [Python 3.8+](https://www.python.org/downloads/)

### Quick start

To learn how to get started with any template, follow the steps in [this quickstart](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/get-started?tabs=localinstall&pivots=programming-language-python) 

This quickstart will show you how to authenticate on Azure, initialize using a template, provision infrastructure and deploy code on Azure via the following commands:

```bash
azd auth login

azd init --template calvinonazure/app-service-linux-python

azd up
```