# Relatório de validação do website MyPME

Data: 12 de julho de 2026<br>
Estado: preparado localmente para publicação manual no GitHub Pages; ainda não publicado.

## Ficheiros criados

- `index.html`
- `privacy-policy.html`
- `account-deletion.html`
- `support.html`
- `styles.css`
- `app-ads.txt`
- `robots.txt`
- `sitemap.xml`
- `README.md`
- `GITHUB_PAGES_DEPLOYMENT.md`
- `.gitignore`
- `assets/logo-placeholder.svg`
- `assets/dashboard-placeholder.svg`
- `assets/reports-placeholder.svg`
- `assets/activity-placeholder.svg`

## Conteúdo e páginas

- Página inicial com posicionamento, benefícios, oito funcionalidades, funcionamento, público-alvo, privacidade, estado do produto e contacto.
- Política adaptada da fonte legal 2.1.2, preservando Firebase Authentication, Firestore, Analytics, Crashlytics, SQLite, AdMob, UMP, Advertising ID, localização aproximada inferida por IP, diagnósticos, eliminação e limitações offline.
- Página de eliminação com navegação dentro da aplicação, reautenticação, dados abrangidos, processo retomável, dispositivos offline, distinção de dados Google e pedido alternativo por e-mail.
- Suporte para login, sincronização, recuperação de palavra-passe, relatórios PDF, eliminação, privacidade e publicidade.

## Validações

- Todos os ficheiros obrigatórios existem.
- Ligações internas, fragmentos/âncoras, caminhos relativos e ligações `mailto:` verificados.
- Todas as páginas usam `lang="pt-AO"`, UTF-8, viewport, títulos específicos, descrição e canonical com placeholder documentado.
- Landmarks semânticos, hierarquia de headings, texto alternativo e ligação para saltar ao conteúdo presentes.
- `:focus-visible`, alvos clicáveis adequados, contraste legível e navegação por teclado contemplados no CSS.
- Página inicial renderizada em Chrome headless a 360, 390, 768, 1024 e 1440 px. Grelhas e navegação reduzem colunas progressivamente; a navegação móvel quebra em linhas visíveis, sem depender de scroll horizontal.
- Estilos de impressão e preferência de movimento reduzido incluídos.
- Open Graph contém metadados locais de título, descrição, tipo e localidade; nenhuma URL pública foi inventada.
- Não existem scripts, trackers, cookies, analytics web, fontes externas, anúncios incorporados, formulários ou dependências npm.
- Não existem segredos nem IDs de unidades de anúncio no website.
- Não existe afirmação de disponibilidade pública no Google Play.

## app-ads.txt

O ficheiro está na raiz, em texto simples UTF-8, com uma única linha válida para o publisher fornecido. Não contém HTML, comentários, redes adicionais ou IDs de blocos de anúncio.

## Placeholders pendentes

`SEU-USUARIO` permanece apenas em canonical, `robots.txt`, `sitemap.xml` e documentação onde está explicitamente identificado para substituição. Antes da publicação, deve ser substituído pelo proprietário real do repositório GitHub e validado novamente.

## Passos manuais restantes

1. Criar o repositório público `mypme-site`.
2. Adicionar o remote autorizado e enviar a branch `main`.
3. Ativar GitHub Pages em **Settings → Pages → Deploy from a branch**, branch `main`, pasta `/root`.
4. Confirmar a URL pública e substituir todos os placeholders.
5. Verificar as quatro páginas e `app-ads.txt` no domínio publicado.
6. Registar as URLs no Google Play Console e verificar o domínio/`app-ads.txt` no AdMob.
