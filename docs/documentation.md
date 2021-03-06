# :pencil: Documentação do Projeto



## :gear: Informações gerais:

Se você está lendo este documento é por quê tem interesse em contribuir neste projeto, isso é ótimo. Aqui estão algumas informações úteis que você gostaria de saber antes de ler os arquivos.

Este projeto foi desenvolvido utilizando as **tags semânticas do HTML5, CSS3 seguindo o conceito de Mobile First  e JavaScript "Vanilha"**.



## :writing_hand: Informações específicas

### HTML:

Aqui temos dois aquivos: index (página principal) e email, em ambas todas as importações estão comentadas para facilitar o entendimento. 

Todas as classes e IDs estão em inglês seguindo padrões de desenvolvimento, mas todas as interações com usuário são em português, como title, alerts, placeholders.

### CSS:

Aqui temos três arquivos: 

- **Global** contendo as variáveis de cores, botões e classes utilizadas em ambas as páginas.
- **Index** contendo a estilização da página principal somente.
- **Email** contendo a estilização da página e-mail somente.

A responsividade (presente apenas na index) foi desenvolvida a partir do conceito de Mobile First, você encontrará os estilos referentes ao desktop no Media Query logo ao final do arquivo.

### JavaScript

Aqui temos dois arquivos:

- **Data** responsável apenas por consumir os dados da api.
- **Validator** que concentra as funções de validação dos inputs e eventos dos botões dos formulários.
- **Index** responsável por preencher a página **principal** com os dados vindo de Data.
- **Email** responsável por preencher a página **e-mail** com os dados vindo de Data.



#### That is it! ☺

Espero que esse documento seja útil no entendimento sobre a arquitetura do projeto.



