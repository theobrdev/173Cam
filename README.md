# SCP_Camera 1.2

## O que é

SCP_Camera é um aplicativo para Windows que simula uma estação de monitoramento da Fundação SCP. Em vez de um jogo com objetivo, ele é uma experiência de observação: você abre o app, a tela vai para tela cheia e fica assistindo às câmeras de contenção, enquanto coisas estranhas acontecem.

## A ideia

A ideia é recriar a sensação de ser o operador de plantão, olhando para um monitor durante horas. Nada acontece em intervalos fixos. A câmera falha, o som muda, algo escapa ao fundo, e você nunca sabe quando vai ser o próximo evento. A câmera principal mostra o SCP-173, e você pode trocar para outras gravações, feeds e até para o rádio da instalação.

## O que tem no SCP_Camera

- **Câmera do SCP-173:** a câmera principal. Em momentos aleatórios, a imagem falha e a tela fica preta ao som de pedra raspando. Às vezes, quando a imagem volta, algo grita. Muito raramente, o alerta de que o SCP-106 escapou da instalação toca ao fundo, em volume baixíssimo, uma ou mais vezes.
- **Piscar:** você pode forçar uma tela preta rápida quando quiser. Mas cuidado com o que acontece enquanto você não está olhando.
- **Feed do SCP-895 (CAM06):** o feed ao vivo da câmera de contenção do SCP-895, com chiado, relógio em tempo real e interrupções em que a imagem escurece e algo aparece na tela.
- **Gravação do SCP-131:** uma gravação com som próprio. Quando ela termina, o aplicativo sorteia para onde ir em seguida: o SCP-173, o feed do SCP-895 ou o vídeo do SCP-██6.
- **Rádio:** uma tela preta com o símbolo da Fundação girando devagar. De tempos em tempos, uma transmissão sorteada toca no rádio da instalação.
- **SCP-██6:** [REDACTED]

## Novidades da versão 1.2

- **Rádio:** uma nova câmera, que você abre com a tecla `R`. O app sorteia as transmissões que tocam, com pausas aleatórias entre elas.
- **Grito do SCP-173:** na câmera do SCP-173, depois de algumas telas pretas, a imagem volta acompanhada de um grito.
- **Discord Rich Presence:** o seu perfil do Discord mostra o que você está assistindo no SCP_Camera, com o tempo de sessão e links para as páginas oficiais. O SCP-██6 aparece como `[REDACTED]`. A presença só aparece se o aplicativo do Discord estiver aberto no computador. Com o Discord fechado, o app funciona normalmente.

## Menu e opções

O app abre em um menu, com os botões **JOGAR**, **OPÇÕES** e **SAIR**. Você pode usar o mouse, ou as setas do teclado com `Enter`. O `ESC` volta ao menu anterior ou fecha o app.

Em **OPÇÕES** existe uma única opção, **Monitor Secundário**. Clique no quadrado ao lado para ativar ou desativar. Já vem desativada, e a sua escolha fica salva para as próximas vezes. Ela abre o app direto em uma janela sem bordas (borderless) que fica fixada no topo, ideal para deixar rodando em um segundo monitor enquanto você faz outras tarefas.

Com ela ativada, ao clicar em JOGAR:

- **Se você tem dois monitores:** o app abre sem bordas no segundo monitor e fica sempre por cima das outras janelas.
- **Se você tem um monitor só:** o app abre em uma janela pequena, sem bordas e sempre por cima. Para mover, clique nela e arraste.
- Nesse modo, a tecla `F`/`F11` não faz nada e o cursor do mouse fica visível.

## Controles

| Tecla | Ação |
|-------|------|
| `1` | Câmera do SCP-173 (a principal) |
| `3` | Gravação do SCP-131 |
| `8` | Feed do SCP-895 |
| `R` | Rádio |
| `0` | Vídeo do SCP-██6 |
| `ESPAÇO` | Piscar: tela preta de 1 a 2 segundos (só na câmera do SCP-173) |
| `M` | Muta e desmuta o som |
| `F` ou `F11` | Alterna entre tela cheia e janela (fora do modo Monitor Secundário) |
| `ESC` | Fecha o app |

## Download

Baixe o `SCP_Camera.exe` na aba Releases, ou na página do itch.io, e execute. Requer Windows 10 ou 11.

Se o Windows mostrar um alerta (SmartScreen), clique em **Mais informações** e depois em **Executar assim mesmo**. Isso é comum em programas pequenos que não têm assinatura digital.

> Aviso: o app tem sons repentinos, gritos, escurecimentos bruscos da imagem e conteúdo perturbador. Cuidado com o volume.

## Créditos

**SCPs**
- SCP-173, SCP-106, SCP-131 e SCP-██6: SCP Foundation (CC BY-SA 3.0), https://scp-wiki.wikidot.com
- SCP-895, de Aelanna (CC BY-SA 3.0): https://scpwiki.com/scp-895

**Vídeos**
- Vídeo do SCP-173: SandS Channel
- Vídeo do SCP-██6: the grave encounter number two
- Vídeo do SCP-131: autor desconhecido (se você é o autor, entre em contato para receber o crédito ou pedir a remoção)

**Feed do SCP-895**
- Código e imagens: stephlynch (CC BY-SA 3.0), com imagens derivadas de uma cena do Blender 2.83, de Ian Hubert (CC BY-SA 3.0), https://cloud.blender.org/p/gallery/5eff317d7920214fcfa0770e

**Sons**
- SCP: Secret Laboratory e SCP: Containment Breach
- Áudios do rádio e grito do SCP-173: SCP: Containment Breach
- Áudio do SCP-██6: the grave encounter number two e SCP: Containment Breach

**Desenvolvimento**
- Desenvolvido por TBloper ([itch.io](https://tbloper.itch.io)) / theobrdev ([GitHub](https://github.com/theobrdev))
- Feito com Python, pygame, OpenCV e pypresence

Projeto de fã, gratuito e não afiliado à SCP Foundation nem à Northwood Studios.

## Páginas oficiais

O SCP_Camera só é distribuído nestes dois lugares:

- GitHub: https://github.com/theobrdev/173Cam/
- itch.io: https://tbloper.itch.io/scp-173-camera

Se você baixou de qualquer outro site, ele não é oficial. Se encontrar uma página assim, por favor avise.

Contato: Discord @tbloper