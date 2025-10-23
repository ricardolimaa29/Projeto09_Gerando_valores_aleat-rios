# Projeto09_Gerando_valores_aleat-rios

# 🐼 Exercícios de Pandas + Random (Com Resolução)

Esses exercícios unem as bibliotecas **pandas** e **random**, simulando situações do mundo real com geração de dados aleatórios.  
Os desafios são básicos, mas ajudam bastante a treinar raciocínio lógico e manipulação de dados com DataFrames.

---

## 💡 1) Gerador de Notas Aleatórias

Crie um programa que gere as notas de **10 alunos** para **3 matérias**: Matemática, Português e Ciências.  
As notas devem ser números **aleatórios de 0 a 10** (inteiros).

**Desafios:**
- Crie um `DataFrame` com as colunas `["Aluno", "Matemática", "Português", "Ciências"]`.
- Calcule a **média geral de cada aluno**.
- Mostre o aluno com **a maior média**.


---

## 📊 2) Vendas Aleatórias de Lojas

Crie um DataFrame que simule as vendas de **5 lojas diferentes**, com valores diários gerados aleatoriamente entre **100 e 1000 reais** durante **7 dias**.

**Desafios:**
- Calcule o **total de vendas por loja**.
- Mostre qual loja **vendeu mais na semana**.
- Calcule o **valor médio diário geral** (média de todas as lojas e dias).



---

## 📦 3) Controle de Estoque Aleatório

Simule um estoque de **8 produtos**.  
Cada produto deve ter:
- Nome (Produto 1, Produto 2, etc.)
- Quantidade (aleatória entre 10 e 100)
- Preço (aleatório entre 5.0 e 100.0)

**Desafios:**
- Adicione uma coluna chamada **"Valor Total"** (`quantidade * preço`).
- Descubra **qual produto tem o maior valor total**.
- Mostre apenas os produtos com valor total **acima da média**.



---

## 🧠 4) Sorteio de Dados Aleatórios

Crie um programa que simule **50 lançamentos de dado (1 a 6)** e salve os resultados em um DataFrame.

**Desafios:**
- Mostre **quantas vezes** cada número foi sorteado.
- Crie uma coluna adicional chamada **"Par/Ímpar"**.
- Mostre **quantas vezes** saíram números pares e ímpares.



---

### ✨ Dica Extra

Para exibir todos os dados sem cortes:
```python
pd.set_option("display.max_rows", None)
pd.set_option("display.max_columns", None)
```

E para gerar **resultados iguais toda vez**:
```python
random.seed(42)
```

---

**Autor:** Professor Ricardo Rodrigues Lima  
**Tema:** Introdução ao uso conjunto de `pandas` e `random`  
**Nível:** Iniciante com desafios práticos 🎯
