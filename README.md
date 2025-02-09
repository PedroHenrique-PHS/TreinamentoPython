# TreinamentoPython
## 📌 Roteiro de Estudo - Python

---

### 🔹 Nível 1 - Fundamentos do Python (1 a 2 semanas)

✅ **Objetivo**: Aprender a sintaxe básica e conceitos fundamentais.

🔹 **Tópicos**:
- Instalação do Python e configuração do ambiente (VS Code, PyCharm, Jupyter)
- - **Instalação do Python**:
    - Acesse o site oficial do Python ([python.org](https://www.python.org/))
    - Baixe a versão mais recente compatível com seu sistema operacional
    - Durante a instalação, marque a opção "Add Python to PATH"
  - **Configuração do VS Code**:
    - Instale o [Visual Studio Code](https://code.visualstudio.com/)
    - Instale a extensão "Python" da Microsoft no marketplace do VS Code
    - Configure o interpretador do Python no VS Code
  - **Configuração do PyCharm**:
    - Baixe e instale o [PyCharm](https://www.jetbrains.com/pycharm/)
    - Crie um novo projeto e configure o interpretador do Python
  - **Instalação do Jupyter Notebook**:
    - Instale via pip: `pip install jupyter`  
    - Execute com o comando: `jupyter notebook`
- **Variáveis e tipos de dados (inteiros, float, strings, booleanos)**
  - Inteiros (`int`): números sem casas decimais, ex: `10`, `-5`
  - Ponto flutuante (`float`): números com casas decimais, ex: `3.14`, `-0.5`
  - Strings (`str`): sequência de caracteres, ex: `'Olá, mundo!'`, `"Python"`
  - Booleanos (`bool`): valores `True` ou `False`
  - Conversão entre tipos: `int()`, `float()`, `str()`, `bool()`

- **Operadores aritméticos, lógicos e de comparação**
  - Aritméticos: `+`, `-`, `*`, `/`, `//` (divisão inteira), `%` (módulo), `**` (exponenciação)
  - Comparação: `==`, `!=`, `>`, `<`, `>=`, `<=`
  - Lógicos: `and`, `or`, `not`

- **Estruturas condicionais (`if`, `elif`, `else`)**
  - Uso de `if` para executar um bloco de código se a condição for verdadeira
  - `elif` para testar condições adicionais
  - `else` como última alternativa
  ```python
  idade = 18
  if idade < 18:
      print("Menor de idade")
  elif idade == 18:
      print("Tem exatamente 18 anos")
  else:
      print("Maior de idade")
  ```

- **Estruturas de repetição (`for`, `while`)**
  - `for` para percorrer listas, strings e intervalos
  ```python
  for i in range(5):
      print(i)  # Saída: 0, 1, 2, 3, 4
  ```
  - `while` para executar um bloco de código enquanto a condição for verdadeira
  ```python
  contador = 0
  while contador < 5:
      print(contador)
      contador += 1
  ```

- **Funções (`def`, argumentos, retorno de valores)**
  - Declaração de funções com `def`
  - Parâmetros e argumentos
  - Retorno de valores com `return`
  ```python
  def soma(a, b):
      return a + b
  print(soma(2, 3))  # Saída: 5
  ```

- **Manipulação de strings**
  - Métodos úteis: `upper()`, `lower()`, `strip()`, `replace()`, `split()`
  ```python
  texto = " Olá, Python! "
  print(texto.strip())  # Remove espaços extras: "Olá, Python!"
  print(texto.upper())  # " OLÁ, PYTHON! "
  print(texto.replace("Python", "Mundo"))  # " Olá, Mundo! "
  ```


📝 **Exercícios**:
- Criar um programa que verifica se um número é par ou ímpar
- Escrever uma função que retorna a soma de dois números
- Criar um loop que imprime os números de 1 a 100

---

### 🔹 Nível 2 - Estruturas de Dados e Manipulação de Arquivos (2 a 3 semanas)

✅ **Objetivo**: Trabalhar com diferentes tipos de dados e arquivos.

🔹 **Tópicos**:
- **Listas e tuplas (operações básicas, métodos úteis)**
  - Listas: `append()`, `remove()`, `pop()`, `sort()`, `len()`
  - Tuplas: estruturas imutáveis, acesso por índice
  ```python
  lista = [1, 2, 3]
  lista.append(4)
  print(lista)
  ```

- **Dicionários e conjuntos**
  - Dicionários: armazenamento chave-valor, `keys()`, `values()`, `items()`
  - Conjuntos: elementos únicos, `add()`, `remove()`, `union()`, `intersection()`
  ```python
  dicionario = {"nome": "João", "idade": 25}
  print(dicionario["nome"])
  ```

- **List comprehension**
  - Criar listas de forma concisa
  ```python
  quadrados = [x**2 for x in range(10)]
  print(quadrados)
  ```

- **Manipulação de arquivos (`open`, leitura, escrita)**
  ```python
  with open("arquivo.txt", "w") as f:
      f.write("Olá, mundo!")
  ```
  ```python
  with open("arquivo.txt", "r") as f:
      print(f.read())
  ```

- **Módulos e pacotes (`import`, `pip`)**
  - Importação de módulos (`import math`, `from os import path`)
  - Uso do `pip install` para instalar pacotes externos

- **Introdução ao tratamento de erros (`try`, `except`)**
  ```python
  try:
      x = 1 / 0
  except ZeroDivisionError:
      print("Erro: divisão por zero")
  ```


📝 **Exercícios**:
- Criar um programa que lê um arquivo `.txt` e conta quantas palavras ele tem
- Implementar um dicionário de dados que simula um cadastro de clientes
- Criar uma lista de números aleatórios e ordená-los sem usar `.sort()`

📚 **Recursos**:
- Dicas para estudar e praticar programando (https://dev.to/gabogaldino/dicas-para-estudar-e-praticar-programando-3ia6)
- Sites abaixo permitem praticar codificação. Vou analisar cada um e a medida que for conhecendo vou comentando ou retirando os que não valem a pena:
- https://www.codewars.com/
https://www.leetcode.com/
https://www.hackerrank.com/
https://www.topcoder.com/
https://www.exercism.org/
https://www.coderbyte.com/
https://www.codingame.com/
https://www.codechef.com/
https://www.w3schools.com/
https://www.hackerearth.com/
existem muitos outros, se souber, usar, e quiser indicar algum outro, responde o post ae !
https://www.freecodecamp.org/
https://www.beecrowd.com.br/judge/pt/login
https://neps.academy/br/login
https://www.codecademy.com/
https://www.frontendmentor.io/

---

### 🔹 Nível 3 - Programação Orientada a Objetos (POO) (2 a 3 semanas)

✅ **Objetivo**: Entender e aplicar POO no Python.

🔹 **Tópicos**:
- Classes e objetos
- Atributos e métodos de instância
- Métodos especiais (`__init__`, `__str__`, etc.)
- Herança e polimorfismo
- Métodos e atributos estáticos

📝 **Exercícios**:
- Criar uma classe `Carro` com atributos como modelo, cor e ano
- Criar um sistema de gerenciamento de contas bancárias usando POO
- Implementar um sistema de login com autenticação básica

---

### 🔹 Nível 4 - Manipulação de Dados e Automação (3 a 4 semanas)

✅ **Objetivo**: Aprender a trabalhar com dados e automação.

🔹 **Tópicos**:
- Manipulação de arquivos CSV e JSON
- Expressões regulares (`re`)
- Web Scraping com `BeautifulSoup` e `requests`
- Automação com `Selenium`
- Introdução ao Pandas e NumPy

📝 **Exercícios**:
- Criar um bot que preenche formulários automaticamente
- Criar um script que baixa cotações de moedas da internet
- Analisar dados de um arquivo CSV e gerar estatísticas

📚 **Recursos**:
- Curso Pandas e NumPy (Data Science Academy)

---

### 🔹 Nível 5 - Desenvolvimento Web e APIs (3 a 4 semanas)

✅ **Objetivo**: Criar aplicações web e consumir APIs.

🔹 **Tópicos**:
- Introdução ao Flask e FastAPI
- Criando e consumindo APIs REST
- Autenticação com JWT
- Banco de Dados com SQLite e PostgreSQL
- Front-end com Flask e Jinja2

📝 **Exercícios**:
- Criar uma API que retorna informações de usuários
- Criar um site simples com Flask e HTML
- Construir um dashboard de dados usando Flask e Pandas

📚 **Recursos**:
- Curso Flask (Miguel Grinberg)

---

### 🔹 Nível 6 - Ciência de Dados e Machine Learning (Opcional - 6+ semanas)

✅ **Objetivo**: Aplicar Python para análise de dados e IA.

🔹 **Tópicos**:
- Pandas, Matplotlib e Seaborn
- Aprendizado de máquina com Scikit-learn
- Redes neurais com TensorFlow e PyTorch

📝 **Exercícios**:
- Criar um modelo de regressão linear para prever preços
- Criar um classificador de imagens usando CNN

📚 **Recursos**:
- Curso de Machine Learning (Andrew Ng - Coursera)

---

## 💡 Dicas Finais
✅ Pratique diariamente com pequenos projetos.
✅ Resolva desafios de programação no LeetCode e Codewars.
✅ Participe de comunidades como Stack Overflow e GitHub.
✅ Trabalhe em projetos reais para reforçar o aprendizado.
