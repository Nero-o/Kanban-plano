
# Kanban de atividades

Este projeto é um aplicativo Kanban que ajuda as equipes a gerenciar suas tarefas e projetos. Ele permite que os usuários criem cartões com tarefas, movam esses cartões entre colunas para indicar seu status atual e adicionem comentários e anexos para manter informações relevantes junto com a tarefa.




## Estrutura do projeto
```
kanban-plano/
  ├── index.html
  ├── css/
  │   ├── style.css
  │   └── responsive.css
  ├── js/
  │   ├── main.js
  │   └── modules/
  │       ├── modal.js
  │       └── slider.js
  └── images/
      ├── banner.jpg
      ├── logo.png
      └── icons/
          ├── facebook.svg
          └── twitter.svg
```
## Funcionalidades
- Criar e editar cartões com título, descrição e prazo.
- Mover cartões entre as colunas "Novo", "Em progresso" e "Concluído".
- Adicionar comentários e anexos a cartões existentes.
- Pesquisar cartões por título ou descrição.
- Editar ou excluir cartões existentes.
- Responsivo para dispositivos móveis.
## Rodando localmente

Clone o projeto

```bash
git clone https://github.com/Nero-o/Kanban-plano
```

Entre no diretório do projeto

```bash
cd projeto-kanban
```
Inicie o servidor

```bash
  npm run start
```


## Uso
Abra o navegador e acesse o endereço:
```bash
http://localhost:3000
```
- Crie um novo cartão arrastando um cartão vazio da coluna "Novo" para a coluna "Em progresso".

- Mova o cartão para a coluna "Concluído" quando a tarefa estiver finalizada.

- Adicione comentários ou anexos ao cartão clicando no botão "Adicionar Comentário" ou "Adicionar Anexo".

- Edite ou exclua um cartão clicando no ícone de lápis ou lixeira no canto superior direito do cartão.

- Pesquise por um cartão específico usando a barra de pesquisa na parte superior do aplicativo.


## Contribuição
Para contribuir com o projeto, siga as seguintes etapas:

- Faça um fork do repositório.
- Clone o seu fork localmente.
- Crie uma nova branch para a sua feature:
```bash
git checkout -b minha-feature
```
- Implemente as alterações necessárias e faça commit das mudanças:
```bash
git commit -m "Adiciona funcionalidade X"
```
- Envie as mudanças para o seu repositório no GitHub:
```bash
git push origin minha-feature
```

## Autores

- [@Nero-o](https://github.com/Nero-o)
- [@Myerx](https://github.com/Myerzx)
- [@Thiago361](https://github.com/Thiago361)

