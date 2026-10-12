# Última Onda

Jogo de sobrevivência em ondas contra zumbis, em primeira pessoa, com visual poligonal (PS2/N64), 46 armas com raridades, chicletes e cooperativo online para até 4 jogadores.

## Como colocar no ar (GitHub Pages)

1. Crie uma conta em github.com (se ainda não tiver) e clique em **New repository**. Dê um nome, por exemplo `ultima-onda`, deixe **Public** e crie.
2. Na página do repositório, clique em **uploading an existing file** e envie todos os arquivos desta pasta: `index.html`, `manifest.webmanifest`, `icon.svg`, `.nojekyll` e este `README.md`. Clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
4. Espere cerca de um minuto. O endereço fica `https://SEU-USUARIO.github.io/ultima-onda/`. Mande esse link para os amigos.

## Jogar com os amigos

1. Todo mundo abre o link do site.
2. Um jogador toca em **Cooperativo online**, digita um apelido, escolhe o mapa no menu antes e toca em **Criar sala**.
3. Ele passa o código da sala (ex.: `zm4k2q`) para os outros, que tocam em **Cooperativo online**, digitam o código e tocam em **Entrar**.
4. Quando todos aparecerem na lista, o anfitrião toca em **Iniciar partida**.

Observações:

- O anfitrião roda os zumbis. Ele precisa deixar a aba aberta e em primeiro plano.
- A conexão entre jogadores usa WebRTC pelo serviço público do PeerJS. Em redes muito restritas (alguns 4G ou Wi-Fi de escola) pode falhar; troque de rede e tente de novo.
- No celular, use **Adicionar à tela inicial** no navegador: o jogo abre em tela cheia e deitado.
- O melhor resultado e as configurações ficam salvos no próprio aparelho.

## Controles

Computador: WASD mover, Shift correr, Espaço pular, C deslizar, clique atirar, R recarregar, V facada, T inspecionar a arma (dá para andar enquanto inspeciona; a animação repete até você atirar, recarregar, dar facada, trocar, mirar, correr ou pular), botão direito ou X mirar, G mascar chiclete, E comprar ou abrir, Q ou roda do mouse trocar de arma, Esc pausar.
Celular: joystick à esquerda, arraste à direita para olhar e use os botões (INSP inspeciona a arma, MIRA liga e desliga a mira). Em Configurações dá para mudar a sensibilidade e mover os botões.

## Se o cooperativo não conectar

- Todos precisam abrir o link `https://SEU-USUARIO.github.io/ultima-onda/` (https), e o anfitrião deve **criar a sala primeiro** e deixar a aba aberta.
- Digite o código exatamente como aparece (maiúsculas/minúsculas não importam).
- Se aparecer "Demorou demais" ou "servidor de conexão", troque de rede (Wi-Fi ↔ 4G) e tente de novo.
- Importante: o `.nojekyll` começa com ponto e pode não aparecer na hora de enviar; o jogo funciona sem ele.

## Skins de arma

No menu (ou pausado), toque em **Skins**. Escolha uma arma (ou "Todas as armas"), use um modelo pronto ou crie o seu: cor do **corpo**, do **cabo** e dos **detalhes**, mais um padrão (lisa, camuflagem, listras, xadrez ou pontos). A prévia mostra o resultado e tudo fica salvo neste aparelho. **Usar em todas as armas** aplica a skin atual a todas, e **Remover skin** volta ao visual original.
