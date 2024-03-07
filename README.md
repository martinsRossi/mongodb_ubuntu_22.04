# Instalção do Mongodb no Ubuntu 22.04

Guia para instalar o MongoDB em Linux Ubuntu em 7 passos.

## Descrição
Este repositório tem como propósito de ajudar a instalar o MongoDB na versão 22.04 do Ubuntu. Muitos usuários apresentaram problemas ao instalar o MongoDB nesta versão do Ubuntu. Tentarei ajudar com os passos para a instalação

<!--## Conteúdo
- **-->

## Índice
- <a href="#intro">Introdução ao MongoDB</a>
- <a href="#instalacao">Instalação do MongoDB em Ubuntu 22.04</a>
- <a href="#servico">Inciando e habilitando o serviço do MongoDB</a>
- <a href="#database">Criando um banco de dados e usuário em MongoDB</a>
- <a href="#parametros">Ajustando parâmetros de Segurança do MongoDB em Ubuntu</a>
- <a href="#remote">Configurando MongoDB para acesso remoto</a>
- <a href="#trabalhando">Trabalhando com banco de dados MongoDB</a>


<p id="intro"></p>

## Introdução ao MongoDB

### O que é o MongoDB?
O desenvolvimento de aplicativos escalonáveis e de alto desempenho fez uso extensivo do MongoDB, um banco <a href="https://www.pcperformance.com.br/glossario/o-que-e-cross-platform/">cross-plataform</a> e de código aberto. Em termos de modelagem e organização de dados, o MongoDB é diferente dos bancos de dados SQL convencionais.

Em vez de relações tabulares rígidas, o MongoDB é construído sobre um modelo de dados flexível e orientado a documentos. Cada entidade é armazenada como um documento BSON – uma representação binária de pares de valores de campo semelhantes a JSON. Os documentos contêm estruturas hierárquicas com matrizes e subdocumentos, espelhando dados complexos do mundo real.

Algumas caracteristicas do MongoDB são: modelo de documento declarativo, os esquemas dinâmicos e recursos de escalabilidade nativa. Isso torna-o um banco muito amigável com o desenvolvimento ágil por não ter muitas restrições (schemaless).

## 

<p id="instalacao"></p>
## Instalação do MongoDB em Ubuntu 22.04
Depois de concluir estas etapas a seguir, você pode instalar e configurar o MongoDB em seu sistema Ubuntu 22.04. As duas primeiras etapas orientam você no processo de instalação. As etapas restantes detalham como criar um banco de dados e usuários do banco de dados, proteger o servidor de banco de dados, configurar o acesso remoto e trabalhar com o banco de dados MongoDB.

### Passo 1: Instale o MongoDB no Ubuntu 22.04

A primeira etapa é instalar os pacotes de pré-requisitos necessários durante a instalação. Para fazer isso, execute o seguinte comando:

<code class="language-bash"> sudo apt install software-properties-common gnupg apt-transport-https ca-certificates -y</code>

Para instalar o pacote MongoDB mais recente, você precisa adicionar o repositório do pacote MongoDB ao arquivo de lista de fontes no Ubuntu. Antes disso, você precisa importar a chave pública do MongoDB em seu sistema usando o comando wget da seguinte forma:

```
curl -fsSL https://pgp.mongodb.com/server-7.0.asc |  sudo gpg -o /usr/share/keyrings/mongodb-server-7.0.gpg --dearmor
```
Caso o curl não esteja instalado, rode:

```
```


```
```


```
```


```
```


```
```



<p id="servico"></p>
## Inciando e habilitando o serviço do MongoDB

<p id="database"></p>
## Criando um banco de dados e usuário em MongoDB

<p id="parametros"></p>
## Ajustando parâmetros de Segurança do MongoDB em Ubuntu

<p id="remote"></p>
## Configurando MongoDB para acesso remoto

<p id="trabalhando"></p>
## Trabalhando com banco de dados MongoDB
