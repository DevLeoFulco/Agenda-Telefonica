# Agenda Telefônica em Angular e TypeScript

Este projeto é uma aplicação de agenda telefônica desenvolvida usando Angular e TypeScript. A agenda permite armazenar, ler e filtrar contatos, levando em consideração acentuações no nome dos contatos.

## Funcionalidades

- **Armazenamento de Contatos**: Os contatos são armazenados em um arquivo JSON e carregados na agenda durante a inicialização.
  
- **Leitura de Contatos**: A agenda lê os contatos do arquivo JSON e exibe na interface do usuário.
  
- **Filtragem de Contatos com Acentuação**: A agenda tem a capacidade de filtrar contatos por texto, mesmo quando há a presença de acentuações nos nomes dos contatos.

## Conceitos Aplicados

- **CLI (Command Line Interface) do Angular**: Utilização do Angular CLI para criar, gerenciar e construir a aplicação Angular.
  
- **Sintaxe de Template**: Implementação de templates Angular para renderizar a interface do usuário.
  
- **@Input**: Utilização do decorador `@Input` para passar dados de um componente pai para um componente filho.
  
- **NgModel**: Utilização do `NgModel` para criar ligação de duas vias, permitindo a atualização de dados tanto no modelo quanto na view.
  
- **@For**: Utilização do decorador `@For` para realizar iteração sobre uma lista de contatos e renderizá-los na interface.

## Instruções de Uso

1. **Instalação**: Clone o repositório e instale as dependências usando `npm install`.
  
2. **Execução**: Execute o comando `ng serve` para iniciar o servidor de desenvolvimento. Navegue até `http://localhost:4200/` para acessar a aplicação.

3. **Carregamento de Contatos**: Os contatos são carregados automaticamente da fonte de dados JSON.

4. **Filtragem**: Utilize o campo de busca para filtrar os contatos por nome. O filtro é sensível a acentuações.

## Como Contribuir

1. Fork o repositório.
  
2. Crie uma nova branch (`git checkout -b feature/nome-da-feature`).
  
3. Faça commit das suas mudanças (`git commit -am 'Adiciona nova feature'`).
  
4. Faça push para a branch (`git push origin feature/nome-da-feature`).
  
5. Crie um novo Pull Request.

---

