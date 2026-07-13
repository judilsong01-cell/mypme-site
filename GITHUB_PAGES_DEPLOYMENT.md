# Publicação manual no GitHub Pages

Estas instruções não executam publicação automática. É necessário confirmar manualmente a conta, o repositório, o domínio e as definições externas.

## 1. Preparar o repositório

1. Inicie sessão no GitHub pela sua conta pessoal ou organização autorizada.
2. Crie um repositório **público** chamado `mypme-site`.
3. Não adicione segredos, credenciais, keystores, tokens nem ficheiros da aplicação Android.
4. Copie os ficheiros deste diretório para a raiz do repositório.

Exemplo de comandos a executar manualmente depois de criar o repositório remoto:

```bash
git remote add origin https://github.com/SEU-USUARIO/mypme-site.git
git push -u origin main
```

`SEU-USUARIO` é um placeholder. Substitua-o apenas pelo proprietário real do repositório.

## 2. Ativar o GitHub Pages

1. Abra **Settings → Pages** no repositório.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha:
   - Branch: `main`
   - Folder: `/root`
4. Guarde a configuração.
5. Aguarde a publicação e confirme a URL apresentada pelo GitHub.

## 3. Substituir os placeholders

Antes da publicação final, substitua `SEU-USUARIO` em:

- canonical de cada página HTML;
- `robots.txt`;
- `sitemap.xml`;
- `README.md` e este guia.

Use a URL pública realmente confirmada. Não invente domínio ou caminho.

## 4. Verificar o website publicado

Abra e confirme:

- `/`
- `/privacy-policy.html`
- `/account-deletion.html`
- `/support.html`
- `/app-ads.txt`
- `/robots.txt`
- `/sitemap.xml`

Confirme também navegação, e-mail, telemóvel, teclado, contraste, ausência de scroll horizontal e conteúdo legal.

O `app-ads.txt` deve responder como texto simples e conter apenas:

```text
google.com, pub-7775669208593038, DIRECT, f08c47fec0942fa0
```

## 5. Registos externos

Depois de confirmar a URL pública:

1. Registe a URL da Política de Privacidade no Google Play Console.
2. Registe a URL da página de eliminação de conta no Google Play Console.
3. Confirme o website do programador no Google Play Console.
4. Registe ou confirme o domínio no AdMob.
5. Aguarde e confirme a verificação pública de `app-ads.txt` no AdMob.

Não ative anúncios reais apenas por ter publicado estas páginas. Consentimento, testes físicos, declarações Play Console e aprovação do candidato produtivo continuam como etapas separadas.
