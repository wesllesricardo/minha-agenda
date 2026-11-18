# Minha Agenda

Agenda pessoal no padrão visual da E3 Company: calendário do mês, reuniões por dia, anotações em cada data e lembretes.

**Abrir a agenda:** https://wesllesricardo.github.io/minha-agenda/

## O que ela faz

- Marca reuniões com horário, categoria, link da chamada, local e anotações.
- Guarda anotações livres em cada dia.
- Marca reuniões como concluídas: elas ficam riscadas e saem da lista de próximas e dos avisos.
- Cria reuniões fixas em massa: toda semana (em um ou mais dias), a cada 2 semanas, todo dia útil ou todo mês, até a data que você escolher (até 150 de uma vez). Dá para editar ou excluir só uma ou a série a partir daquela data.
- Mostra as próximas reuniões e avisa na tela 15 minutos antes, enquanto a página está aberta.
- Exporta reuniões em `.ics`, com alarmes de 1 hora e de 15 minutos antes, para o calendário do celular ou do Outlook.
- Envia uma reunião para o Google Agenda com um clique.

## Onde ficam os dados

Nesta versão do GitHub Pages, as reuniões e anotações ficam salvas só no navegador de quem usa (`localStorage`). Nada é enviado para servidor nenhum. Se você limpar os dados do navegador, tudo é apagado.

É um arquivo único (`index.html`), sem dependências nem etapa de build.
