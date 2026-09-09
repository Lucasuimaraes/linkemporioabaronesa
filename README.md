# Empório A Baronesa — link da loja

Site estático publicado no Cloudflare Pages em:

https://linkemporioabaronesa.pages.dev/

## Publicação automática

Todo envio para a branch `main` executa o workflow do GitHub Actions e publica a pasta `site/` no projeto Cloudflare Pages `linkemporioabaronesa`.

O repositório precisa ter estes secrets em **Settings → Secrets and variables → Actions**:

- `CLOUDFLARE_ACCOUNT_ID`
- `CLOUDFLARE_API_TOKEN`

O token da Cloudflare deve ter a permissão **Account → Cloudflare Pages → Edit** para a conta que contém o projeto.

