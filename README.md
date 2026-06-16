# NeuroFlex — Exoesqueleto de Reabilitação

Site do TCC de Mecatrônica — ETEC Col. Fernando Prestes.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `neuroflex-tcc`)
2. Faça upload do arquivo `index.html` para a raiz do repositório
3. Vá em **Settings → Pages**
4. Em "Source", selecione **Deploy from a branch → main → / (root)**
5. Salve. O site vai estar disponível em:
   `https://seu-usuario.github.io/neuroflex-tcc`

## Como adicionar as fotos

Crie uma pasta `fotos/` no repositório e adicione as imagens com os nomes:

```
fotos/prototipo-lateral.jpg
fotos/prototipo-frente.jpg
fotos/teste-braco.jpg
fotos/detalhe-articulacao.jpg
fotos/equipe-lab.jpg
```

## O que personalizar no index.html

- **Linha 329 — Nome da ETEC:** troque "Col. Fernando Prestes" pelo nome correto
- **Seção Equipe (~linha 430):** troque "Aluno 1/2/3" pelos nomes e funções reais
- **Seção Orientador (~linha 455):** coloque o nome do orientador
- **Links GitHub/LinkedIn:** adicione os links reais nos `href="#"`
- **Estatísticas hero:** ajuste os números conforme o projeto avançar

## Estrutura de arquivos

```
neuroflex-tcc/
├── index.html
├── fotos/
│   ├── prototipo-lateral.jpg
│   ├── prototipo-frente.jpg
│   └── ...
└── README.md
```
