# Uppercut!

Jogo de boxe em primeira pessoa num mapa aberto, feito com Three.js. Você luta contra CPUs ou contra um amigo na mesma tela, abre baús escondidos e coleciona 50 luvas especiais.

![Lutadores nadando no lago](screenshot.png)

## Como jogar

Abra o link do GitHub Pages, ou abra o `index.html` no navegador (Chrome, Edge ou Firefox). Não precisa instalar nada.

### Instalar como aplicativo

Pelo link do GitHub Pages, o jogo pode ser instalado e ganha ícone próprio:

- **Chrome ou Edge no computador:** clique no ícone de instalar na barra de endereço (um monitor com uma setinha) ou abra o menu ⋮ e escolha **Instalar Uppercut!**.
- **Android:** no Chrome, abra o menu ⋮ e toque em **Instalar app** ou **Adicionar à tela inicial**.
- **iPhone/iPad:** no Safari, toque em Compartilhar e depois em **Adicionar à Tela de Início**.

Depois de aberto uma vez, o jogo também funciona sem internet.

Também dá para rodar com um servidor local:

```bash
npx serve .
```

### No celular

O jogo funciona no celular com o aparelho deitado: joystick à esquerda para andar (empurre até a borda para correr), arraste no lado direito da tela para olhar e use os botões **Soco**, **Forte**, **Defesa** (segure) e **Pular**. O botão **II** pausa. No celular os mapas gigantes têm menos árvores e pedras para o jogo ficar mais leve.

### Controles

| Ação | Teclado e mouse | Controle de videogame |
|---|---|---|
| Andar | W A S D | analógico esquerdo |
| Olhar | mouse | analógico direito |
| Soco | clique esquerdo | RT |
| Soco forte | clique direito | RB |
| Defender | Q (segurar) | LT |
| Pular / nadar para fora | Espaço | A |
| Correr / nadar rápido | Shift | L3 |
| Pausar | Esc | |

No modo **Amigo na mesma tela**, o Jogador 2 usa o controle ou o teclado: I J K L para andar, setas para olhar, Enter para socar, Shift direito para o soco forte, P para defender e O para pular.

## O que tem no jogo

- **3 modos:** contra CPUs (até 30), amigo na mesma tela (tela dividida) e online com amigos por código de sala.
- **11 mapas:** Ilha Verde (pequena) e 10 mapas gigantes: Floresta Gigante, Deserto Dourado, Montanhas Nevadas, Arquipélago Tropical, Vale do Vulcão, Campo de Flores, Cânion Vermelho, Floresta de Outono, Pântano dos Cogumelos e Terra dos Doces.
- **Lutas por tempo:** 3, 5, 10 ou 15 minutos. Ganha quem tiver mais nocautes.
- **100 luvas especiais** em 4 raridades (comum, rara, épica e lendária). Nos baús espalhados pelo mapa você usa a luva durante a luta; para usar sempre, compre na **Loja de luvas** com moedas (cada nocaute vale 1 moeda; comum 10, rara 20, épica 50, lendária 100) e escolha **Usar**. Cada luva tem visual próprio: estampas, fogo, gelo, raios, asas, espinhos, coroa e brilho nas lendárias.
- 🤖 **Cada CPU usa uma luva diferente** conforme a dificuldade: Fácil = luvas Comuns, Normal = Raras, Difícil = Épicas e Lendárias
- 👑 **Luva Suprema**: prêmio por ter todas as 100 luvas — toda branca, com 3 coroas brancas de joias azuis flutuando em volta. Ao equipar, você ganha a **Coroa Suprema** flutuante e o **Traje Supremo** branco e azul pro seu lutador. Com ela, todos os combos viram **Supremos** (Supremo Uppercut, Suprema Metralhadora…) e ficam 6x mais fortes, com área 2x maior e uma Suprema Metralhadora que enche a tela com 50 luvas. Alguns ganham versões especiais: Supremo Furacão (6 furacões que viram um furacão gigante e puxam os inimigos), Supremo Soco Voador (segure o soco e voe para qualquer direção, sem limite de tempo), Supremo Uppercut (luva gigante que lança o alvo lá no céu), Supremo Martelo (luva gigante que cai do céu), Supremo Meteoro (chuva de meteoros) e Supremo Contra-ataque (onda de choque)
- 💥 **Hiper Explosão** (luvas lendárias e Luva Suprema): aperte **E** (U ou Y no controle do Jogador 2, botão 💥 no celular) para soltar uma explosão que joga todo mundo pra longe. Recarrega em 12 s (6 s na Suprema, que explode bem maior)
- **Luva Suprema:** uma luva mítica de prêmio, que você ganha quando tiver todas as outras 100.
- **Kits médicos** espalhados pelo mapa devolvem 40 de vida e voltam depois de 20 segundos.
- **Natação:** os lagos são fundos e você precisa nadar.
- **Personagem personalizável:** 50 penteados (filtro para meninos e meninas), 20 roupas, 10 acessórios (bochechas rosadas, sardas, óculos, medalha, cinturão e outros) e cores de pele, cabelo e roupa. O visual fica salvo e aparece para os outros jogadores no online.
- **Minimapa** com adversários e baús.

