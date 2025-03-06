# Buscador de CEP

Este é um projeto simples de buscador de CEP utilizando React.js e a API do ViaCEP.

## Tecnologias Utilizadas

- React.js
- Axios
- React Icons
- HTML, CSS

## Funcionalidades

- Busca de informações sobre um CEP informado pelo usuário.
- Exibição de dados como logradouro, bairro, cidade e estado.
- Validação para evitar buscas com campo vazio.

## Como Executar o Projeto

### 1. Clonar o Repositório
```bash
 git clone https://github.com/Luamateus2/Buscador-de-Cep.git
```

### 2. Instalar as Dependências
Acesse a pasta do projeto e instale as dependências:
```bash
 cd buscador-cep
 npm install
```

### 3. Rodar o Projeto
```bash
 npm start
```
O projeto estará rodando em `http://localhost:3000`

## Estrutura do Projeto

```
├── src
│   ├── services
│   │   ├── api.js (Configuração do Axios para consumir a API do ViaCEP)
│   ├── style.css (Estilização do projeto)
│   ├── App.js (Componente principal)
│   ├── index.js (Ponto de entrada do React)
├── package.json (Configuração do Node.js e dependências)
```

## API Utilizada
O projeto utiliza a API gratuita do ViaCEP para buscar os dados de um CEP:
```
https://viacep.com.br/ws/{CEP}/json/
```

## Contribuição
Sinta-se à vontade para contribuir com melhorias. Basta seguir os passos:
1. Faça um fork do projeto.
2. Crie uma branch (`feature/nova-funcionalidade`).
3. Faça as alterações e commite.
4. Envie um pull request.

## Licença
Este projeto está sob a licença MIT.



