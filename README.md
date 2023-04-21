# GitFav

GitFav é uma página web que permite pesquisar por usuários no GitHub e salvá-los em uma lista dinâmica. Cada perfil salvo exibe o nome do usuário, seu nome de perfil, seus seguidores e quantos repositórios ele tem. Além disso, há um link para acessar diretamente o perfil no GitHub. 

O projeto foi desenvolvido utilizando HTML, CSS e JavaScript, com destaque para o uso de conceitos como async/await para requisições assíncronas.

## Como utilizar

Para utilizar o GitFav, basta acessar a página web e digitar o nome do usuário que deseja buscar no GitHub na barra de pesquisa. Ao clicar em "Adicionar", o perfil será salvo na lista exibida abaixo da barra de pesquisa.

Na lista, você pode acessar o perfil diretamente clicando no link exibido ou remover um perfil salvo clicando no botão de lixeira correspondente.

## Como executar o projeto

Para executar o projeto localmente, basta clonar o repositório e abrir o arquivo index.html em um navegador web. 

```bash
git clone https://github.com/seu-usuario/gitfav.git
cd gitfav
```


## Funcionamento técnico

O GitFav utiliza a API do GitHub para buscar informações sobre os usuários. As requisições são feitas de forma assíncrona utilizando a função fetch e as informações são exibidas dinamicamente na página utilizando JavaScript.

Os perfis salvos são no navegador do usuário utilizando a API Local Storage. Isso permite que os perfis permaneçam salvos mesmo após a página ser fechada e reaberta.

![image](https://user-images.githubusercontent.com/68011048/233516046-6b14cda8-3564-4c68-9c13-353106aec9ba.png)
