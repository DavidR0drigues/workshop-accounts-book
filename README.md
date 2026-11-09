# Livro de Contas – Oficina

Aplicação PWA sem dependências externas para registar intervenções, faturas, pagamentos, pesquisar históricos e manter cópias de segurança. Os dados ficam no IndexedDB do navegador deste computador.

## Executar localmente

Abra um terminal nesta pasta e inicie um servidor local, por exemplo `python -m http.server 8000`. Aceda a `http://localhost:8000` no Chrome ou Edge. A aplicação e o service worker requerem HTTP/HTTPS (não abra o HTML diretamente como ficheiro).

## Publicar no GitHub Pages

Publique estes ficheiros na raiz de um repositório GitHub e, em **Settings → Pages**, escolha a branch e a pasta raiz. Abra o endereço HTTPS publicado.

## Instalar no PC da oficina

No Chrome ou Edge, abra a aplicação publicada e use o ícone **Instalar** na barra de endereço (ou o menu do navegador → **Instalar Livro Oficina**). A primeira abertura requer internet; depois a app pode abrir offline.

## Dados e cópias de segurança

Use **Escolher pasta de backup** para configurar uma pasta local e mantenha cópias exportadas noutro local seguro. A pasta e o IndexedDB pertencem ao perfil do navegador. **Nunca coloque dados reais de clientes neste repositório, em exemplos, commits ou ficheiros publicados.**
