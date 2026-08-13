# Estuda

**Estuda** é um aplicativo web inspirado na planilha **Cronograma de Estudos — Planilha Automática**. Funciona sem servidor, salva os dados no navegador e pode ser publicado gratuitamente no GitHub Pages.

## Funcionalidades

- Mapeamento automático das horas disponíveis da semana
- Cadastro de até 20 matérias com distribuição proporcional do tempo
- Cronograma semanal editável em blocos de 30 minutos
- Rastreador de revisões em +1, +7 e +30 dias
- Alertas de revisões vencidas e próximas
- Importação e exportação de backup em JSON
- Layout responsivo para computador e celular
- Instalação como PWA, com ícone e abertura sem abas do navegador
- Funcionamento offline após o primeiro acesso

## Como usar

Abra `index.html` no navegador. Não é necessário instalar nada.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main`, pasta `/ (root)`, e clique em **Save**.

O endereço público aparecerá nessa mesma tela após a publicação.

## Instalar no celular

- **Android:** abra o link no Chrome, toque no menu e escolha **Instalar aplicativo** ou use o botão mostrado no menu lateral.
- **iPhone/iPad:** abra no Safari, toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.

Depois de instalado, o Estuda abre como aplicativo, sem a barra e as abas comuns do navegador. O primeiro acesso precisa ser feito com internet; depois, o app também abre offline.

## Privacidade

Os dados ficam apenas no `localStorage` do navegador. Use **Exportar dados** para criar backups.
