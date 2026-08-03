# Meu Pet — Área de Membros Premium

Projeto estático em HTML, sem tela de login, pronto para publicação na Vercel ou no GitHub Pages.

## Alteração desta versão

O player voltou ao **modelo antigo de iframe**, igual ao usado na versão original da área de membros:

- incorporação direta por `iframe`;
- domínio `youtube-nocookie.com`;
- sem uso da API JavaScript do YouTube;
- sem `referrerpolicy` personalizado;
- reprodução dentro da própria página para vídeos que permitem incorporação;
- botão **Abrir no YouTube** mantido como alternativa.

Todas as aulas, módulos, progresso, busca, rolagem automática, materiais em PDF e demais funções da versão anterior foram preservados.

## Arquivos

- `index.html` — área de membros completa;
- `README.md` — instruções do projeto.

## Publicação

Envie os dois arquivos para a raiz do projeto na Vercel ou no GitHub Pages.

Para testar localmente no computador, abra um terminal dentro da pasta e execute:

```bash
python -m http.server 8080
```

Depois acesse:

```text
http://localhost:8080
```

## Observação sobre o YouTube

A página consegue reproduzir internamente apenas vídeos que permitem incorporação em outros sites. Quando o proprietário do vídeo bloqueia essa opção no YouTube, o HTML não consegue remover a restrição; nesse caso, use o botão **Abrir no YouTube**.
