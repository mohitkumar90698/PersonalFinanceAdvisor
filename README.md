# PersonalFinanceAdvisor

PersonalFinanceAdvisor is a chatbot specifically designed to assist users with personal finance-related inquiries. By feeding data about various financial topics into a large language model (LLM), this chatbot provides insightful information and advice for financial planning, budgeting, investing, and more.

## Features

- **User-friendly Interface:** Provides answers to a wide range of personal finance questions.
- **Comprehensive Repository:** Access to extensive information on financial planning, budgeting, debt management, and investing.
- **Personalized Guidance:** Offers tailored financial advice and recommendations based on user inputs and preferences.

## Installation

To get started with PersonalFinanceAdvisor, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/mohitkumar90698/PersonalFinanceAdvisor.git
    cd PersonalFinanceAdvisor
    ```

2. Install the Gaia Node:

    Run the command below:
    ```bash
    curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
    ```

3. Update the config.json file to run with a small language model:
    ```bash
    gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json
    ```

4. Start the node:
    ```bash
    gaianet start
    ```

## How to Use

1. Open your web browser and navigate to the generated link.
2. Start interacting with the chatbot by typing your personal finance-related questions.
