# Site PRO - Vitória Kayfer

Versão ajustada para Cloudflare Pages + GitHub.

## Antes de subir
Edite `admin/config.yml` e troque estes placeholders:
- `SEU_USUARIO_GITHUB/SEU_REPOSITORIO`
- `https://SEU-AUTH-DOMINIO.com`
- `https://SEU-SITE.pages.dev`

## O que foi corrigido
- removido o Netlify Identity do `/admin`
- trocado o backend do Decap CMS de `git-gateway` para `github`
- mantido o site estático pronto para Cloudflare Pages

## Observação importante
Para o `/admin` salvar conteúdo no GitHub em produção, o Decap CMS precisa de um endpoint OAuth. Sem isso, o site abre, mas o login do painel não conclui.
