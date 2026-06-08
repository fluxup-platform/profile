# FluxUp

**FluxUp** é uma plataforma de gestão de times ágeis que centraliza o acompanhamento de sprints, tarefas e compromissos de desenvolvimento — integrando-se a ferramentas como Jira, Azure DevOps e Trello para oferecer visibilidade em tempo real do fluxo de trabalho.

---

## O que resolve

Times ágeis frequentemente perdem visibilidade sobre o andamento real das demandas entre uma daily e outra. O FluxUp substitui controles manuais (listas em bloco de notas, chats) por um painel centralizado onde cada desenvolvedor registra explicitamente o status esperado de cada atividade até a próxima daily — tornando o comprometimento do time rastreável e auditável.

---

## Repositórios

| Repositório | Descrição |
|---|---|
| [fluxup-frontend](https://github.com/fluxup-platform/fluxup-frontend) | Interface web — calendário de tarefas, squads e configurações de workspace |
| [fluxup-bff](https://github.com/fluxup-platform/fluxup-bff) | BFF NestJS — agrega e transforma dados entre o frontend e os serviços de backend |
| [fluxup-backend](https://github.com/fluxup-platform/fluxup-backend) | API principal — lógica de negócio, gestão de tarefas e orquestração de fluxo |
| [fluxup-connector](https://github.com/fluxup-platform/fluxup-connector) | Conector — abstrai e padroniza o acesso a Jira, Azure DevOps, Trello e Confluence |
| [fluxup-installer](https://github.com/fluxup-platform/fluxup-installer) | CLI de instalação — configura e sobe o ambiente on-premises via Docker Compose |
| [fluxup-infrastructure](https://github.com/fluxup-platform/fluxup-infrastructure) | IaC Terraform — provisiona e versiona recursos de nuvem por ambiente |
| [fluxup-mock-api-connector](https://github.com/fluxup-platform/fluxup-mock-api-connector) | Mock server — simula a API do conector para desenvolvimento e testes |

---

## Discussões

Tem uma ideia, encontrou um bug ou quer sugerir uma melhoria? Use o portal de discussões:

👉 [github.com/fluxup-platform/profile/discussions](https://github.com/fluxup-platform/profile/discussions)

---

## Licença

Todos os repositórios desta organização estão protegidos por licença proprietária.  
Veja o arquivo `LICENSE` em cada repositório para mais detalhes.
