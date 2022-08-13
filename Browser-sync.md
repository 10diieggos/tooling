# browser-sync

## Instalação

Para instalar o browser-sync, o primeiro passo é instalar o NodeJS. Caso você ainda não tenha o NodeJS instalado e tenha dúvidas de como instalar, veja esse artigo, que explica como instalar o NodeJS no Windows e no Linux.

Após instalar o NodeJS, vamos abrir o terminal e digitar o seguinte comando:

`npm install -g browser-sync`

E após terminar o processo de instalação, o browser-sync já estará pronto para uso.

## Uso

Para iniciar o browser-sync, vamos abrir o terminal e direcionar para a pasta do projeto, utilizando o comando cd. Depois, vamos rodar o seguinte comando na raiz do projeto:

`browser-sync start --server --files . --directory`

### Explicando o que são cada um dos argumentos

browser-sync start vai iniciar o servidor do browser-sync.

`--server vai iniciar o servidor localmente`

`--files .` vai garantir que o browser-sync observe todos os arquivos do projeto

`--directory` é opcional, mas sem esse argumento, o browser-sync vai procurar por uma página index.html para servir de início da aplicação. Caso você queira ver uma página diferente, eu recomendo adicionar esse argumento.

Depois de rodar o comando, uma nova aba no seu navegador padrão deve se abrir automaticamente com a estrutura do projeto. Em seguida, basta escolher um arquivo .html e agora qualquer mudança que acontecer no projeto será atualizada automaticamente no navegador, sem a necessidade de recarregar a página para ver as mudanças.

### Acessando de outro dispositivo (local)

[ ... ]

Fonte: [Alura](https://www.alura.com.br/artigos/instalando-o-browser-sync)