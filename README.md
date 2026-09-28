# Rick and Morty Explorer

Aplicação educacional que consulta a [Rick and Morty API](https://rickandmortyapi.com/) e mostra cartões de personagens com imagem, nome, status, espécie e origem.

**Projeto desenvolvido para fins educacionais.**

**Demonstração informada no repositório:** [GitHub Pages](https://rafael-m-silva.github.io/Rick-and-Morty-Explorer/)

![Interface do Rick and Morty Explorer](./images/tela-rick.JPG)

## O que o projeto demonstra

- Requisições com <code>fetch</code> e <code>async/await</code>.
- Leitura de dados JSON e criação de elementos no DOM.
- Paginação pelo botão “carregar mais”.
- Organização de uma interface com HTML e CSS.

## Tecnologias

HTML5, CSS3, JavaScript e a API pública de Rick and Morty. Não há instalação de dependências.

## Como executar

~~~bash
git clone https://github.com/Rafael-M-Silva/Rick-and-Morty-Explorer.git
cd Rick-and-Morty-Explorer
~~~

Abra <code>index.html</code> no navegador ou sirva a pasta como site estático. A consulta aos personagens exige internet.

## Limitação conhecida

O botão de paginação ainda não é desativado corretamente na última página: o código usa o atributo <code>disablad</code> em vez de <code>disabled</code>. A documentação foi corrigida sem modificar o exercício.

## Autor

**Rafael Mauricio (Bigode)** · [GitHub](https://github.com/Rafael-M-Silva) · [LinkedIn](https://linkedin.com/in/rafael-mauricio-dev/) · [Bigode Ensina](https://bigodeensina.com.br/)