### Combos

| Combo | Como fazer |
|---|---|
| Uppercut | soco, soco, forte |
| Metralhadora | 4 socos (segure o soco para continuar, até 4 s) |
| Martelo | forte, forte |
| Furacão | soco, forte, soco, forte (segure o soco para continuar, até 5 s) |
| Meteoro | pule e dê um soco forte no ar |
| Contra-ataque | defenda um golpe e solte um soco forte |
| Soco Voador | correndo, soco forte |
| Tubarão | na água, nadando rápido, soco forte |
| Onda Gigante | na água: forte, forte |
| Redemoinho | na água: soco, forte, soco, forte |
| Rajada de Bolhas | na água: 4 socos |
| Salto do Golfinho | pule para fora da água e dê um soco forte no ar |

Cada golpe seguido sem apanhar aumenta sua força em 5%, até +50%.

## Publicar no GitHub Pages

1. Crie um repositório e envie os arquivos desta pasta.
2. No repositório, vá em **Settings → Pages**.
3. Em **Source**, escolha a branch `main` e a pasta `/ (root)` e salve.
4. Depois de um ou dois minutos, o jogo fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Jogar online com amigos

1. Escolha **Online com amigos**, digite um apelido, escolha o mapa e clique em **Criar sala**.
2. O código da sala aparece no canto da tela. Passe o código para seus amigos.
3. Eles abrem o jogo pelo mesmo link, escolhem **Online com amigos**, digitam o código e clicam em **Entrar**.

A conexão é direta entre os computadores (WebRTC, usando a biblioteca [PeerJS](https://peerjs.com) e o servidor gratuito dela só para os jogadores se acharem). A sala fica aberta enquanto quem criou estiver com o jogo aberto. Em algumas redes (escola, empresa, alguns 4G) a conexão pode ser bloqueada.

Quando o jogo é aberto dentro do Claude, o modo online usa as salas do Claude, com lista de amigos e convites.

A coleção de luvas, a luva padrão, o apelido e o último mapa escolhido ficam salvos no navegador (localStorage).

## Contas e salvamento

No menu, clique em **👤 Conta**.

- **Código de salvamento:** clique em *Gerar meu código*, copie e cole no outro aparelho em *Carregar código*. Funciona sempre, sem configurar nada. O código só adiciona luvas, nunca apaga.
- **Contas online (e-mail e senha):** guardam o progresso na internet e funcionam em qualquer aparelho. Para ligar, siga os passos abaixo uma vez só.

### Como ligar as contas online (Firebase, grátis)

1. Entre em **console.firebase.google.com** com sua conta Google e clique em **Criar projeto** (pode chamar de `uppercut`). O Google Analytics pode ficar desligado.
2. No menu da esquerda, abra **Criação > Authentication**, clique em **Vamos começar**, escolha **E-mail/senha**, ative e salve.
3. Ainda em Authentication, abra **Configurações > Domínios autorizados** e adicione `elfox-hub.github.io`.
4. Abra **Criação > Firestore Database**, clique em **Criar banco de dados**, escolha um local (ex.: `southamerica-east1`) e o **modo de produção**.
5. Na aba **Regras** do Firestore, apague tudo, cole isto e clique em **Publicar**:

```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /saves/{uid} {
      allow read, write: if request.auth != null && request.auth.uid == uid;
    }
  }
}
```

6. Clique na engrenagem **⚙ > Configurações do projeto**, desça até **Seus apps** e clique no ícone **</>** (Web). Dê um nome, registre e copie os valores de `firebaseConfig`.
7. No GitHub, abra o arquivo **firebase-config.js**, clique no lápis ✏️ e troque cada `COLE_AQUI` pelo valor correspondente. Clique em **Commit changes**.
8. Espere uns minutos, abra o jogo e aperte **Ctrl+Shift+R**. Em **👤 Conta** vão aparecer os campos de e-mail e senha.

Os valores do `firebase-config.js` não são senha: pode deixar no GitHub. Quem protege as contas são as regras do passo 5.

Jogando dentro do Claude, a conta é a do próprio Claude e o salvamento é automático.

## Arquivos

- `index.html`: o jogo inteiro (HTML, CSS e JavaScript num arquivo só)
- `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`: arquivos que deixam o jogo instalável como aplicativo
- `firebase-config.js`: configuração das contas online (veja "Contas e salvamento")
- `screenshot.png`: imagem do jogo usada neste README

O Three.js (versão r128), o PeerJS (versão 1.5.4) e as fontes (Lilita One e Nunito) são carregados pela internet na primeira vez que o jogo é aberto. O modo online precisa de internet sempre.
