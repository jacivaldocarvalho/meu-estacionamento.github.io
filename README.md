# **Meu Estacionamento - Sistema de Gerenciamento de Estacionamento**

Este repositório contém o código-fonte de um sistema de gerenciamento de estacionamento desenvolvido com **TypeScript**, **JavaScript**, **HTML**, e **CSS**. O objetivo do projeto é criar uma interface simples e eficiente para a administração de vagas e veículos de um estacionamento.

## **Índice**

- [Objetivo do Projeto](#objetivo-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Demonstração](#demonstração)
- [Estrutura de Arquivos](#estrutura-de-arquivos)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Evoluções Possíveis para o Projeto](#evoluções-possíveis-para-o-projeto)
- [Referências Bibliográficas](#referências-bibliográficas)
- [Contatos](#contatos)

## **Objetivo do Projeto**

Este sistema foi criado para gerenciar um estacionamento simples, controlando o número de vagas disponíveis e ocupadas, permitindo adicionar veículos ao estacionamento e removê-los. Ele foi desenvolvido utilizando **TypeScript** para maior segurança de tipos, que é transpilado para **JavaScript** para execução no navegador. A interface é responsiva e projetada para ser de fácil utilização, com funcionalidades essenciais para o gerenciamento de vagas.

## **Tecnologias Utilizadas**

- **HTML**: Estruturação da página web.
- **CSS**: Estilização da interface.
- **JavaScript**: Implementação da lógica de controle de vagas.
- **TypeScript**: Tipagem estática para melhorar a manutenção e evitar erros em tempo de execução.

## **Demonstração**

Você pode visualizar a aplicação online acessando o seguinte link:

[**Acesse o site - Meu Estacionamento**](https://jacivaldocarvalho.github.io/meu-estacionamento.github.io/)

## **Estrutura de Arquivos**

A estrutura do repositório é a seguinte:

```bash
├── assets/                        # Arquivos de mídia (ex: imagens)
├── index.html                     # Arquivo HTML principal
├── tsconfig.json                  # Configuração do TypeScript
├── style.css                      # Arquivo de estilos CSS
├── script.ts                      # Lógica do TypeScript
└── README.md                      # Documentação do projeto
```

## **Como Rodar o Projeto**

1. **Clonar o Repositório**:

   Para rodar o projeto localmente, clone o repositório para sua máquina:

   ```bash
   git clone https://github.com/jacivaldocarvalho/meu-estacionamento.github.io.git
   ```

2. **Instalar Dependências (se necessário)**:

   Caso deseje compilar o TypeScript localmente, instale as dependências necessárias com o seguinte comando:

   ```bash
   npm install
   ```

3. **Rodar a Aplicação**:

   Abra o arquivo `index.html` em seu navegador para visualizar o site ou utilize um servidor local para servir os arquivos estáticos.

## **Evoluções Possíveis para o Projeto**

### 1. **Implementação de Funcionalidades Avançadas**
   - **Cadastro de veículos**: Adicionar um formulário para cadastrar veículos com informações como modelo, placa, e data de entrada.
   - **Controle de horários**: Implementar o controle do tempo de permanência do veículo e calcular a tarifa automaticamente.
   - **Login de administrador**: Criar uma funcionalidade de autenticação para gerenciar as vagas e visualizar o histórico de entradas e saídas.

### 2. **Integração com Backend**
   - **API RESTful**: Criar uma API em **Node.js** ou **Python** para armazenar dados de veículos e vagas em um banco de dados, permitindo persistência das informações.
   - **Autenticação**: Implementar um sistema de login para gerenciar o acesso ao sistema.

### 3. **Melhoria na Interface**
   - **Melhorias no Design**: Utilizar frameworks como **Bootstrap** ou **Material UI** para melhorar a aparência e responsividade da aplicação.
   - **Interatividade**: Adicionar animações ou transições para uma experiência de usuário mais fluída.

### 4. **Testes Automatizados**
   - **Testes Unitários**: Utilizar ferramentas como **Jest** para realizar testes unitários nos scripts TypeScript.
   - **Testes de Interface**: Implementar testes de interface com ferramentas como **Cypress**.

## Contribuições

Se você tiver sugestões de melhorias ou encontrar problemas com o script, sinta-se à vontade para abrir um **issue** ou submeter um **pull request**.

## Contatos e Network

- **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/jacivaldocarvalho/) 👔
- **E-mail**: [E-mail](mailto:jacivaldocarvalho@gmail.com) 📧
- **GitHub**: [GitHub](https://github.com/jacivaldocarvalho) 🐙
- **Medium**: [Medium](https://medium.com/@jacivaldocarvalho) ✍️

Sempre aberto a novas conexões e oportunidades de aprendizado!

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## **Referências Bibliográficas**

- [Documentação Oficial do TypeScript](https://www.typescriptlang.org/docs/)
- [Documentação de JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Documentação de CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [Introdução ao Desenvolvimento Web](https://developer.mozilla.org/pt-BR/docs/Learn/Getting_started_with_the_web)

