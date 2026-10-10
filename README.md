# Portfólio · LclzGit

Site de portfólio com os projetos que desenvolvi: plataformas de estudo da legislação tributária, calculadoras fiscais, automações com APIs de notas fiscais e um jogo idle.

É um único `index.html`, sem build nem dependências. Para ver, abra o arquivo no navegador.

## Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha *Deploy from a branch*, selecione a branch e a pasta `/ (root)`.
3. O site fica em `https://lclzgit.github.io/Portf-lio/`.

## Estrutura

```
index.html               Página do portfólio (HTML + CSS + JS embutidos)
assets/img/              Capturas de tela dos projetos
demos/daemon-bar/        Cópia jogável do protótipo do Daemon Bar (repo IdleGame)
```

## Como editar

- **Projetos:** cada projeto é um `<article class="card">` dentro de `#grid`. O atributo `data-cat` define o filtro (`estudo`, `calc`, `auto`, `jogo`). Use `class="card feature"` para um card de largura total.
- **Contato:** na seção `#contato` há um comentário pronto para adicionar LinkedIn e e-mail.
- **Daemon Bar:** para atualizar a demo, copie `prototype/index.html` do repo IdleGame para `demos/daemon-bar/index.html`.

## Projetos incluídos

| Projeto | Repositório | Visibilidade |
|---|---|---|
| ReformaPro | [reformapro](https://github.com/LclzGit/reformapro) | público |
| IRCSPro | [IRPRO](https://github.com/LclzGit/IRPRO) | público |
| Calculadora da Reforma Tributária | CalculadoraReformaTributaria | privado |
| Calculadora & Apuração DIFAL | Calculadora-DIFAL, Apuracao-DIFAL | privado |
| SNNFSe Python | [Snnfse-python](https://github.com/LclzGit/Snnfse-python) | público |
| Painel de NFs × Qive | PainelNFs-x-QIVE | privado |
| Daemon Bar | [IdleGame](https://github.com/LclzGit/IdleGame) | público |
