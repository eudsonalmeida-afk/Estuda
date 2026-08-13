# Cronograma de Estudos

Aplicativo web inspirado na planilha **Cronograma de Estudos — Planilha Automática**. Funciona sem servidor, salva os dados no navegador e pode ser publicado gratuitamente no GitHub Pages.

## Funcionalidades

- Mapeamento automático das horas disponíveis da semana
- Cadastro de até 20 matérias com distribuição proporcional do tempo
- Cronograma semanal editável em blocos de 30 minutos
- Rastreador de revisões em +1, +7 e +30 dias
- Alertas de revisões vencidas e próximas
- Importação e exportação de backup em JSON
- Layout responsivo para computador e celular

## Como usar

Abra `index.html` no navegador. Não é necessário instalar nada.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main`, pasta `/ (root)`, e clique em **Save**.

O endereço público aparecerá nessa mesma tela após a publicação.

## Privacidade

Os dados ficam apenas no `localStorage` do navegador. Use **Exportar dados** para criar backups.
