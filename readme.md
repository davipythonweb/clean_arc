# project-clean-arctetura

- utilizando pylint e comandos para gerar o requirements.txt, apos os commits.
- configs do vscode para nao gerar arquivos cache
___________________________________________________

- essa_eh_minha_funcao -> snake_case === variaveis e funçoes
- minhaFuncao -> cammelCase === NAõ utilizar em codigo
- MinhaFuncao -> PascalCase === classes
__________________________________________________
- instalar pacotes do projeto
`pip install -r requirements.txt`
- instalar pre-commit para rodar as configuraçoes do pylint e arquivo yaml
`pre-commit install`
- tirando um arquivo mandado para o git
`git rm <nome_do_arquivo> --cached`
- verificando o log do git
`git log --oneline`
- verificando status dos arquivos no stage
`git status`
- sobrescrever o commit anterior com as novas auteraçoes
`git commit --amend --no-edit`
- forçar o push
`git push --force`

________________________________

- testando flake8 e black