# pipoca-academy-tests

Repositório de testes automatizados do Pipoca Academy utilizando Cypress para validação das principais funcionalidades e garantia de qualidade da plataforma.

## Como fazer um fork e clonar o repositório

Siga os passos abaixo para fazer um fork e clonar este repositório:

### 1. Fazer o Fork do Repositório
1. Acesse a página do repositório no GitHub.
2. No canto superior direito, clique no botão **Fork**.
3. Escolha sua conta ou organização para onde o fork será criado.

### 2. Clonar o Repositório
1. Após criar o fork, acesse o repositório na sua conta do GitHub.
2. Clique no botão **Code** (verde) e copie a URL do repositório (HTTPS ou SSH).
3. Abra o terminal no seu computador.
4. Navegue até o diretório onde deseja salvar o repositório clonado.
5. Execute o comando abaixo para clonar o repositório:

   ```bash
   git clone https://github.com/seu-usuario/pipoca-academy-tests.git
   ```

   Substitua `seu-usuario` pelo seu nome de usuário no GitHub.

6. Entre no diretório do repositório clonado:

   ```bash
   cd pipoca-academy-tests
   ```

Pronto! Agora você tem uma cópia do repositório localmente.

## Como contribuir para o projeto

Siga os passos abaixo para contribuir com o projeto:

1. Certifique-se de que você fez o fork e clonou o repositório (veja as instruções acima).
2. Crie uma nova branch para sua contribuição:

   ```bash
   git checkout -b nome-da-sua-branch
   ```

   Substitua `nome-da-sua-branch` por um nome descritivo para sua alteração.

3. Faça as alterações necessárias no código.
4. Faça o commit das suas alterações:

   ```bash
   git add .
   git commit -m "Descrição clara do que foi alterado"
   ```

5. Envie sua branch para o repositório remoto:

   ```bash
   git push origin nome-da-sua-branch
   ```

6. Acesse o repositório no GitHub e clique em **Pull Request**.
7. Preencha os detalhes da sua Pull Request e envie para revisão.

Certifique-se de solicitar o merge na branch `main` do repositório original.

## Atualização da documentação

Atualize a documentação, se necessário:
   - Certifique-se de que o arquivo `README.md` e outros documentos relevantes estão atualizados para refletir suas alterações.
   - Inclua exemplos ou explicações adicionais, se aplicável.

## Estrutura de Pastas

Abaixo está a estrutura de pastas do repositório:

```
.
├── LICENSE
├── README.md
├── test
├── .gitignore
```

- `LICENSE`: Contém a licença do projeto.
- `README.md`: Arquivo com informações e instruções sobre o projeto.
- `test`: Contém os testes automatizados do projeto.
- `.gitignore`: Arquivo que especifica quais arquivos ou pastas devem ser ignorados pelo Git.
