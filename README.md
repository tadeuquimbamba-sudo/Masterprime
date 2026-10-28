# ATSVMP — Master Prime

Site oficial da **Associação de Técnicos de Saúde Voluntária Master Prime** (ATSVMP), de Malanje, Angola.

A associação forma agentes voluntários e leva educação, prevenção e cuidado às comunidades mais vulneráveis.

## O que tem o site

- Sobre nós, Objectivos, Missão e Visão, Valores e O que fazemos
- Realizações, em linha do tempo (com a campanha de vacinação contra a poliomielite e o sarampo em destaque)
- Apoie-nos e Contacto, com ligação directa ao WhatsApp
- Fotos ampliáveis, galeria deslizante e verificador de idade para a vacinação

## Estrutura

```
.
├── index.html   # o site inteiro (HTML, CSS, JavaScript e imagens num só ficheiro)
├── .gitignore
├── .nojekyll    # faz o GitHub Pages publicar o ficheiro tal como está
└── README.md
```

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes ficheiros.
2. Vá a **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, a branch `main` e a pasta `/ (root)`.
4. Guarde. O site fica disponível em `https://SEU-UTILIZADOR.github.io/NOME-DO-REPOSITORIO/`.

## Como publicar no Netlify

Ligue o repositório ao Netlify, sem comando de build, e use a raiz do projecto como pasta de publicação.

## Como actualizar

Edite o `index.html`. Para acrescentar uma realização, copie um bloco `<div class="tl-item">` dentro de `<div class="timeline">` e altere o ano, o título e o texto.

---

Desenvolvido por [Casi Art Soluções](https://casiartsolucoes-ao.netlify.app) — *Seu Projecto, Nossa Execução*.
