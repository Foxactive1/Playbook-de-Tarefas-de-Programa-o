# **Playbook de Tarefas de Programação**  
_InNovaIdeia Assessoria em Tecnologia ®_

Este repositório contém prompts, diretrizes e exemplos para auxiliar programadores, analistas e educadores em diversas etapas do ciclo de desenvolvimento de software, garantindo qualidade, eficiência e boas práticas.

---

## **1. Escrever Código**

**Prompt:**

Você é um programador experiente.  
Escreva um código eficiente e bem estruturado em **[INSERIR LINGUAGEM DE PROGRAMAÇÃO]** para **[REALIZAR AÇÃO]**.

- Implemente a lógica e os algoritmos necessários.
- Otimize para desempenho e legibilidade.
- Documente o código para referência futura e manutenção.

**Exemplo:**

```python
# Função para calcular fatorial
def fatorial(n):
    if n == 0 or n == 1:
        return 1
    return n * fatorial(n-1)

print(f"Fatorial de 5: {fatorial(5)}")
