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


---

## 2. Depurar Código

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

Código original:

for i in range(len(lista)):
    print(lista[i])

Sugestão após revisão:

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

Esta função chamada soma recebe dois parâmetros (a e b) e retorna a soma deles.
Caso de uso: somar dois números inteiros ou floats.
Melhoria: adicionar type hints para clareza.

def soma(a: float, b: float) -> float:
    return a + b


---

5. Refatorar Código

Prompt:

Você é um especialista em programação com foco em refatoração.
Refatore o [TRECHO DE CÓDIGO] fornecido para melhorar eficiência, legibilidade e manutenibilidade sem alterar sua funcionalidade.

Simplifique lógicas complexas.

Remova código redundante.

Documente o código refatorado para maior clareza.


Exemplo:

Antes:

if idade >= 18:
    autorizado = True
else:
    autorizado = False

Depois (refatorado):

autorizado = idade >= 18


---

6. Criar Documentação

Prompt:

Você é um especialista em documentação para programadores.
Prepare uma documentação completa para o [CÓDIGO] fornecido.

Comece explicando a finalidade principal do código.

Explique cada parte do código separadamente.

Inclua exemplos e perguntas frequentes para ajudar os usuários.


Exemplo de documentação:

### Função `soma`

Esta função realiza a soma de dois números.

**Parâmetros:**
- `a` (float): primeiro número.
- `b` (float): segundo número.

**Retorno:**
- (float): soma de `a` + `b`.

**Exemplo de uso:**

```python
resultado = soma(10, 5)
print(resultado)  # Saída: 15

FAQ:

Posso passar strings? Não, apenas números inteiros ou floats.


---

## **7. Escrever Testes**

**Prompt:**

Você é um especialista em testes de software.  
Projete e escreva testes abrangentes para um **[TRECHO DE CÓDIGO]** específico usando **[FRAMEWORK DE TESTE]**.

- Delineie uma estratégia de teste que cubra casos extremos.
- Implemente testes unitários, de integração e de ponta a ponta conforme necessário.
- Garanta que todos os testes sejam completos e eficientes.

**Exemplo (Pytest):**

```python
def soma(a, b):
    return a + b

def test_soma():
    assert soma(2, 3) == 5
    assert soma(-1, 1) == 0
    assert soma(0, 0) == 0
    assert soma(1.5, 2.5) == 4.0


---

Sobre

Criado por Dione Castro Alves – Founder da InNovaIdeia Assessoria em Tecnologia ®
Conecte-se: LinkedIn | GitHub | Email


---

“Transformando ideias em soluções tecnológicas inovadoras.”
