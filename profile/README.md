<p align="center">
  <img src="https://raw.githubusercontent.com/pier-dock/.github/main/profile/assets/banner.png" alt="Pier — a dock para macOS, Windows e Linux" width="100%">
</p>

<p align="center">
  Uma dock em <strong>vidro líquido</strong> que substitui a barra do sistema: seus apps, o que está tocando,<br>
  os pull requests do GitHub e o status do sistema, numa barra só.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/pier-dock/.github/main/profile/assets/dock.png" alt="A dock do Pier: botão de apps, apps fixados, mídia, GitHub e sistema" width="100%">
</p>

## O que tem na dock

- **Apps** fixados e abertos, com indicador de janela, app em foco na cor de destaque e atalhos <kbd>Ctrl</kbd> <kbd>Alt</kbd> <kbd>1</kbd>–<kbd>9</kbd>.
- **Tocando agora**: capa, faixa e controles do Spotify, Música, YouTube Music e outros players.
- **GitHub**: seus pull requests com o estado dos checks, revisões pendentes e o mapa de contribuições do ano.
- **Sistema**: Wi-Fi, volume (role para ajustar), bateria e relógio.
- **Ordem livre**: arraste apps, widgets e separadores na própria dock.

<table>
  <tr>
    <td width="33%"><img src="https://raw.githubusercontent.com/pier-dock/.github/main/profile/assets/now-playing.png" alt="Popover Tocando agora"></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/pier-dock/.github/main/profile/assets/pull-requests.png" alt="Popover de pull requests e revisões"></td>
    <td width="33%"><img src="https://raw.githubusercontent.com/pier-dock/.github/main/profile/assets/contributions.png" alt="Popover de contribuições do ano"></td>
  </tr>
  <tr>
    <td align="center"><sub>Tocando agora</sub></td>
    <td align="center"><sub>Pull requests e revisões</sub></td>
    <td align="center"><sub>Contribuições do ano</sub></td>
  </tr>
</table>

## Vidro de verdade, em cada sistema

O desfoque vem do próprio sistema, não de um efeito na página:

| Sistema | Material |
| --- | --- |
| **macOS** 12+ | Liquid Glass (macOS 26) ou vibrancy |
| **Windows 11** | Acrylic na dock e nos popovers, Mica nas configurações |
| **Linux** | Blur do KWin; no GNOME, material sólido (com extensão própria para janelas, atalhos e área reservada) |

Onde o sistema não desenha vidro, o Pier usa um material sólido. Opacidade, material e cor de destaque (Coral, Azul, Verde, Âmbar, Lilás) ficam nas configurações.

## Feito com

[Tauri 2](https://tauri.app) (Rust) · React · TypeScript · [Geist](https://vercel.com/font)
