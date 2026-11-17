# Pontinho

Jogo de cartas Pontinho para o celular — contra o computador (2–4 jogadores), duas pessoas no mesmo aparelho, ou duas pessoas online, cada uma no seu celular.

Jogue em: https://priscillasantana.github.io/pontinho/

No iPhone, abra no Safari e toque em **Compartilhar → Adicionar à Tela de Início** para jogar em tela cheia, como um app.

## Jogar online

Em **Novo jogo**, uma pessoa toca em **Criar sala** e recebe um código de 4 letras (ou manda o convite com o link). A outra toca em **Entrar** e digita o código.

O serviço gratuito do [PeerJS](https://peerjs.com) só apresenta um celular ao outro pelo código; depois disso, as jogadas vão direto de um aparelho para o outro (WebRTC), sem servidor próprio. O celular de quem criou a sala comanda o jogo e manda para o outro só o que ele pode ver. Se a conexão cair, o jogo tenta reconectar sozinho.

Limites: em algumas redes (alguns dados móveis ou Wi-Fi corporativo) os celulares não conseguem se conectar direto; e quem criou a sala precisa manter o jogo aberto.

Versão atual e histórico de mudanças: [CHANGELOG.md](CHANGELOG.md). No jogo, a versão aparece no canto inferior direito da tela.
