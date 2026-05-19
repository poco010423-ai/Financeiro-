# 🎮 NeoBrick 3D

Jogo estilo Tetris com peças 3D renderizadas via Three.js e visual neon cyberpunk.

## ▶️ Jogar agora

👉 **[Clique aqui para jogar](https://SEU_USUARIO.github.io/neobrick-3d/)**

_(Substitua `SEU_USUARIO` pelo seu usuário do GitHub após publicar)_

---

## 🕹️ Controles

| Ação | Mobile | Teclado |
|------|--------|---------|
| Mover | ◀ ▶ botões | ← → |
| Descer | ▼ botão | ↓ |
| Rotar | 🔄 botão | ↑ ou X |
| Drop rápido | DROP | Espaço |
| Pausar | START/PAUSE | — |
| Tela cheia | TELA CHEIA | — |

## ✨ Funcionalidades

- Peças 3D com material físico (Three.js MeshPhysicalMaterial)
- 15 estilos de cores neon
- 11 tipos de peças (7 clássicas + 4 especiais)
- Sistema de vidas (3 chances)
- Música chiptune via Web Audio API
- Recorde salvo localmente
- PWA — pode ser instalado como app

---

## 🚀 Como hospedar no GitHub Pages

1. Crie um repositório público no GitHub (ex: `neobrick-3d`)
2. Faça upload dos 4 arquivos:
   - `index.html`
   - `icon.svg`
   - `manifest.json`
   - `README.md`
3. Vá em **Settings → Pages → Branch: main → / (root) → Save**
4. Aguarde ~1 minuto e acesse: `https://SEU_USUARIO.github.io/neobrick-3d/`

---

## 📦 Estrutura

```
neobrick-3d/
├── index.html      ← jogo principal
├── icon.svg        ← ícone estilo Tetris
├── manifest.json   ← configuração PWA
└── README.md       ← este arquivo
```

---

*Desenvolvido com Three.js r128 + Tailwind CSS v4*
