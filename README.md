# Site Institucional QHealth

Site público da QHealth — **Software, Consultoria e Academia**.

**Slogan:** Gestão inteligente. Saúde mais segura.

## Arquitetura
- Site estático, independente do QHealth Software e do Control Center.
- `index.html`: página institucional completa, responsiva e sem etapa de compilação.
- `qhealth-logo-oficial.webp`: identidade visual oficial.
- `qhealth-gestao-riscos.webp`: captura real e preparada do módulo Gestão de Riscos.
- `_headers`: cabeçalhos de segurança da hospedagem.
- `robots.txt`: indexação pública.

## Publicação gratuita — Cloudflare Pages
1. Acessar **Workers & Pages → Create application → Pages → Connect to Git**.
2. Autorizar a conta GitHub `QHealthgestao` e selecionar **somente** este repositório.
3. Selecionar a branch de produção **main**.
4. Framework preset: **None**. Build command: **em branco**. Build output directory: **/** (raiz do repositório). Se o painel exigir uma pasta de saída, usar `.`.
5. Publicar e validar primeiro o domínio gratuito `*.pages.dev`.
6. Somente depois da homologação, adicionar `qhealth.com.br` e `www.qhealth.com.br` como domínios personalizados; ao migrar DNS, preservar integralmente registros MX/SPF/DKIM/TXT dos e-mails Lark e outros subdomínios ativos.

**Importante:** nunca conectar este projeto às bases do software ou modificar `qhealth-gestao` / `qhealth-control-center` por causa da hospedagem institucional.

## Contato comercial
O formulário estático prepara um e-mail para `danielfernando@qhealth.com.br`. Não há envio, armazenamento ou coleta automática de dados; o visitante confirma o envio no cliente de e-mail.
