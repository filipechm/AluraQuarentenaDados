# Caderno de Treino

App de treino para hipertrofia em um único arquivo (`index.html`). É só abrir no navegador, sem instalar nada.

- **Divisões ABC e ABCD** com exercícios, séries, faixa de repetições, descanso e RIR.
- **Registro por série:** carga (kg) e repetições, com carga sugerida pela progressão dupla.
- **Mesociclo de 4 semanas:** Base → Volume (+1 série) → Intensidade (−2 reps, +5% de carga) → Deload (−40%).
- **Calendário:** dias feitos, treinos perdidos e próximas datas sugeridas com a letra do treino e a fase.
- **Cronômetro de descanso** ao concluir cada série.
- **Coach IA** (ao abrir pelo link do Claude): análise do progresso, perguntas ao treinador e troca de exercícios por alternativas sugeridas.
- **Backup** por código copiável (os dados ficam no `localStorage` do navegador).

## Instalar no celular (tela inicial)

O app é um PWA: depois de instalado, abre em tela cheia, com ícone próprio, e funciona sem internet.

1. Publique a pasta em um endereço HTTPS. Pelo GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch**, escolha a branch e a pasta `/ (root)`. O app ficará em `https://<usuario>.github.io/AluraQuarentenaDados/app-treino/`.
2. No celular, abra esse endereço:
   - **Android (Chrome):** menu ⋮ → **Instalar app** (ou "Adicionar à tela inicial").
   - **iPhone (Safari):** botão Compartilhar → **Adicionar à Tela de Início**.

Os treinos ficam salvos no próprio celular. Use **Programa → Backup dos dados** para copiar ou restaurar.
