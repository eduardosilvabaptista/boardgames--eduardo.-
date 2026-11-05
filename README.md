# Boardgames Eduardo — Android PWA

## Instalação no Android
1. Publica o conteúdo desta pasta num alojamento HTTPS (por exemplo, GitHub Pages).
2. Abre o endereço publicado no Chrome do Android.
3. Menu ⋮ → **Instalar aplicação** ou **Adicionar ao ecrã inicial**.
4. Confirma a instalação.

## Funcionalidades
- Coleção de jogos manual, com campos para BGG ID, ano, jogadores, duração, peso, capa e notas.
- Pesquisa no BGG por abertura do site.
- Tentativa de importação de detalhes através da API XML do BGG (pode ser bloqueada por CORS; nesse caso, preencher manualmente).
- Registo de partidas, participantes, lugares e notas.
- Pontuação proporcional ao número de jogadores; empates dividem a soma dos pontos das posições ocupadas.
- Ranking geral, anual e por jogo; dashboard e histórico.
- Dados guardados localmente no navegador (localStorage).

## Limitações importantes
Esta versão é um protótipo PWA local. Os dados ficam neste dispositivo/navegador e não sincronizam entre telemóveis. Para sincronização multi-dispositivo é necessário adicionar uma base de dados e autenticação. A importação BGG depende da disponibilidade da API e das políticas de acesso do BGG.
