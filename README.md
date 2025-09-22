# Chatbot "Sabor que Abraça" - A Essência da Vovó Joana

## Descrição do Projeto

Este repositório apresenta um **case fictício** desenvolvido para a disciplina de Processamento de Linguagem Natural, do curso de **Pós-Graduação em Inteligência Artificial do SENAI**. O projeto consiste em um chatbot que busca capturar e digitalizar a essência da "Vovó Joana", a alma por trás da confeitaria fictícia "Doces da Vovó Joana".

O objetivo é transformar suas anotações, receitas, dicas e histórias de família, contidas em arquivos de texto (.txt), em uma persona digital interativa. Utilizando técnicas de NLP, o sistema lê esses "cadernos de receita", aprende o tom de voz, o carinho e a sabedoria da Vovó, permitindo que usuários conversem com ela através de uma interface acolhedora, como se estivessem na cozinha de casa.

## Funcionalidades Mágicas da Vovó

* **Receitas e Histórias da Vovó (.txt):** O chatbot é alimentado por uma coleção de arquivos .txt que contêm as preciosas receitas da Vovó, seus "segredinhos" de cozinha e pequenas histórias que dão sabor à sua memória.
* **Traduzindo Carinho em Dados (Embeddings OpenAI):** Cada texto é processado e transformado em um "vetor de sentimento" através dos embeddings da OpenAI, capturando o significado e o afeto por trás das palavras.
* **O Caderno de Receitas Digital (Banco de Vetores FAISS):** Esses vetores são organizados em um banco de dados ultrarrápido, que funciona como um índice mágico do caderno de receitas da vovó, permitindo encontrar a resposta ou a história certa em um piscar de olhos.
* **A Voz da Vovó (Modelo gpt-4o-mini):** Com um prompt de comando cuidadosamente elaborado, o modelo **gpt-4o-mini** utiliza o caderno de receitas digital para conversar com os usuários, replicando o tom de voz carinhoso, o estilo e a sabedoria da Vovó Joana.
* **A Cozinha Virtual da Vovó (Interface Streamlit):** A interação acontece em uma interface web simples e acolhedora, projetada para ser a "cozinha virtual" da Vovó, onde todos são bem-vindos para um bate-papo e uma xícara de café.

## Ingredientes Tecnológicos

Para dar vida à Vovó, usamos os seguintes "ingredientes" tecnológicos:
* **Python:** A base da nossa receita.
* **Streamlit:** A fôrma que dá o formato da nossa "cozinha virtual".
* **OpenAI:** O "fermento mágico" que transforma texto em sentimento (embeddings).
* **FAISS:** A prateleira super organizada onde guardamos todas as memórias.
* **GPT-4o-mini:** O coração do chatbot, que dá voz e personalidade à Vovó Joana.

## Colocando o Bolo no Forno (Como Executar)

1.  **Pré-requisitos:**
    * Python 3.8 ou superior.
    * Instalar os "temperos" listados no arquivo `requirements.txt`:
        ```bash
        pip install -r requirements.txt
        ```
2.  **Preparação da Base de Dados:**
    * Organize as anotações e receitas da Vovó (.txt) na pasta designada.
3.  **Iniciando o Aplicativo:**
    * Execute o comando para abrir a "cozinha virtual":
        ```bash
        streamlit run main.py
        ```
    * Siga as instruções na tela para começar a conversar com a Vovó!

## Uso e Finalidade

> **⚠️ ATENÇÃO:** Este projeto foi desenvolvido como um **case fictício e TOTALMENTE para fins acadêmicos** no âmbito da Pós-Graduação do SENAI. **Não possui licença comercial**.
> **🚫 NÃO é permitida nenhuma forma de comercialização** ou utilização que não esteja estritamente relacionada a pesquisas e estudos acadêmicos.

## Contribuições

Sugestões de novas receitas (ou funcionalidades) são bem-vindas para fins de aprendizado. Se você deseja aprimorar a "memória" da Vovó, sinta-se à vontade para abrir issues ou enviar pull requests, sempre respeitando o propósito acadêm-ico do projeto.

## Contato

Para dúvidas, mais informações ou apenas para compartilhar uma receita de família, abra uma issue neste repositório.
