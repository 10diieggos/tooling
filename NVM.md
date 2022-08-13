# [NVM](https://github.com/nvm-sh/nvm "Repositorio do NVM no Github")

### Instalação

`wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

Isso vai executar um script que vai clonar o repositório do NVM e jogar em um diretório chamado `~/.nvm/`, que é onde serão instaladas as várias versões do Node.js que quisermos.

A versão do NVM no momento de escrita deste post era a `v0.39.1`. Para garantir uma versão mais recente, copie esse mesmo comando na [página do repositório do NVM no GitHub](https://github.com/nvm-sh/nvm).

### Comandos básicos

`$ nvm ls`- listar versões instaladas

`$ nvm ls-remote`- Listar versões disponíveis para instalação

`$ nvm install vX.X.X`- Instalar uma versão

`$ nvm install node`- Instalar a versão mais recente

`$ nvm uninstall vX.X.X`- Desinstalar uma versão

`$ nvm use vX.X.X`- Usar uma versão
]
`$ nvm use node`- Usar a versão mais recente

Fonte: [Treinaweb](https://www.treinaweb.com.br/blog/instalando-e-gerenciando-varias-versoes-do-node-js-com-nvm)

Consulte a fonte para mais comandos!