# Sintaxe

App de celular (iOS e Android) para aprender a programar de verdade: lógica de programação, HTML, CSS, JavaScript e C#, sempre começando do básico do básico.

- **Plano completo com o canvas das 30 telas:** abra [`sintaxe.html`](sintaxe.html) no navegador.
- **Versão online (privada):** https://claude.ai/artifact/Se7FpsGdiJ5cCK5ku1M8QP

## Ideias principais

- **Nível zero em toda linguagem.** Cada trilha começa explicada como para uma criança: primeiro a ideia com coisas do dia a dia, depois o nome técnico, depois o código.
- **Foco: JavaScript dentro do HTML.** Trilha própria ("JS na página") com uma receita única, **pegar → ouvir → reagir**, e a frase "Quando *[evento]* no *[elemento]*, faça *[ação]*" antes do código.
- **Prever antes de executar.** O aluno aposta no resultado antes de rodar o código. O erro de previsão gera uma explicação sobre aquele engano.
- **Revisão espaçada (FSRS)** com uma notificação por dia, só quando há revisão vencendo.
- **Pensado para o celular:** exercícios de toque (prever, apontar o bug, ordenar linhas, montar frases) e um teclado próprio para código.
- **Arena:** modo de prática em luta por turno em que o golpe é o próprio código. Os inimigos são erros clássicos e cada módulo termina com um chefão.
- **Estudo mais profundo:** ensinar o Robô (o aluno explica um conceito para um aprendiz), escrever de memória no dia seguinte, um site pessoal que cresce a cada módulo, desafios fora do app (GitHub e VS Code) e exercícios com temas de que a pessoa gosta.

## Trilhas

| Trilha | Carga | Começa com |
|---|---|---|
| Lógica de programação (base de tudo) | ~30 h | L0 · O computador é um robô obediente |
| Fundamentos da web (HTML) | ~25 h | F0 · A página é feita de caixinhas |
| CSS | ~35 h | C0 · A roupa da página |
| JavaScript | ~45 h | J0 · O computador falando com você |
| **JS na página** (foco) | ~35 h | W0 · O controle remoto da página |
| Integração (projetos) | ~30 h | 4 projetos para o portfólio |
| C# e .NET | ~110 h | CS0 · Conversando com o computador |

Caminhos: **Web** (Lógica → HTML → CSS → JS → JS na página → Integração), **Back-end C#** (Lógica → C#) ou **Full-stack** (os dois, com um projeto final que junta o site e uma API em C#).

## Stack planejada

React Native + Expo · CodeMirror 6 em WebView com teclado de código nativo · execução de HTML/CSS/JS em WebView isolada (offline) · C# compilado em servidor (Roslyn em contêiner isolado) · FSRS + notificações locais · SQLite com sincronização · tutor com Claude via back-end.

## Roadmap

| Fase | Quando | O quê |
|---|---|---|
| 0 · Protótipo | semanas 1–6 | Teclado de código, Lógica L1–L6, JS na página W1–W5 |
| 1 · MVP nas lojas | meses 2–3 | Contas, mapa, revisão com notificações, trilhas base, modo offline |
| 2 · Profundidade | meses 4–6 | Visualizador de execução, Lab CSS, CSS e JS completos |
| 3 · Projetos e tutor | meses 7–9 | Projetos, tutor socrático, portfólio, Arena piloto |
| 4 · C# e .NET | meses 10–14 | Servidor de compilação, trilha C#, projeto full-stack, Arena completa |
