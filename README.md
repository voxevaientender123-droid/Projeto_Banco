# 🏦 Simulador Banco FEVP

📖 **Visão geral** 
 
O **Simulador Banco FEVP** é um protótipo de aplicativo bancário em Python que permite ao usuário criar contas, realizar operações financeiras e consultar extratos, com segurança integrada.  
O objetivo é demonstrar conceitos de **gerenciamento financeiro**, **autenticação**, **validação de entradas** e boas práticas de segurança em um contexto controlado.

Você pode ver o protótipo visual aqui:  
[Protótipo no Canva – Simulador Banco FEVP](https://facsenacpe-tech.my.canva.site/banco-fevp4)

---

## 🔐 Funcionalidades principais

- Criação de conta com dados iniciais (nome do titular, senha)  
- Login e autenticação do usuário  
- Consulta de saldo  
- Consulta de extrato (histórico de operações)  
- Depósito  
- Saque  
- Transferência  
- Pagamento de contas/boletos 
- Proteções básicas de segurança: validação de campos, verificação de saldo, autenticação de senha

---

## 🏗️ Arquitetura e tecnologias utilizadas

- Linguagem de programação: **Python**  
- Interface / protótipo visual: **Canva**  
- Controle de versão: **Git / GitHub**  
- Boas práticas de segurança: validação de entrada, checagem de senhas, tratamento de exceções  
- Dados armazenados **em memória**, sem banco de dados externo  

---

## Requisitos Funcionais (RF)

| Código | Descrição |
|--------|------------|
| **RF01** | Criar conta bancária, solicitando nome do titular e senha. |
| **RF02** | Senha com letras e números, mínimo 6 caracteres. |
| **RF03** | Gerar automaticamente um número de conta único. |
| **RF04** | Login por número de conta e senha. |
| **RF05** | Depositar valores em contas existentes. |
| **RF06** | Sacar valores, se houver saldo suficiente. |
| **RF07** | Transferir valores entre contas cadastradas. |
| **RF08** | Exibir saldo atualizado após cada operação. |
| **RF09** | Registrar todas as operações em histórico de transações. |
| **RF10** | Consultar histórico de transações. |
| **RF11** | Exibir mensagens de erro claras em caso de dados inválidos, saldo insuficiente ou autenticação incorreta. |
| **RF12** | Pagar contas ou boletos, solicitando senha e verificando saldo suficiente. |
| **RF13** | Encerrar a sessão (logout) de forma segura. |

---

## Requisitos Não Funcionais (RNF)

| Código | Descrição |
|--------|------------|
| **RNF01** | Desenvolvido exclusivamente em **Python**. |
| **RNF02** | Interface **via terminal**. |
| **RNF03** | Tempo de resposta rápido |
| **RNF04** | Dados mantidos **em memória**, sem uso de arquivos ou banco de dados externo. |
| **RNF05** | Senhas armazenadas com **hash SHA-256**. |
| **RNF06** | Sistema **intuitivo e fácil de usar**, mensagens claras no terminal. |
| **RNF07** | Compatível com **Python 3.8 ou superior**. |
| **RNF08** | Validação de entradas para impedir dados inválidos ou negativos. |
| **RNF09** | Código legível, comentado e com **docstrings**. |

---

⚙️ Como Executar





**** FALTA ESTE TRECHO ****





💡 Requisitos: Python 3.8 ou superior

🧠 Aprendizados Envolvidos
Estrutura de dados: listas e dicionários

Funções

Tratamento de erros e validação de entradas

Simulação de fluxo bancário realista

🚀 Limitações e Melhorias Possíveis
Limitações atuais
Dados em memória: todas as contas e transações são perdidas ao fechar o programa.

Interface limitada: apenas via terminal;

Segurança básica;

Validação limitada: apenas campos básicos;

Melhorias possíveis
Persistência de dados com SQLite, MySQL ou arquivos JSON.

Criar interface gráfica ou versão web.

Implementar autenticação multifator.

Melhorar validação de entradas (CPF válido, limites de depósito/saque).

Adicionar relatórios e gráficos de movimentações.

Permitir categorias de pagamento e resumo mensal.

👨‍💻 Autores

Eduardo Henrique 
Felipe Constantino
José Pedro
José Vicenth

📚 Projeto educacional — SENAC PE
<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>
