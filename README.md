
# Qbank

Qbank é um sistema de gerenciamento de contas bancárias simples, desenvolvido como parte de um projeto de Engenharia de Software. Ele permite que os usuários criem, visualizem, atualizem e excluam contas bancárias, utilizando a metodologia de Desenvolvimento Orientado a Testes (TDD) e integração contínua.

## Funcionalidades

O Qbank possui as seguintes funcionalidades principais:

- **Criar uma conta:** O usuário pode cadastrar uma nova conta bancária fornecendo informações como o nome do titular e o saldo inicial.
- **Visualizar contas:** O usuário pode consultar uma lista com as contas cadastradas.
- **Atualizar uma conta:** O usuário pode alterar os dados de uma conta existente.
- **Excluir uma conta:** O usuário pode excluir uma conta de sua lista de contas.

## Como rodar o projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/SEU_USUARIO/qbank.git
   ```

2. **Abra o projeto no NetBeans:**

   Abra o NetBeans e selecione "Abrir Projeto". Navegue até o diretório do projeto clonado e abra o arquivo de projeto.

3. **Rodando o projeto:**

   O Qbank é uma aplicação Java, então para rodá-lo basta rodar a classe principal do projeto. Caso haja alguma configuração específica, consulte a documentação ou os arquivos de configuração no projeto.

## Como rodar os testes

Os testes foram desenvolvidos utilizando a metodologia de Desenvolvimento Orientado a Testes (TDD). Para rodá-los, siga as instruções abaixo:

1. Abra o **terminal** ou **PowerShell** no diretório do projeto.
   
2. **Execute os testes com Maven:**

   Para rodar todos os testes, execute o seguinte comando no terminal:

   ```bash
   mvn test
   ```

3. Os resultados dos testes serão exibidos no terminal, mostrando se os testes passaram ou falharam.

## Como contribuir

1. **Fork** o repositório.
2. Crie uma branch para a sua feature (`git checkout -b feature/nome-da-feature`).
3. Faça o commit das suas alterações (`git commit -m 'Adicionando nova funcionalidade'`).
4. **Push** para a sua branch (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request no GitHub para revisão e merge.

---

### **Licença**

Este projeto é licenciado sob a [MIT License](LICENSE).
