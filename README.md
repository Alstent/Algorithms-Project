# Algorithms Project

Um projeto que tem como principal objetivo resolver problemas e otimizar algoritmos do tipo que aparecem em inúmeros processos de entrevista por _whiteboard_ e que vão acelerar a minha capacidade de resolver problemas!

Pessoas desenvolvedoras de software, além de serem muito boas em implementações, devem, também, ser boas resolvendo problemas e otimizando algoritmos. Esse projeto tem o intuito de melhorar ainda mais, a minha capacidade de resolução de problemas e otimização de código, que envolve algumas habilidades:

  - Lógica;

  - Capacidade de interpretação do problema;

  - Capacidade de interpretação de um código legado;

  - Capacidade de resolução do problema, de forma otimizada;

  - Resolver o problemas/Otimizar algoritmos mesmo sob pressão.

# Sumário

- [Habilidades](#habilidades)
- [Instruções do projeto](#instruções-do-projeto)
- [Testes](#testes)
- [Linter](#linter)

# Habilidades

  - Estrutura de dados

  - Complexidade de algoritimos

  - Capacidade de interpretação do problema;

  - Capacidade de resolução do problema, de forma otimizada;
  
  - Analisar corretamente a ordem de complexidade de um algoritmo.

  - Recursividade

  - Algoritmos de ordenação e algoritmos de busca

# Instruções do projeto:

1. Clone ou download o repositório

2. Mude para a branch de desenvolvimento
  * Va para a branch `dev`
    * `git checkout dev`

3. Crie o ambiente virtual para o projeto

- `python3 -m venv .venv && source .venv/bin/activate`

4. Instale as dependências

- `python3 -m pip install -r dev-requirements.txt`
5. Verifique que os testes estão executando:
  * ` python3 -m pytest`

# Testes

Para executar os testes certifique-se de que os seguintes passos foram realizados;

1. **criar o ambiente virtual**

```bash
$ python3 -m venv .venv
```

2. **ativar o ambiente virtual**

```bash
$ source .venv/bin/activate
```

3. **instalar as dependências no ambiente virtual**

```bash
$ python3 -m pip install -r dev-requirements.txt
```

📚 Se quiser saber mais sobre a instalação de dependências com `pip`, veja esse [artigo](https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1).

Com o seu ambiente virtual ativo, as dependências serão instaladas neste ambiente.
Quando precisar desativar o ambiente virtual, execute o comando "deactivate". Lembre-se de ativar novamente quando voltar ao projeto.

O arquivo `dev-requirements.txt` contém todas as dependências que serão utilizadas no projeto, ele está agindo como se fosse um `package.json` de um projeto `Node.js`.

**Executar os testes**

```bash
$ python3 -m pytest
```

Este comando irá executar todos os testes do projeto. Caso o teste falhe e você queira ter um print melhor do erro basta executar o seguinte comando:

```bash
python3 -m pytest -s -vv
```

Caso precise executar apenas um arquivo de testes basta executar o comando:

```bash
python3 -m pytest tests/nomedoarquivo.py
```

Para resolver um problema de cada vez, utilize o argumento `-x` para o Pytest encerrar a execução no primeiro erro que encontrar:

```bash
python3 -m pytest tests/nomedoarquivo.py -x
```

✍️ **Teste manual**: abra um terminal Python importando as funções de interesse através do comando `python3 -i tech_news/arquivo_de_interesse.py` e as invoque utilizando diferentes parâmetros.

**Verificar o estilo**
Para verificar se você está seguindo o guia de estilo do Python corretamente, execute o comando:

```bash
$ python3 -m flake8
```

# Linter

Para garantir a qualidade do código, utilizei neste projeto o linter `Flake8`.
Assim o código estará alinhado com as boas práticas de desenvolvimento, sendo mais legível e de fácil manutenção! Para rodá-lo localmente no projeto, execute o comandos abaixo:

```bash
python3 -m flake8
```

### © Rafael Alstent