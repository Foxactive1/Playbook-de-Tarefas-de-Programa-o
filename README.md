Playbook de Tarefas de Programação

InNovaIdeia Assessoria em Tecnologia ®

Este repositório contém prompts, diretrizes e exemplos para auxiliar programadores, analistas e educadores em diversas etapas do ciclo de desenvolvimento de software, garantindo qualidade, eficiência e boas práticas.


---

1. Escrever Código

Prompt:

Você é um programador experiente.
Escreva um código eficiente e bem estruturado em [INSERIR LINGUAGEM DE PROGRAMAÇÃO] para [REALIZAR AÇÃO].

Implemente a lógica e os algoritmos necessários.

Otimize para desempenho e legibilidade.

Documente o código para referência futura e manutenção.


Exemplo:

# Função para calcular fatorial
def fatorial(n):
    if n == 0 or n == 1:
        return 1
    return n * fatorial(n-1)

print(f"Fatorial de 5: {fatorial(5)}")


---

2. Depurar Código

Prompt:

Você é um especialista em depuração com mais de 20 anos de experiência.
Analise o [TRECHO DE CÓDIGO] fornecido para identificar e corrigir um [ERRO] específico.

Percorra o código para diagnosticar o problema.

Proponha uma solução para corrigir o erro.

Sugira otimizações para desempenho e legibilidade.


Exemplo (erro corrigido):

# Antes: erro de divisão por zero
def divisao(a, b):
    return a / b

# Correção:
def divisao(a, b):
    if b == 0:
        return "Erro: divisão por zero!"
    return a / b

print(divisao(10, 0))


---

3. Revisão de Código

Prompt:

Você é um especialista em revisão de código.
Realize uma revisão abrangente do [TRECHO DE CÓDIGO] fornecido.

Avalie o código quanto à eficiência, legibilidade e manutenibilidade.

Identifique bugs, problemas de segurança ou gargalos de desempenho.

Ofereça sugestões práticas para melhoria.


Exemplo:

# Código original:
for i in range(len(lista)):
    print(lista[i])

# Sugestão após revisão:
for item in lista:
    print(item)  # Mais legível e pythonico


---

4. Explicar Código

Prompt:

Você é um programador e educador experiente.
Explique o [TRECHO DE CÓDIGO] de forma que todos possam entender.

Detalhe a funcionalidade do código.

Destaque seus casos de uso e melhores práticas.

Sugira possíveis otimizações, se aplicável.


Exemplo:

def soma(a, b):
    return a + b

Explicação:

