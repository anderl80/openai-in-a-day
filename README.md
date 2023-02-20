# OpenAI in a day

*This technical workshop will provide an introduction to OpenAI and an overview of Azure OpenAI Studio. Participants will be prompted to complete engineering exercises and use OpenAI to access company data. They will also learn about embedding solution accelerators and prototyping one use case from start to finish. The workshop will conclude with a Q&A and wrap-up.*

## Agenda

### 🌅 Morning (9:00 – 12:00)

> *Fokus: Introduction and first steps*

* Intro (90min)
  * 📣 Intro OpenAI (45mins)
  * 📣 Azure OpenAI Studio (45mins)
* 🧑🏼‍💻 Prompt Engineering Exercises (90mins)
  * OpenAI cookbook examples (30min)
  * Extendes examples on slides (60min)

### 🌆 Afternoon (1:00 – 4:30)

> *Fokus: Solutions*

* 📣 Using OpenAI to access company data (45min)
  * How to bring your own data
  * Fine-tuning, embedding
  * Solutions Call Center, Q&A
* Customer Solutions Insights / Best Practices (30min)
* FAQ (30min)
* 💻 Presentation of embeddings solution accelerator (30min)
* 💻 Hands-on lab on two exemplay use-cases (60min)

## Preparation (for Use Case Labs)

### OpenAI subscription and deployments

If the participant has `Azure OpenAI contributor` access, this can be during the workshop. Otherwise, if the participant is `Azure OpenAI user`, the subscription admin needs do make the deployments available upfront.

* Create 'text-davinci-003' and 'text-embedding-ada-002' deployments (and assign the participant to the deployments)

### Workspace environment

Choose one of the following options to set up your environment: Codespaces, Devcontainer or bring your own environment (Anaconda). Building the environment can take a few minutes, so please start early.

#### 1️⃣ Codespaces

> *Best option if you already have a Github account. You can develop on local VSCode or in a browser window.*

* Go to Github repository and click on `Code` button
* Edit the `credentials.env` file including OpenAI endpoint and key before starting any notebooks

#### 2️⃣ Devcontainer

> *Usually a good option if VSCode and Docker Desktop are already installed.*

* Install [Docker](https://www.docker.com/products/docker-desktop)
* Install [Visual Studio Code](https://code.visualstudio.com/)
* Install [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension
* Clone this repository
* Open the repository in Visual Studio Code
* Click on the green button in the bottom left corner of the window
* Select `Reopen in Container`
* Wait for the container to be built and started
* Edit `credentials.env` file including OpenAI endpoint and key before starting any notebooks

#### 3️⃣ Bring your own environment

> *If you already have a Python environment with Jupyter Notebook installed.*

Make sure you have the requirements installed in your Python environment using `pip install -r requirements.txt`.
