## 🔗 Acesse o projeto
[Repositório no GitHub](https://github.com/danieldiaspavan-creator/qa-login-project)

# 🧪 Projeto de Testes - Funcionalidade de Login

## 📌 Objetivo
Este projeto tem como objetivo validar a qualidade da funcionalidade de login de uma aplicação, por meio da criação e execução de testes manuais e validação de cenários positivos e negativos, garantindo que o sistema atenda aos requisitos funcionais e às regras de negócio.

---

## 🎯 Escopo dos Testes

A funcionalidade testada contempla:

- Autenticação de usuário
- Validação de credenciais
- Tratamento de erros
- Mensagens exibidas ao usuário

---

## 🧪 Tipos de Teste Aplicados

- Testes Funcionais
- Testes Exploratórios
- Testes Negativos
- Testes de Regressão (conceitual)

---

## 📋 Cenários de Teste

| ID   | Cenário                          | Descrição |
|------|----------------------------------|----------|
| CT01 | Login com dados válidos          | Usuário realiza login com credenciais corretas |
| CT02 | Login com senha inválida         | Usuário informa senha incorreta |
| CT03 | Login com usuário inexistente    | Usuário não cadastrado tenta acessar |
| CT04 | Campos obrigatórios não preenchidos | Tentativa de login sem preencher campos |
| CT05 | Validação de mensagens de erro   | Sistema retorna mensagens adequadas |

---

## 🧾 Casos de Teste (Exemplo)

### CT01 - Login com sucesso

**Pré-condição:** Usuário previamente cadastrado

**Passos:**
1. Acessar a tela de login  
2. Informar usuário válido  
3. Informar senha válida  
4. Clicar em "Entrar"  

**Resultado Esperado:**  
Usuário autenticado com sucesso e redirecionado para a área logada do sistema.

---

### CT02 - Senha inválida

**Passos:**
1. Acessar a tela de login  
2. Informar usuário válido  
3. Informar senha incorreta  
4. Clicar em "Entrar"  

**Resultado Esperado:**  
Sistema deve exibir mensagem de erro informando credenciais inválidas.

---

## 🔗 Testes de API (se aplicável)

Validação de endpoints relacionados à autenticação:

- Verificação de status HTTP (200, 401)
- Validação de payload de resposta
- Testes de sucesso e falha

Ferramenta utilizada:
- Postman

---

## ⚙️ Automação de Testes (em evolução)

Este projeto encontra-se em evolução para automação de testes utilizando:

- Playwright

Objetivo:
- Automatizar cenários críticos (ex: login válido)
- Garantir regressão mais rápida e confiável

---

## 🧠 Estratégia de Teste

A estratégia adotada prioriza:

- Cenários críticos de negócio (login é funcionalidade essencial)
- Testes negativos para garantir robustez do sistema
- Validação de feedback ao usuário (mensagens de erro)
- Cobertura dos principais fluxos de autenticação

---

## 🛠️ Ferramentas Utilizadas

- Postman (testes de API)
- Playwright (automação - em evolução)
- Git/GitHub (versionamento)
- Documentação em Markdown

---

## 🚀 Possíveis Melhorias

- Expansão da cobertura de testes
- Implementação completa da automação
- Integração com pipeline CI/CD
- Inclusão de testes de segurança (ex: autenticação)

---

## 👨‍💻 Autor

Daniel Pavan  
QA Analyst em evolução com foco em qualidade de software, automação de testes e melhoria contínua de processos.
