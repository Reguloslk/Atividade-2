# Atividade-2
# Execução e Atualização do Projeto no VS Code

## Tarefa 1 – Abrir o Projeto

### No VS Code Local

```bash id="kvn2u7"
code .
```

### Ou pelo GitHub Codespaces

1. Acesse o repositório no GitHub.
2. Clique em **Code**.
3. Clique na aba **Codespaces**.
4. Selecione **Create Codespace on main**.

---

## Tarefa 2 – Executar o Projeto

Abra o terminal integrado:

```bash id="rj9l3x"
python main.py
```

Exemplo de saída:

```text id="o1kmjb"
1 - Cadastrar
2 - Listar
3 - Remover
4 - Sair
Escolha uma opção:
```

Tire um print mostrando:

* VS Code aberto.
* Arquivos do projeto.
* Terminal executando o programa.

---

## Tarefa 3 – Fazer uma Alteração

Exemplo: adicionar uma linha ao README.

Antes:

```text id="h7yr0y"
Sistema para controle de equipamentos.
```

Depois:

```text id="b1rz8h"
Sistema para controle de equipamentos.

Versão 1.1 - Atualização da documentação.
```

Salve o arquivo e execute novamente o programa para verificar que tudo continua funcionando.

---

## Tarefa 4 – Commit e Push

Verifique as alterações:

```bash id="x9wdg5"
git status
```

Adicione os arquivos:

```bash id="f3h0kr"
git add .
```

Crie o commit:

```bash id="mvpr4l"
git commit -m "Atualiza README para versao 1.1"
```

Envie para o GitHub:

```bash id="v3x63o"
git push
```

Verifique o histórico:

```bash id="a0qv5r"
git log --oneline
```

---

## Tarefa 5 – Evidências

Tire prints mostrando:

1. VS Code ou Codespaces aberto.
2. Estrutura dos arquivos.
3. Terminal executando `python main.py`.
4. Arquivo alterado.
5. Commit criado.
6. Resultado do `git push`.
7. Histórico exibido por `git log --oneline`.

---

## Link do Repositório

Formato esperado:

```text id="s4o5dg"
https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO
```
