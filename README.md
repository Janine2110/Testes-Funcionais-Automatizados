# 🧩 Testes Funcionais Automatizados – LocalEats

Projeto desenvolvido para a disciplina de **Qualidade de Software** no curso de **ADS - Análise e Desenvolvimento de Sistemas (UniSenac-RS)**.

Este projeto tem como objetivo a automação de testes funcionais (E2E) no sistema LocalEats utilizando **Playwright + Pytest + Page Object Model (POM)**.

---

## 👥 Integrantes

- Janine Veigas Farias  
- Miguel Rubim Vencato  

---

## 📌 Objetivo

Automatizar testes funcionais do sistema LocalEats garantindo que os principais fluxos do usuário funcionem corretamente de ponta a ponta.

---

## 🚀 Tecnologias utilizadas

- Python  
- Playwright  
- Pytest  
- Page Object Model (POM)  

---

## 🧪 Fluxos testados

### 🔐 Login de usuário (Janine)
- Acesso ao sistema
- Autenticação do usuário
- Validação de login

### 🍽️ Navegação de restaurantes (Miguel)
- Acesso à lista de restaurantes
- Clique em restaurante específico
- Navegação para página de detalhes

---

## ⚙️ Execução dos testes

### Instalação de dependências

```bash
pip install -r requirements.txt
```

### Executar Testes

```bash
pytest
```

## 📊 Resultado dos testes

- Total de testes: 2  
- Testes aprovados: 2  
- Testes falharam: 0

## 🧱 Estrutura do Projeto

```bash
pages/
 ├── login_page.py
 ├── restaurantes_page.py

tests/
 ├── test_login.py
 ├── test_restaurantes.py

codegen/
 ├── codegen_login.py
 ├── codegen_restaurante.py
```

## 🧠 Boas práticas aplicadas

- Uso de Page Object Model (POM)  
- Separação entre testes e lógica de interface  
- Reutilização de código  
- Testes E2E (end-to-end)  
- Organização por fluxo funcional  

---

## 🔍 Observações

- O Codegen foi utilizado como ponto inicial para criação dos testes  
- Os testes foram refatorados para maior legibilidade e manutenção  
- Seletores foram ajustados para evitar fragilidade  
- Fluxos foram validados de ponta a ponta (usuário real)  

---

## 💡 Conclusão

A automação de testes com Playwright melhora a confiabilidade do sistema e reduz o esforço de testes manuais repetitivos, principalmente em fluxos críticos como login e navegação de restaurantes.  
