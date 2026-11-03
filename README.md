# Opinião Brasil

Site simples de comentários e vídeos do YouTube. Funciona no GitHub Pages, sem instalar nada.

## Estrutura

```
index.html          ← o site
admin.html          ← painel para escrever e publicar
marked.min.js       ← biblioteca de formatação (não mexer)
posts/posts.json    ← lista das publicações
posts/*.md          ← o texto de cada publicação
```

## Colocar no ar

1. Crie um repositório **público** chamado `opiniaobrasil` na conta `Marcelo2244`.
2. **Add file → Upload files** e arraste todo o conteúdo desta pasta (não a pasta em si). Clique em **Commit changes**.
3. **Settings → Pages** → *Deploy from a branch* → branch `main`, pasta `/ (root)` → **Save**.
4. Em alguns minutos o site fica em `https://marcelo2244.github.io/opiniaobrasil/`.

## Publicar

Abra `https://marcelo2244.github.io/opiniaobrasil/admin.html`.

No primeiro acesso, cole uma chave do GitHub. A página ensina a gerar: *Fine-grained token*, só para o repositório `opiniaobrasil`, com **Contents: Read and write**. Se você já tem a chave do site `opiniaojuridica`, pode editá-la no GitHub e acrescentar o repositório `opiniaobrasil` em vez de criar outra.

- **Comentário:** preencha título e texto e clique em Publicar.
- **Vídeo:** cole o link do YouTube no campo *Vídeo do YouTube*. O vídeo aparece no topo da publicação e com miniatura na página inicial. O texto é opcional.
- **Vários vídeos num texto:** use o botão **▶ Vídeo no texto**, ou cole um link do YouTube sozinho numa linha.

Aceita todos os formatos de link do YouTube: `youtube.com/watch?v=…`, `youtu.be/…`, `youtube.com/shorts/…` e `youtube.com/live/…`.

## Sobre envio de vídeos

O vídeo fica hospedado no YouTube, e o site só o exibe. Envie primeiro para o seu canal (pode ser como **Não listado**, se não quiser que apareça no canal) e depois cole o link no painel.
