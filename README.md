# Nome da sua aplicação

## 🗺 Contexto

### O que esta aplicação faz  
  
`Citar o principal objetivo da aplicação de maneira sucinta, em uma ou duas frases.`

Se possível, listar casos de uso. Por exemplo:
- A aplicação é utilizada no projeto X para facilitar a geração de Y (se existir, inserir link do repositório do caso de uso);
- A aplicação é utilizada...  

### Motivação  
  
`Elencar os motivos pelo qual esta solução foi utilizada, em detrimento de outras soluções. Trazer benefícios/vantagens da utilização desta aplicação em específico.`

### Links relacionados a Contexto
- [Página do Oráculo](https://oraculo.rdstation.com.br/)
- [Página do Backstage](https://backstage-staging.rdstation.com.br/catalog)
- [Arquitetura da aplicação](https://github.com/Vinicius-MManganotti/template-lean/blob/main/arquitetura.md) 

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você está com o [Docker instalado](https://github.com/ResultadosDigitais/rd-product-team-wiki/wiki/Como-configurar-o-ambiente-de-desenvolvimento-utilizando-Docker) em sua máquina;
- Você está com o [jFrog configurado](https://github.com/ResultadosDigitais/rd-product-team-wiki/wiki/Configura%C3%A7%C3%A3o-do-registro-da-RD-para-consumir-artefatos-privados-no-jFrog-(NPM)) em sua máquina;
- `caso a aplicação necessite de mais algum pré-requisito, insira aqui`

## 🚀 Desenvolvendo em ambiente local

### Passo a passo para rodar a aplicação em abiente local

Para rodar a aplicação em ambiente local, faça o seguinte comando no terminal:
`$ make start`
`Caso a aplicação em específico tenha mais algum passo para rodar corretamente, insira aqui o comando.`

## 🎮 Utilizando a aplicação

`Esta sessão é dedicada para trazer exemplos de comandos comuns que podem ser utilizados na aplicação. Estes comandos mais comuns podem ser apresentados em formato de passo a passo. Exemplo:`

Para resetar a aplicação (ação recomendada antes de iniciar a manipular o código), faça o seguinte comando:
`$ docker-compose run feature_flagger_ui rails db:reset RAILS_ENV=development

$ docker-compose run feature_flagger_ui rails db:reset RAILS_ENV=test`

---
> Gerado através do Backstage ♦️
