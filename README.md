<details>
  <summary><strong>👨‍💻 Desenvolvido:</strong></summary><br />

Neste projeto tive que:

1. **_Conteinerizar_** aplicações;
2. Criar uma conexão entre elas;
3. Orquestrar seu funcionamento.

Temos uma aplicação full-stack neste repositório: um **aplicativo de tarefas**! Esta aplicação precisa ser conteinerizada para funcionar. Eu desenvolvi os arquivos de configuração para cada frente específica: `Front-end`, `Back-end` e, no nosso caso, para um aplicativo de `teste` que valida se as aplicações estão se comunicando.

Criei as imagens para as aplicações e configurei essas imagens com o `docker-compose`.

Para isto, utilizei uma série de comandos do `docker` com diferentes níveis de complexidade.

Cada comando foi escrito em seu próprio arquivo no diretorio docker-commands.
</details>

---
  ### Como instalar e configurar:
  1. Clone o repositório
   - git clone git@github.com:Ingrid-Paulino/project-docker-todo-list.git
  2. Entre na pasta do repositório que você acabou de clonar:
   - cd project-docker-todo-list
  3. Instale as dependências
   - npm install
  4. Para rodar o projeto
   - npm start