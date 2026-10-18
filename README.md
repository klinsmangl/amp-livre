# amp livre

Controle pelo navegador para o amplificador Bluetooth **Sinilink XY-AP50L** (placa XinYi, chip JieLi). Substitui o app oficial: sem conta, sem nuvem, sem instalar nada.

**Abrir:** https://klinsmangl.github.io/amp-livre/

## O que faz

- volume (0–30), tocar/pausar, anterior/próxima, parar
- entrada: Bluetooth, AUX, pendrive (USB), cartão SD, PC (placa de som USB)
- equalizador: Normal, Rock, Pop, Clássico, Jazz, Country
- modo de repetição e lista de músicas do pendrive/cartão (experimental)
- nome Bluetooth, PIN de pareamento, som de aviso
- mostra o estado da placa e a versão do firmware

## Onde funciona

Precisa de Web Bluetooth: Chrome ou Edge no Android, Windows, macOS e ChromeOS. No Linux, talvez seja preciso ligar `chrome://flags/#enable-experimental-web-platform-features`. No iPhone, use o navegador Bluefy. Firefox e Safari não têm Web Bluetooth.

A placa aceita um controle por vez: feche o app oficial antes de conectar.

## Limites

- Feito com uma placa de firmware 1.2.1. Equalizador personalizado não existe nessa versão.
- A lista de músicas ainda não foi testada com pendrive ou cartão de verdade.

## Privacidade

É uma página estática: um único `index.html`, sem bibliotecas nem chamadas externas. Nada vai para a internet; a conversa é só entre o navegador e a placa, pelo Bluetooth.

---

Projeto independente, sem relação com a Sinilink ou a XinYi.
