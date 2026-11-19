<p align="center">
  <a href="https://bashln.github.io/portfolio/">
    <img
      src="https://bashln.github.io/portfolio/assets/images/og.png"
      alt="Leonam Duarte (bashln), desenvolvedor júnior full stack e frontend"
      width="100%"
    />
  </a>
</p>

<h1 align="center">Leonam Duarte · bashln</h1>

<p align="center">
  Desenvolvedor júnior full stack e frontend em Caxias do Sul, RS.<br />
  Aberto a vagas remotas ou híbridas.
</p>

<p align="center">
  <a href="https://bashln.github.io/portfolio/"><img src="https://img.shields.io/badge/portf%C3%B3lio-abrir-3fb950?style=flat-square" alt="Portfólio" /></a>
  <a href="https://bashln.github.io/portfolio/assets/cv/leonam-duarte-cv-dev-jr-2026.pdf"><img src="https://img.shields.io/badge/curr%C3%ADculo-PDF-fb923c?style=flat-square" alt="Currículo em PDF" /></a>
  <a href="https://www.linkedin.com/in/leonam-monteiro-679200362"><img src="https://img.shields.io/badge/LinkedIn-leonam--monteiro-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:lpdmonteiro@gmail.com"><img src="https://img.shields.io/badge/email-lpdmonteiro%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
</p>

## O que eu construo

Apps Android que funcionam sem conta e sem servidor, ferramentas de terminal em Go e interfaces web sem build. Em todos, menos peça móvel e mais comportamento verificável.

## Em destaque

### [MeuGasto](https://github.com/bashln/MeuGasto)

<p align="center">
  <img src="docs/screenshots/meugasto-inicio.jpg" width="240" alt="Tela inicial do MeuGasto com resumo de gastos do mês" />
  <img src="docs/screenshots/meugasto-compras.jpg" width="240" alt="Lista de compras com estabelecimentos ocultados e valores por compra" />
  <img src="docs/screenshots/meugasto-relatorios.jpg" width="240" alt="Relatórios com tendência de gastos e distribuição por mercado" />
</p>

Registra compras de supermercado pelo QR Code da NFC-e. O usuário escaneia o cupom, o app consulta a SEFAZ do estado e grava estabelecimento, data, itens e preços no banco local, sem digitar item por item. A nuvem é opcional e as tabelas de analytics não guardam identidade, com pelo menos cinco contribuintes por agregado.

Kotlin, Jetpack Compose, Room, Ktor e Supabase. [Código](https://github.com/bashln/MeuGasto) e [APK](https://github.com/bashln/MeuGasto/releases).

### [TCG Coleção](https://github.com/bashln/tcg-colecao)

<p align="center">
  <img src="docs/screenshots/tcg-inicio.jpg" width="260" alt="Tela inicial do TCG Coleção com valor da coleção e cartas mais valiosas" />
  <img src="docs/screenshots/tcg-cartas.jpg" width="260" alt="Grade da coleção com cartas, variante, condição e preço pago" />
</p>

Organiza coleções de cartas Pokémon no Android e no navegador. O reconhecimento da carta roda no aparelho, a coleção funciona offline e a sincronização entre as duas versões é opcional. O domínio é um módulo Kotlin puro, testado na JVM, separado do módulo Android.

Kotlin, Compose, Room, ML Kit, React 19, TypeScript e Supabase.

### [EcoRota](https://github.com/bashln/ecorota)

Analisa cada viagem com GPS e acelerômetro, dá uma nota de 0 a 100, explica quais comportamentos custaram pontos e estima a economia de combustível. Sem conta, sem analytics e sem servidor.

Kotlin, Jetpack Compose, Room e OpenStreetMap.

## Outros

- OS-ATE, sistema de ordens de serviço que construí no trabalho. Repositório privado, com a lógica e a suíte de testes preservadas e os dados substituídos por placeholders. Go, Vue 3 e SQLite.
- [pomotui](https://github.com/bashln/pomotui), timer Pomodoro em Go para o terminal, com Bubble Tea. Presets, tempos customizados e contadores por fase.
- [portfolio](https://github.com/bashln/portfolio), meu currículo navegável. Uma página estática, bilíngue, sem build e sem dependências de runtime.
- [scripts](https://github.com/bashln/scripts), automação idempotente de pós-instalação para Arch, Fedora e Ubuntu. Também mantenho temas para Neovim, como o [nvim-outrun](https://github.com/bashln/nvim-outrun).

## Contato

Histórico profissional e formação estão no [portfólio](https://bashln.github.io/portfolio/) e no [LinkedIn](https://www.linkedin.com/in/leonam-monteiro-679200362). Para falar comigo, use o [e-mail](mailto:lpdmonteiro@gmail.com).

<details>
<summary>English</summary>

### Leonam Duarte · bashln

Junior full stack and frontend developer in Caxias do Sul, Brazil. Open to remote or hybrid roles.

I build Android apps that need no account or server, Go terminal tools, and web interfaces without a build step. The projects above are public and most run automated checks in CI. MeuGasto and TCG Coleção ship signed APKs from releases.

Professional history and education are on my [portfolio](https://bashln.github.io/portfolio/?lang=en) and [LinkedIn](https://www.linkedin.com/in/leonam-monteiro-679200362). You can reach me by [email](mailto:lpdmonteiro@gmail.com).

</details>
