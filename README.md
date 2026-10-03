# Face Doctor Água Verde — Demo de website

Protótipo conceitual para apresentação comercial.

## Como abrir
Abra `index.html` no navegador (com internet, para carregar as fontes do Google e o mapa).

## Estrutura
- `index.html` — site completo em um único arquivo (HTML, CSS e JavaScript). As imagens já estão embutidas nele.
- `assets/` — cópias das imagens usadas no site (recortes das fotos da clínica e o logo FD em PNG transparente), para edição ou reutilização.

## Funcionalidades
- Navegação lateral (desktop) e menu compacto (tablet/celular)
- Modo claro/escuro com o ícone de espelho (preferência salva no navegador)
- Tecnologias com espaço reservado (“?”) para as imagens dos equipamentos
- Lista editorial de tratamentos, comparador antes/depois, carrossel de avaliações
- Mapa do Google Maps na seção de localização
- Agendamento em 4 etapas dentro do site + área “Meu perfil” com próximos horários, histórico, remarcação e cancelamento
- Dica: em “Meu perfil”, use “Ver perfil demonstrativo” para mostrar um perfil já preenchido

## Observação
Os agendamentos ficam salvos apenas no navegador de quem usa (localStorage). Para uso real, seria necessário integrar um back-end ou sistema de agenda da clínica.
