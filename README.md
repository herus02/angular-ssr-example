# Exemplo de Angular 19 com SSR
Esse projeto é uma demonstração do recurso do Angular Universal para SSR, a fim de exemplificar o uso da ferramenta e tornar isso parte do meu portfolio.

## Projeto 
Criação de uma lista de produtos com carrinho de compras (Product Cart) e ambiente administrativo para gerenciar o estoque dos produtos (Inventory management). Os dados serão lidos de json estático dentro do projeto. Será publicado no Github Pages.

## Ferramentas
Esse projeto também irá utilizar o recursos de SSR do Angular Universal, como  provideClientHydration() dentro do provideHttpClient(), junto com withFetch() que permite que o cliente ou browser refresque a interface com novas atualizações, permanecendo os dados estáticos. 

Para o Carrinho, o NgRX e seus selector, actions, effects e reducers farão o trabalho de criar um estado global para poder ser utilizado durante a navegação entre as páginas 

## Conclusão 
Há diversas complexidades até em iniciar um projeto com Angular Universal e isso torna o processo de estudo mais extenso. Estou preferindo analisar um projeto criado para usar como referência.