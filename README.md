# Sistema de Notas do Aluno

Programa desenvolvido em python, simples. Para verificar se um aluno foi aprovado ou reprovado, nota minima é 7
---

## 1. Tecnologias Utilizadas

* **Python 3**
* Funções
* Estrutura condicional (`if`/`else`)
* Entrada de dados com `input()`
* Saída de dados com `print()`

---

## 2. Como Instalar e Executar

### 2.1 Instalação
Certifique-se de que o Python 3 esteja instalado no seu computador. Depois, salve o código em um arquivo chamado:
`sistema_notas.py`

### 2.2 Execução
Abra o terminal na pasta onde o arquivo está localizado e execute:

```bash
python sistema_notas.py
```

Caso esteja utilizando Linux ou macOS, utilize:

```bash
python3 sistema_notas.py
```

---

## 3. Exemplo de Uso

### Exemplo de Aprovação
```text
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 7
A média final é: 7.50
Status: APROVADO!
```

### Exemplo de Reprovação
```text
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 5
Digite a segunda nota: 6
A média final é: 5.50
Status: REPROVADO.
```

---

## 4. Código

```python
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema de Notas do Aluno ===")
n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")
```

---

## 5. Funcionamento

O programa realiza as seguintes etapas:
1. Solicita a primeira nota.
2. Solicita a segunda nota.
3. Calcula a média das duas notas.
4. Exibe a média final com duas casas decimais.
5. Verifica se a média é maior ou igual a 7,0.
6. Exibe o status final do aluno.

---

## 6. Checklist do Projeto

- [x] Criar função para calcular a média
- [x] Solicitar duas notas ao usuário
- [x] Calcular a média
- [x] Exibir a média com duas casas decimais
- [x] Verificar aprovação ou reprovação

---

## 7. Fórmula da Média

A média do aluno é calculada somando as duas notas e dividindo o resultado por 2.

> **Fórmula:** `Média = (Nota 1 + Nota 2) / 2`

---

## 8. Tabela de Resultados

| Média | Status |
| :--- | :--- |
| Maior ou igual a 7,0 | **APROVADO** |
| Menor que 7,0 | **REPROVADO** |

---

## 9. Autor e Contato

* **Autor:** Paulo Henrique Silva de Souza
* **GitHub:** [Seu GitHub](https://github.com/@HenriqueSouza00)
* **Dev.io:** [Seu Dev.io](https://dev.to/henriquesouza00)
* **LinkedIn.com:** [Seu LinkedIn.com](https://www.linkedin.com/in/henriquesouza00/)
