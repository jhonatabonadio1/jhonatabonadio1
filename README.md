<h1 align="center">Olá, eu sou o Jhonata 👋</h1>
<h3 align="center">Desenvolvedor de Software & Tech Lead<br>React Native • React • Next.js • TypeScript • .NET • Node.js</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=620&lines=Tech+Lead+de+um+time+de+4+pessoas;App+com+10+milh%C3%B5es%2B+de+downloads;70+mil%2B+transa%C3%A7%C3%B5es+por+dia;500%2B+postos+com+automa%C3%A7%C3%A3o+de+bombas;Sistemas+que+n%C3%A3o+podem+falhar" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/jhonatabonadio1"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jhonbonadio@gmail.com"><img src="https://img.shields.io/badge/Email-jhonbonadio%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Bras%C3%ADlia%2FDF-Remoto-22C55E?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Brasília/DF · Remoto" />
</p>

---

### 🙋‍♂️ Sobre mim

Sou desenvolvedor de software há 5 anos e hoje **Tech Lead de um time de 4 pessoas** (front-end, mobile, back-end e integrações) na Baratão Combustíveis.

Entrei na empresa como o **primeiro desenvolvedor mobile** e construí sozinho o aplicativo, do zero até o primeiro milhão de usuários. Com o app crescendo, assumi pagamentos, antifraude e o back-end, e depois projetei a plataforma que automatiza as bombas de combustível em mais de 500 postos.

Meu forte são **sistemas que não podem falhar**: pagamentos, antifraude, integração com hardware e operação em produção. Também participo da criação de interfaces no Figma, da UX com Produto e de negociações com parceiros, traduzindo o técnico para o negócio.

---

### 📊 Em números

<table align="center">
  <tr>
    <td align="center" width="25%"><h2>1 mi</h2>usuários com o app<br>que construí sozinho</td>
    <td align="center" width="25%"><h2>10 mi+</h2>downloads<br>do aplicativo</td>
    <td align="center" width="25%"><h2>70 mil+</h2>transações<br>por dia</td>
    <td align="center" width="25%"><h2>500+</h2>postos com automação<br>de bombas</td>
  </tr>
</table>

<p align="center">
  🏆 Top 30 em <b>Compras</b> na App Store &nbsp;•&nbsp; Top 10 em <b>Auto e veículos</b> no Google Play
</p>

---

### 🧭 Trajetória

**`set/2021` · Desenvolvedor Mobile React Native** — Baratão Combustíveis
- Primeiro desenvolvedor mobile da empresa: app de abastecimento, pagamento e benefícios construído do zero até o primeiro milhão de usuários.
- Pagamentos com 3D Secure e Apple Pay, login com Google e Apple, módulos nativos Android e iOS.
- Servidor próprio de CodePush, versão web com React Native Web e CI/CD com testes E2E em Maestro.
- Apps para maquininhas POS (Getnet e Cielo), app de validação do frentista e integrações com PicPay e Webmotors.

**Back-end e automação dos postos**
- APIs e integrações em Node.js, C#/.NET e Ruby on Rails, incluindo eSocial e Detrans de vários estados.
- Arquitetura do CTBaratao, que conecta mais de 500 postos com internet instável a um backend central.

**`dez/2025` · Tech Lead Full Stack** — Baratão Combustíveis
- Liderança de um time de 4 pessoas: arquitetura, mentoria e priorização com a gestão.
- Code review obrigatório por pull request, testes E2E vinculados ao deploy e Kanban com limite de WIP.
- Hardening de segurança e monitoramento com Grafana, Prometheus e Loki.

---

### 🧩 Alguns problemas que resolvi

