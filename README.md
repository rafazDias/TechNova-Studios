# Task Manager API - TechNova Solutions

## 📝 Descrição do Projeto
Este projeto consiste em uma API de Gerenciamento de Tarefas desenvolvida para a TechNova Solutions[cite: 4, 20]. O objetivo principal é modernizar o processo de desenvolvimento da empresa, substituindo o compartilhamento de código via arquivos ZIP por um fluxo de trabalho profissional utilizando Git[cite: 6, 12, 14].

## 🛠 Tecnologias Utilizadas
* **Linguagem/Stack:** [Inserir Python, Node.js ou PHP] [cite: 26, 27, 28, 29]
* **Versionamento:** Git [cite: 12]
* **Padronização:** Conventional Commits [cite: 55, 56]

## 🚀 Funcionalidades Mínimas
* Criar tarefa [cite: 22]
* Listar tarefas [cite: 23]
* Atualizar tarefa [cite: 24]
* Deletar tarefa [cite: 25]

## 🌿 Estratégia de Branches
Adotamos o seguinte fluxo de ramificação para garantir a organização[cite: 38, 39]:
* **main:** Versão estável em produção[cite: 40].
* **produção:** Branch específica para o ambiente de produção[cite: 41].
* **develop:** Branch principal para integração de novas funcionalidades[cite: 42].
* **integração:** Branch para testes de integração antes do merge final[cite: 43].
* **feature/*:** Utilizada para o desenvolvimento de novas funcionalidades[cite: 44].
* **hotfix/*:** Destinada a correções urgentes diretamente em produção[cite: 45].

## 🔄 Fluxo de Desenvolvimento
O processo padrão para contribuição segue estas etapas[cite: 47, 48]:
1. Criar uma branch `feature/` a partir da `develop`[cite: 49].
2. Desenvolver a funcionalidade com commits organizados[cite: 50, 51].
3. Abrir um **Pull Request** com descrição clara do que foi feito e como testar[cite: 52, 68, 70].
4. Realizar o merge na branch `develop` após aprovação[cite: 53].
5. Simular a release para a branch `main`[cite: 54].

> **Nota sobre Hotfixes:** Em caso de bugs em produção, a branch `hotfix/` é criada a partir da `main`, corrigida, e o merge é feito de volta tanto para a `main` quanto para a `develop`[cite: 72, 73, 74, 75, 76, 77].

## 📌 Padrão de Commits
Os commits devem seguir os prefixos abaixo[cite: 55, 56]:
* `feat:` Adição de novas funcionalidades[cite: 57].
* `fix:` Correção de bugs[cite: 58].
* `docs:` Alterações na documentação[cite: 59].
* `refactor:` Melhorias na estrutura do código sem alterar funcionalidade[cite: 60].

## 🏷 Versionamento
Utilizamos o **Versionamento Semântico** com o uso de Tags no Git[cite: 61, 62, 63, 67]:
* **v1.0.0** [cite: 64]
* **v1.1.0** [cite: 65]
* **v1.1.1** [cite: 66]

## 📁 Estrutura do Projeto
```text
├── src/                # Código fonte da API
├── .gitignore          # Arquivos ignorados pelo Git [cite: 36]
├── README.md           # Documentação do projeto [cite: 35]
└── [Outros arquivos de configuração da stack]
