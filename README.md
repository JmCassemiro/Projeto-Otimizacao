# Projeto de Otimização

## Descrição

Este é um projeto acadêmico desenvolvido para a disciplina de Otimização. A aplicação permite resolver problemas com função objetivo e restrições definidas pelo usuário, utilizando uma interface web simples com Flask.

## Funcionalidades

- Inserção da função objetivo
- Definição de restrições (≤ ou ≥)
- Visualização dos resultados da otimização
- Análise de viabilidade após alteração de restrições

## Tecnologias Utilizadas

- Python 3
- Flask
- Jinja2
- HTML/CSS (com Bootstrap)
- Biblioteca Scypy utilizando a função Linprog

## Estrutura do Projeto

```
Projeto-Otimizacao/
│
├── app/
│   ├── templates/
│   ├── utils/
│   └── routes.py
│
├── config.py
├── run.py
├── requirements.txt
└── README.md
```


## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/Projeto-Otimizacao.git
   cd Projeto-Otimizacao
   ```

2. Crie e ative o ambiente virtual:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # No Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Inicie a aplicação:
   ```bash
   python run.py
   ```

5. Acesse pelo navegador:
   ```
   http://localhost:5000
