# 🐍 Cobrinha – Snake II (Nokia 1100)

Jogo da cobrinha em HTML, CSS e JavaScript puros, inspirado no clássico Snake II do Nokia 1100: carcaça prateada, tela LCD verde-amarelada e placar de 4 dígitos.

## Como jogar

- **Mover:** setas do teclado, `W A S D`, teclas `2 4 6 8`, botões na tela ou deslizar o dedo sobre o visor.
- **Pausar / começar:** `Espaço`, `P`, `Enter` ou a barra azul do celular.
- **Comida:** cresce 1 segmento e dá pontos.
- **Inseto bônus:** aparece a cada 4 comidas por pouco tempo; vale mais pontos e faz a cobra crescer 3 segmentos extras.
- **Níveis:** a cada 5 comidas sobe o nível e a velocidade aumenta.
- **Fim de jogo:** bater na parede ou em si mesma. O recorde fica salvo no navegador (`localStorage`).

## Executar localmente

Não precisa instalar nada. Abra o `index.html` no navegador ou, se preferir um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
3. Salve. O jogo ficará em `https://phfcuditablet.github.io/snake/`.

## Estrutura

```
.
├── index.html   # jogo completo (HTML + CSS + JS)
├── README.md
├── LICENSE
└── .gitignore
```

## Licença

MIT. Veja o arquivo [LICENSE](LICENSE).