<table>
  <tr>
    <td width="50%" valign="top">
      <b>💳 Chargeback abaixo de 1%</b><br>
      Cartões clonados davam prejuízo real. Ajudei a montar uma camada antifraude com 3D Secure, verificação de identidade em tempo real, regras de compra e pontuação de crédito por usuário.
    </td>
    <td width="50%" valign="top">
      <b>📱 Vendas que sumiam no Xiaomi</b><br>
      No 3D Secure, o sistema encerrava o app enquanto o cliente autorizava a compra no banco. Um foreground service manteve o processo vivo e recuperou essas vendas.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>⛽ 500 postos com internet instável</b><br>
      Agente .NET em Windows Service, MQTT com QoS, retry com backoff exponencial e comandos idempotentes que <b>nunca autorizam um abastecimento duas vezes</b>.
    </td>
    <td width="50%" valign="top">
      <b>🔧 Bombas que travavam sem explicação</b><br>
      Fui a campo com a fabricante até achar a causa: comandos simultâneos em equipamentos antigos. Um intervalo de <b>200 ms</b> entre comandos resolveu.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>🔄 Atualização sem acesso remoto</b><br>
      Um atualizador leva cada versão aos postos e volta sozinho à anterior se a nova falhar. Uma camada de tradução faz o mesmo comando funcionar com equipamentos de fabricantes diferentes.
    </td>
    <td width="50%" valign="top">
      <b>🚀 Entrega rápida e segura</b><br>
      CodePush próprio para corrigir sem esperar as lojas, React Native Web para a versão web e testes E2E com Maestro que <b>bloqueiam releases com regressão</b>.
    </td>
  </tr>
</table>

---

### 🛠️ Stack

<table>
  <tr>
    <td><b>Linguagens</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ruby/ruby-original.svg" alt="Ruby" title="Ruby" width="36" height="36"/>
    </td>
  </tr>
  <tr>
    <td><b>Aplicações</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React / React Native" title="React / React Native" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" alt="Next.js" title="Next.js" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/android/android-original.svg" alt="Android" title="Android nativo" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apple/apple-original.svg" alt="iOS" title="iOS nativo" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/blazor/blazor-original.svg" alt="Blazor" title="Blazor" width="36" height="36"/>
    </td>
  </tr>
  <tr>
    <td><b>Serviços</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dotnetcore/dotnetcore-original.svg" alt=".NET" title=".NET / ASP.NET Core" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rails/rails-plain.svg" alt="Ruby on Rails" title="Ruby on Rails" width="36" height="36"/>
    </td>
  </tr>
  <tr>
    <td><b>Dados e nuvem</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/microsoftsqlserver/microsoftsqlserver-plain.svg" alt="SQL Server" title="SQL Server" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/googlecloud/googlecloud-original.svg" alt="Google Cloud" title="Google Cloud" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/heroku/heroku-original.svg" alt="Heroku" title="Heroku" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="36" height="36"/>
    </td>
  </tr>
  <tr>
    <td><b>Qualidade e operação</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" title="GitHub Actions" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-plain.svg" alt="Firebase" title="Firebase" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/grafana/grafana-original.svg" alt="Grafana" title="Grafana" width="36" height="36"/>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/prometheus/prometheus-original.svg" alt="Prometheus" title="Prometheus" width="36" height="36"/>
      &nbsp;<sub>+ Maestro (E2E), xUnit, Sentry, Loki</sub>
    </td>
  </tr>
  <tr>
    <td><b>Produto</b></td>
    <td>
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg" alt="Figma" title="Figma" width="36" height="36"/>
      &nbsp;<sub>UI, UX e apresentações para o negócio</sub>
    </td>
  </tr>
</table>

---

### 🧠 Como eu trabalho

- **Problema antes da tecnologia:** entendo o que o negócio precisa e decido pensando em custo, prazo e risco.
- **Qualidade como processo:** code review por pull request, testes ligados ao deploy e monitoramento em produção.
- **Bug de ambiente se resolve no ambiente:** quando o log não basta, vou até o posto, o aparelho ou o fornecedor.
- **Comunicação clara:** traduzo o técnico para Produto, comercial e parceiros.

---

### 🔒 Sobre os repositórios

A maior parte do que construí está em repositórios privados da empresa. Aqui ficam estudos, experimentos e projetos pessoais.

---

### 📈 Atividade

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jhonatabonadio1&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&title_color=8B5CF6&icon_color=8B5CF6" alt="Estatísticas do GitHub" height="165" />
  <img src="https://streak-stats.demolab.com/?user=jhonatabonadio1&theme=tokyonight&hide_border=true&ring=8B5CF6&fire=8B5CF6&currStreakLabel=8B5CF6" alt="Sequência de contribuições" height="165" />
</p>

---

### 📬 Vamos conversar?

<p align="center">
  <a href="https://linkedin.com/in/jhonatabonadio1"><img src="https://img.shields.io/badge/LinkedIn-jhonatabonadio1-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:jhonbonadio@gmail.com"><img src="https://img.shields.io/badge/Email-jhonbonadio%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
