# Exemplos de Prompts Profissionais para Devs

## 1. Refatoração de Código (Foco: Manutenibilidade)
**Modelo:** Claude 3.5 / Gemini
**Prompt:**
"Aja como um revisor de código sênior. Analise o método abaixo e aplique as seguintes refatorações:
1. Extração de método para reduzir a complexidade ciclomática.
2. Substituição de condicionais aninhadas por 'Guard Clauses'.
3. Renomeação de variáveis para seguir a convenção da linguagem.
Linguagem: [Inserir Linguagem]"

## 2. Debugging de Erros Obscuros
**Modelo:** Gemini / DeepSeek
**Prompt:**
"Contexto: Estou recebendo o erro [Colar Erro] ao executar o comando [Comando] no meu ambiente AlmaLinux 10.
Tarefa: Atue como especialista em Linux e DevOps. Diagnostique a causa raiz considerando permissões de kernel e bibliotecas compartilhadas. Forneça o comando exato para correção."

## 3. Geração de Testes Unitários
**Modelo:** Qualquer
**Prompt:**
"Atue como um engenheiro de QA. Gere uma suite de testes unitários para a classe anexa. 
Cobertura mínima: 90%. 
Inclua: Casos de borda (edge cases), entradas nulas e testes de exceção esperada.
Framework: [Inserir Framework, ex: JUnit, xUnit, PyTest]"