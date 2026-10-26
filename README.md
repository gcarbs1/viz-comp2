# LEVA — SCC5836

Apresentação web sobre o artigo **“LEVA: Using Large Language Models to Enhance Visual Analytics”**, publicada na *IEEE Transactions on Visualization and Computer Graphics*.

O material foi desenvolvido para a disciplina **SCC5836 — Visualização Computacional** e apresenta a proposta do LEVA, sua arquitetura, os resultados do estudo com usuários e uma análise crítica do artigo.

## Visualizar localmente

Não há dependências ou etapa de compilação. Você pode abrir `index.html` diretamente no navegador ou iniciar um servidor HTTP local:

```bash
python3 -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000).

## Controles da apresentação

- `→`, `Page Down`, `Espaço` ou `Enter`: próximo slide
- `←`, `Page Up` ou `Backspace`: slide anterior
- `Home` / `End`: primeiro ou último slide
- `F`: tela cheia
- Gestos horizontais e rolagem também mudam os slides

## Estrutura do projeto

```text
.
├── index.html       # apresentação e estilos
├── assets/          # figuras utilizadas nos slides
├── reference/       # artigo e material de referência
└── help/            # documento de apoio da atividade
```

## Publicar com GitHub Pages

1. Envie o repositório para o GitHub.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main`, a pasta `/ (root)` e salve.

Como o projeto é estático e possui um `index.html` na raiz, nenhuma configuração adicional de build é necessária.

## Autores da apresentação

- Gabriel Carbinatto — 12725411
- Enzo Castelo Branco Biondi — 14568142
- Murilo Lima Lirani de Carvalho — 11234673
- Matheus Rodrigues Ferreira — 14762149

## Referência

ZHAO, Yuheng et al. *Using Large Language Models to Enhance Visual Analytics*. IEEE Transactions on Visualization and Computer Graphics, v. 31, n. 3, 2025. DOI: [10.1109/TVCG.2024.3368060](https://doi.org/10.1109/TVCG.2024.3368060).
