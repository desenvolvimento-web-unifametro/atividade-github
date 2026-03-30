### Atividade Github

Regras a seguir:
* Atomicidade: Cada branch e cada commit deve realizar apenas uma tarefa da lista.
* Nomenclatura: As branches devem seguir o padrão feature/nome-da-tarefa (letras minúsculas e separadas por hífen).
* Fluxo Contínuo: Só inicie a próxima tarefa após realizar o Merge da anterior na main.

## Para iniciar a atividade:
1 - Crie um repositorio no seu github
2 - Crie uma pasta para o projeto no seu computador
3 - Abra essa pasta no VSCODE
4 - Primeiro comando para comecar o versionamento utilizando git
```
git init
```
5 - Inicie as atividades e utilize os comandos conforme necessario:
```
git add .
```
```
git commit -m “...”
```
```
git remote add origin url-do-repositorio
```
```
git push -u origin main
```

## Passo a Passo do Fluxo de Trabalho
Para cada item da lista de tarefas, siga estes comandos:

1 - Inicie a tarefa: Certifique-se de estar na main e atualizada.
```
git checkout main
git pull origin main
git checkout -b nome-da-branch
```

2 - Trabalhe e Comite: Após realizar a alteração específica:
```
git add .
git commit -m "tipo: descricao curta do que foi feito"
git push -u origin nome-da-branch
```

3 - Integre: Abra o PR no GitHub, faça o Merge e volte para a main para repetir o processo no próximo item.


## Lista de Tarefas (Backlog)
Siga esta ordem exata. Cada linha representa uma nova branch e um novo ciclo de PR.

Fase 1: Estrutura HTML
- [ ] Criar o arquivo index.html
- [ ] Criar a estrutura básica com a div principal e o h1.
- [ ] Adicionar o formulario com os label's e input's.
- [ ] Adicionar o botão de envio dentro do formulário.
- [ ] Adicionar a div com os elementos de cadastro.
- [ ] Alterar o título da página para "Login".

Fase 2: Setup CSS
- [ ] Criar o arquivo style-login.css e vinculá-lo ao HTML.
- [ ] Criar o reset CSS com configurações globais.
- [ ] Importa e adiciona a fonte poppins as configurações globais.

Fase 3: Estilização (UI)
- [ ] Estilizar o body.
- [ ] Estilizar a div .container-login
- [ ] Estilizar o h1.
- [ ] Estilizar o layout do formulário.
- [ ] Estilizar todos os labels.
- [ ] Estilizar todos os inputs.
- [ ] Adicionar o estado de :focus nos inputs.
- [ ] Estilizar o design do botão.
- [ ] Adicionar o efeito de :hover no botão.
- [ ] Estilizar a div de cadastro.
- [ ] Estilizar o parágrafo da área de cadastro.
- [ ] Estilizar a tag âncora de cadastro.

Fase 4: Refatoração
- [ ] Encontre melhorias que podem ser aplicadas ao projeto original. Implemente cada melhoria em uma branch separada, seguindo a convenção de nomenclatura ideal.
