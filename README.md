## Oi, eu sou o Jhonata

Desenvolvedor de software em Brasília, hoje **Tech Lead de um time de 4 pessoas** na Baratão Combustíveis.

Fui o primeiro desenvolvedor mobile da empresa e construí sozinho o aplicativo até o primeiro milhão de usuários. Depois assumi também o back-end e a automação dos postos. Gosto de sistemas que não podem falhar: pagamentos, antifraude, integração com hardware e operação em produção.

### Em números

| 1 mi | 10 mi+ | 70 mil+ | 500+ |
|:---:|:---:|:---:|:---:|
| usuários com o app que construí sozinho | downloads do aplicativo | transações por dia | postos com automação de bombas |

### Alguns problemas que resolvi

- **Do zero ao primeiro milhão.** App de abastecimento, pagamento e benefícios em React Native, que chegou ao top 30 em Compras na App Store e ao top 10 em Auto e veículos no Google Play.
- **Chargeback abaixo de 1%.** Ajudei a montar a camada antifraude: 3D Secure, verificação de identidade em tempo real, regras de compra e pontuação de crédito por usuário.
- **Vendas que sumiam no Xiaomi.** O sistema encerrava o app enquanto o cliente autorizava o pagamento no banco. Um foreground service manteve o processo vivo e recuperou essas vendas.
- **500 postos com internet instável.** Agente .NET em Windows Service, MQTT com QoS, retry com backoff e comandos idempotentes que nunca autorizam um abastecimento duas vezes. Atualizações chegam a todos os postos e voltam sozinhas à versão anterior se algo falhar.
- **Bombas que travavam sem explicação.** Fui a campo com a fabricante até achar a causa: comandos simultâneos em equipamentos antigos. Um intervalo de 200 ms resolveu.
- **Entrega rápida e segura.** Servidor próprio de CodePush, versão web com React Native Web e CI/CD com testes E2E em Maestro bloqueando releases com regressão.

### Stack

| | |
|---|---|
| **Linguagens** | TypeScript · JavaScript · C# · Ruby · SQL |
| **Aplicações** | React · Next.js · React Native · React Native Web · módulos nativos Android e iOS · Blazor |
| **Serviços** | .NET / ASP.NET Core · Worker Service · Node.js · Ruby on Rails · APIs REST · MQTT |
| **Dados e nuvem** | PostgreSQL · SQL Server · MongoDB · Google Cloud · Heroku · Docker · Linux |
| **Qualidade e operação** | GitHub Actions · Maestro · xUnit · Sentry · Firebase · Grafana · Prometheus · Loki |

### Como eu trabalho

- Entendo o problema antes de escolher a tecnologia, e decido pensando em custo, prazo e risco.
- Código revisado por pull request, testes ligados ao deploy e monitoramento em produção.
- Traduzo o técnico para quem não é técnico: Produto, comercial e parceiros.

### Sobre os repositórios

A maior parte do que construí está em repositórios privados da empresa. Aqui ficam estudos e projetos pessoais.

### Contato

[LinkedIn](https://linkedin.com/in/jhonatabonadio1) · [jhonbonadio@gmail.com](mailto:jhonbonadio@gmail.com)
