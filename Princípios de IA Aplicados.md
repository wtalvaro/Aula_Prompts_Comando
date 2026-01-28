# Aula: Engenharia de Prompt para Desenvolvedores

## 1. O Framework de 5 Pilares
Para um prompt ser profissional, ele deve conter:
1. **Papel:** (Ex: Especialista em Rust)
2. **Contexto:** (Ex: Criando uma API de baixa latência para o BRFrete)
3. **Dados de Entrada:** (Código, logs ou requisitos)
4. **Restrições:** (Ex: Não usar bibliotecas externas, focar em performance)
5. **Formato de Saída:** (Ex: JSON, Markdown, Código comentado)

## 2. Exemplos Práticos

### Cenário: Refatoração (Foco em Manutenibilidade)
**Prompt:** "Aja como um revisor de código sênior. Analise este método C# buscando por Code Smells. Refatore-o para reduzir a Complexidade Ciclomática e garanta que ele siga o DRY (Don't Repeat Yourself)."

### Cenário: Criação de Testes (Foco em Qualidade)
**Prompt:** "Com base na classe Java abaixo, gere uma suíte de testes unitários usando JUnit 5 e Mockito. Certifique-se de cobrir: 1. Caminho feliz; 2. Exceção de entrada nula; 3. Timeout de banco de dados."

## 3. Comparativo de Modelos
| Modelo | Ponto Forte para o Dev | Uso Ideal |
| :--- | :--- | :--- |
| **Gemini** | Janela de Contexto (1M+ tokens) | Analisar documentações inteiras. |
| **Claude** | Lógica e Código Elegante | Refatoração e Arquitetura. |
| **DeepSeek** | Velocidade e Algoritmos | Scripts, Regex e Lógica Pura. |