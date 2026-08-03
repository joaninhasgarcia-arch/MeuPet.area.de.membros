# Meu Pet — Área de Membros Premium (Lhasa e player corrigidos)

Projeto estático em HTML, sem tela de login, pronto para Vercel ou GitHub Pages.

## Correções desta versão

- restaurada a aula **Lhasa em amigurumi — Parte 1 (receita escrita)**;
- mantida logo abaixo a **Parte 2 (receita escrita)**;
- identificada e organizada também a sequência clássica de Lhasa em **Parte 1 e Parte 2**;
- removida a aula avulsa de Border Collie que começava diretamente pela Parte 2;
- mantida a sequência completa de Border Collie em Parte 1 e Parte 2;
- preservadas todas as demais aulas, os módulos de gatinhos, marketing, fotografia e os materiais em PDF;
- o player deixou de usar a API dinâmica do YouTube e voltou a usar incorporação direta por `iframe`, como na versão anterior;
- adicionado `referrerpolicy="strict-origin-when-cross-origin"`, necessário para a reprodução incorporada atual do YouTube;
- mantidos busca, progresso, rolagem automática para o player e navegação entre aulas.

## Quantidade de aulas

- **33 aulas** na trilha de cachorrinhos;
- 10 aulas de gatinhos;
- 10 aulas de marketing, vendas e precificação;
- 7 aulas de fotografia;
- **60 videoaulas ao todo**.

## Teste correto do player

Não teste os vídeos abrindo o `index.html` diretamente pelo gerenciador de arquivos (`file://`). O YouTube pode bloquear a reprodução porque esse modo não envia a referência HTTP do site.

### Opção recomendada

Publique os arquivos na Vercel ou no GitHub Pages e teste pela URL HTTPS.

### Teste local no computador

Na pasta do projeto, execute:

```bash
python -m http.server 8080
```

Depois abra:

```text
http://localhost:8080
```

## Publicação

Envie `index.html` e `README.md` para a raiz do projeto. Na Vercel, publique como site estático. No GitHub Pages, use **Settings > Pages > Deploy from a branch**.

## Observação

Se o proprietário de um vídeo desativar a opção de incorporação no próprio YouTube, nenhum código HTML consegue forçar a reprodução dentro de outro site. Nessa situação, o botão **Abrir no YouTube** continua disponível.
