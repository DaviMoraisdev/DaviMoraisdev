# Roadmap de Estudos e Projetos Futuros

[Voltar ao perfil](../README.md)

Este documento guarda o planejamento de médio e longo prazo. O que já está construído e pode ser verificado fica no [perfil](../README.md); aqui ficam também os itens que ainda são intenção.

## Roadmap de aprendizado

```txt
Fundamentos
  [x] Fundamentos de programação
  [x] Git e GitHub
  [x] HTML, CSS e JavaScript
  [x] PHP com banco de dados

Desenvolvimento Back-End
  [x] Node.js e APIs REST
  [x] TypeScript aplicado a projetos
  [x] Mensageria com RabbitMQ (outbox, consumo idempotente e dead-letter queue)
  [~] Microsserviços e comunicação entre serviços (API Gateway ainda pendente)
  [~] Autenticação e segurança em APIs (hardening previsto na fase 7 do e-commerce)
  [~] Testes automatizados (ampliar a cobertura do auth-service e levar todos os serviços ao CI)
  [~] Pagamentos com provedor externo (fase 5 do e-commerce)
  [ ] Observabilidade e monitoramento

Sistemas e Infraestrutura
  [x] Ambiente Linux com WSL2 e VM de laboratório
  [x] Docker Compose para bancos de dados e mensageria em ambiente local
  [~] Fundamentos de Linux (LPI Linux Essentials)
  [~] Integração contínua com GitHub Actions (hoje em dois dos sete serviços)
  [ ] Containerização dos serviços da aplicação com Dockerfile
  [ ] Implantação contínua
  [ ] Administração de sistemas Red Hat (RHCSA)
  [ ] Automação de sistemas com Ansible (RHCE)
  [ ] Administração de sistemas Linux (LPIC-1)
  [ ] Fundamentos de cloud e IA na AWS
  [ ] Desenvolvimento de aplicações em cloud (AWS Developer Associate)
  [ ] Machine learning em cloud (AWS ML Engineer Associate)

Horizonte de longo prazo
  [ ] Infraestrutura como código (Terraform Associate)
  [ ] Orquestração de containers com Kubernetes (CKA)

Legenda: [x] concluído · [~] em andamento · [ ] planejado
```

A ordem e a situação de cada certificação estão em [`certificacoes.md`](certificacoes.md).

## Projetos futuros

Ideias registradas para aprofundar infraestrutura, dados e observabilidade. Nenhuma delas foi iniciada.

| Projeto | Área | Proposta |
|---|---|---|
| Cloud Resource Manager | Infraestrutura | Gerenciamento e monitoramento de servidores, com status, logs, alertas e painel administrativo |
| InfraSight | Observabilidade | Dashboard de containers com métricas de CPU, memória e rede em tempo real |
| CyberShield | Segurança | Plataforma de monitoramento e detecção de ameaças, unindo segurança e dados |
| Detector de phishing em e-mails | Dados | Classificação de mensagens com machine learning |

## Método de trabalho

Nos projetos, registro além do código o raciocínio por trás dele: a justificativa das decisões de arquitetura, como executar o ambiente localmente, os problemas que surgiram e como foram resolvidos. O fluxo é planejar, documentar, implementar por fases, abrir Pull Request e testar antes do merge.

Na trilha de sistemas, aplico o mesmo princípio: estudo com cronograma definido, prática em laboratório e registro versionado de cada etapa, incluindo os erros e as correções.
