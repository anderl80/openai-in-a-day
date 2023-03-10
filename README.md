# OpenAI in a day

> *In this technical workshop, you will get a comprehensive introduction to OpenAI and Azure OpenAI Studio. You will learn how to create and refine prompts for various scenarios using hands-on exercises. You will also discover how to leverage OpenAI to access and analyze your company data. Moreover, you will explore existing solution accelerators and best practices for prototyping and deploying use cases end-to-end. The workshop will end with a Q&A session and a wrap-up.*

## Agenda

### 🌅 Morning (9:00 – 12:00)

> *Fokus: Introduction and first steps*

* 📣 Intro (90min)
  * Into Workshop (15mins)
  * Intro OpenAI (30mins)
  * Azure OpenAI Studio (45mins)
* 🧑🏼‍💻 Prompt Engineering Exercises using Studio (90mins)

### 🌆 Afternoon (1:00 – 4:30)

> *Fokus: Solutions*

* Recap (15min)
* 📣 Using OpenAI to access company data (60min)
  * How to bring your own data
  * Fine-tuning and embedding
  * Solutions Accelerators
* QnA session (30min)
* 💻 Hands-on lab on two exemplay use-cases (90min)

<sup>
📣 Presentation, 🧑🏼‍💻 Hands-on lab
</sup>

-------------------

## Preparation

> *This is only required for the hands-on lab. If you are only attending the presentation, you can skip this section.*

### OpenAI subscription and deployments

Grant the participant access to the OpenAI subscription and create the required deployments.

Ideally, grant the participants access to OpenAI service be assigning the `Cognitive Service OpenAI user`. If the participant is a `Cognitive Service OpenAI contributor`, they can create the following deployments themselves.

Otherwise, create 'text-davinci-003' and 'text-embedding-ada-002' deployments (and assign the participant to the deployments).

There are two ways to authenticate (see Jupyter notebooks):
1. (Recommended) Use the Azure CLI to authenticate to Azure and OpenAI
2. Using a token (not needed if using the Azure CLI)

Get the OpenAI endpoint (and key) from the Azure portal.

### Workspace environment

Choose one of the following options to set up your environment: Codespaces, Devcontainer or bring your own environment (Anaconda). Building the environment can take a few minutes, so please start early.

#### 1️⃣ Codespaces

> 🌟 Highly recommended: *Best option if you already have a Github account. You can develop on local VSCode or in a browser window.*

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

> *If you already have a Python environment with Jupyter Notebook and the Azure CLI installed.*

Make sure you have the requirements installed in your Python environment using `pip install -r requirements.txt`.
