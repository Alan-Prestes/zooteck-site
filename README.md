# ZooTeck — Site institucional

Landing page estática para GitHub Pages. O aplicativo R Shiny continua no Posit Connect Cloud.

## Publicação
1. Criar repositório público `zooteck-site` no GitHub.
2. Enviar `index.html`, `CNAME` e `README.md` para a raiz da branch `main`.
3. Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
4. Em Settings > Pages > Custom domain, configurar `www.zooteck.com.br` (já declarado no arquivo CNAME).
5. No Registro.br, criar CNAME `www` para `Alan-Prestes.github.io` (verificar nome exato de usuário GitHub).
6. Para redirecionar `zooteck.com.br` ao www, criar os quatro registros A do GitHub Pages para `@`:
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
7. Habilitar Enforce HTTPS quando disponível.

**Importante:** preservar os registros de e-mail (MX, SPF, DKIM, DMARC e demais TXT) e evitar enviar arquivos `.env`, tokens e chaves Supabase ao repositório público.

Documentação: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
