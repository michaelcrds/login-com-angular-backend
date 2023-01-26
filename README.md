# Clonando o Repositório

Primeiro é preciso que efetue a clonagem do repositório para o seu computador para assim efetuar alterações de código. Mas antes de clonar o repositório é importante que realize um **fork**, ou seja, criar uma cópia do mesmo para o seu github. Para isso basta subir a página e clicar no botão de mesmo nome e aguardar alguns minutos. Depois basta clicar em **clone or download** e copiar a URL do respositório.

Já abrindo o bash do Git para efetuar a clonagem será necessário que digite a seguinte linha de código e informe a URL copiada anteriormente:

```
git clone <url-do-repositorio>
```

### Instalando as Dependências

Para instalar as dependências do projeto basta abrir o **Prompt de Comando do Node.js** (caso você esteja no linux, basta utilizar o terminal), acessar a pasta do repositório e inserir o seguinte comando:

```
npm install
```

## Iniciando servidor

O comando abaixo deve ser executado a cada alteração feita no código:

```
npm start
```
