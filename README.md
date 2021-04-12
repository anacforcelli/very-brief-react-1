# very-brief-react-1
Parte 1 do Tutorial Muito Breve de React para Pessoas sem Tempo.

Este é um template didático criado por [Ana Clara Forcelli](https://github.com/anacforcelli) para o aprendizado de React.js com Typescript
Qualquer contribuição é bem-vinda. 

Para começar, devemos olhar para a hierarquia do React+TS.
A primeira coisa que é carregada é o arquivo index.tsx , que vai de cara mandar renderizar o App()(linha 8-index.tsx).

No App.tsx (onde se define a função App() ), ele vai terceirizar novamente a renderização, mandando pro Routes() (linha 6-App.tsx). 

Subindo a pilha, vamos pro Routes.tsx, que vai catar as páginas na pasta /pages e mandar pro App() renderizar.

Todas as páginas são tratadas como Componentes (templates reutilizáveis) de React quando usamos o pacote 'react-router-dom' para implementar a navegação, a fim de tornar o programa modular.

Agora começamos a ter de usar neurônios pois, dependendo da complexidade, será melhor montar uma função (com ou sem Hooks) ou até mesmo uma classe para definir o componente da sua página. 

(Nota pouco importante mas que mexe com a reputação: Existem bibliotecas do React como o Function Component (FC) e Void Function Component (VFC), mas por enquanto não sei no que elas ajudam.)

**FAZENDO COMPONENTES**

Usamos funções puras quando fazemos uma página ou componente mais simples, estático, como uma caixa de texto não interativa. A página /pages/simplePage é um exemplo disso.

Usamos funções com Hooks (ou classes) quando temos que modificar o estado do componente, tornando-o responsivo e mudando o conteúdo de acordo com o uso. A página /pages/complexPageHooks é um exemplo de função com Hooks (useState, useEffect). 


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
To learn React, check out the [React documentation](https://reactjs.org/).
