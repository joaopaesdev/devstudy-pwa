# DevStudy — Planejador de Estudos (PWA)

Aplicação web progressiva (PWA) para organização de rotinas de estudo semanal com suporte offline, cronômetro Pomodoro, estatísticas de progresso e calendário de consistência.

## Funcionalidades
- **Cronograma Semanal:** Organização de matérias e horários de domingo a sábado.
- **Timer Pomodoro:** Ciclos de foco e pausa com alertas sonoros e notificações.
- **Consistência e Métricas:** Acompanhamento de dias ativos e progresso.
- **Offline-First & Backup:** Dados salvos localmente via `localStorage`, com exportação/importação em JSON e suporte offline via Service Worker (`sw.js`).

## Tecnologias Utilizadas
- HTML5, CSS3 e JavaScript puro (Vanilla JS)
- Progressive Web App (`manifest.json` + Service Worker)
- Hospedagem via Vercel
