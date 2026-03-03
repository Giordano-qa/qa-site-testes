# 📋 Casos de Teste – Validação de Formulário

---

## ✅ CT-01 – Validação de Campo Obrigatório

**Objetivo:**  
Verificar se o sistema impede o envio do formulário com campo obrigatório vazio.

**Pré-condição:**  
Usuário acessando a página de formulário.

**Passos:**
1. Acessar a página do formulário.
2. Deixar o campo "Nome" vazio.
3. Clicar no botão "Enviar".

**Resultado Esperado:**  
O sistema deve exibir mensagem informando que o campo é obrigatório e impedir o envio.

---

## ✅ CT-02 – Validação de E-mail Inválido

**Objetivo:**  
Validar comportamento do sistema ao inserir e-mail em formato incorreto.

**Passos:**
1. Inserir "teste@teste" no campo de e-mail.
2. Clicar em "Enviar".

**Resultado Esperado:**  
O sistema deve exibir mensagem de erro indicando formato inválido.

---

## ✅ CT-03 – Fluxo de Navegação Entre Páginas

**Objetivo:**  
Validar se o redirecionamento entre páginas funciona corretamente.

**Passos:**
1. Clicar no botão "Sobre".
2. Verificar se a página correspondente é carregada.

**Resultado Esperado:**  
O usuário deve ser direcionado para a página correta sem erros.
