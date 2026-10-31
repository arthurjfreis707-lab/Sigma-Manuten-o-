# SIGMA 2.0 — Sistema Integrado de Gestão de Manutenção e Ativos

## Conteúdo
- `index.html`: aplicativo web responsivo com cadastro e acompanhamento de manutenções.
- `manifest.json`: configuração para instalação como aplicativo web (PWA).
- `sw.js`: cache básico para funcionamento offline após o primeiro acesso.
- `icon.svg`: ícone do SIGMA.

## Funcionalidades incluídas
- Cadastro, edição, exclusão e consulta de solicitações.
- Campos de solicitante, área, equipamento/patrimônio, fornecedor, peças, status, datas, custo, tempo de reparo e visto do responsável.
- Painel com indicadores de solicitações abertas, em execução e concluídas.
- Pesquisa e filtros por status e área.
- Exportação CSV compatível com Excel.
- Backup e restauração em JSON.
- Armazenamento local no navegador do dispositivo.

## Publicar no GitHub Pages
1. Extraia este ZIP no computador.
2. No repositório GitHub, use **Add file > Upload files**.
3. Envie os arquivos que estão dentro desta pasta (não envie somente o ZIP). `index.html` deve ficar na raiz do repositório.
4. Clique em **Commit changes**.
5. No repositório, abra **Settings > Pages**.
6. Em **Build and deployment**, escolha **Deploy from a branch**.
7. Selecione a branch `main` e a pasta `/(root)`, depois clique em **Save**.
8. Aguarde a publicação e abra o endereço do GitHub Pages informado nessa mesma tela.

## Instalar no Android
Abra o endereço publicado no Google Chrome do Android. No menu do Chrome, escolha **Instalar app** ou **Adicionar à tela inicial**, se disponível.

## Observações importantes
- Esta é uma versão inicial funcional em formato PWA (aplicativo web instalável), não um APK nativo.
- A criação de um APK assinado exige uma etapa adicional de empacotamento Android.
- Os dados ficam armazenados localmente no navegador/dispositivo. Não há login, sincronização em nuvem, banco de dados central ou controle de acesso nesta versão. Faça backups regularmente.
- Para uso corporativo multiusuário, será necessário desenvolver backend, autenticação, banco de dados e política de segurança.
