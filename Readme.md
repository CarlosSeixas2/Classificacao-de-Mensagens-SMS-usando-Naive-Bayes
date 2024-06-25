# Classificação de Mensagens SMS usando Naive Bayes

Este projeto demonstra a aplicação do algoritmo Naive Bayes para classificar mensagens SMS como spam ou não spam (ham). Utilizamos o conjunto de dados "SMSSpamCollection" disponível no kaggle, que contém mensagens rotuladas como spam e não spam.

## Conteúdo

1. [Requisitos](#requisitos)
2. [Instalação](#instalação)
3. [Estrutura do Projeto](#estrutura-do-projeto)
4. [Contribuição](#contribuição)
5. [Licença](#licença)

---

## Requisitos

- Python 3
- Bibliotecas Python: pandas, numpy, scikit-learn, nltk, seaborn, matplotlib

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/classificacao-sms-naive-bayes.git
   cd classificacao-sms-naive-bayes
   ```
   
2. **Crie e ative um ambiente virtual (recomendado):**

    ```bash
    python -m venv env
    source env/bin/activate  # No Windows use `env\Scripts\activate`
    ```
    
3. **Instale as dependências:**
    
    ```bash
    pip install -r requirements.txt
    ```

## Estrutura do Projeto
 - `data/` : Contém o conjunto de dados "SMSSpamCollection".
 - `main.ipynb`: Script com toda a parte de  pré-processar os dados, treinar e avaliar o modelo.
 - `requirements.txt`: Lista de bibliotecas Python necessárias para o projeto.
 - `README.md`: Este arquivo README com informações sobre o projeto.

## Contribuição
Contribuições são bem-vindas! Para sugestões, melhorias ou correções, abra um problema (issue) ou envie um pull request diretamente para o repositório.

## Licença
Este projeto está licenciado sob a MIT License.