# Termo de Autorização de Uso de Imagem e Voz — Afya Unigranrio

Página estática (HTML/CSS/JS, sem build) que coleta os dados, a assinatura desenhada e gera o PDF do termo direto no navegador.

## Como publicar no GitHub Pages

1. Crie um repositório e envie `index.html` (e, opcionalmente, `logo.png`).
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Aguarde 1–2 minutos: o site ficará em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Testar localmente

Abra o `index.html` no navegador, ou rode `python -m http.server` e acesse `http://localhost:8000`.

## Logo

Coloque o arquivo da logo oficial como `logo.png` na mesma pasta. Sem ele, aparece apenas o texto "Afya".

## Observações importantes

- Nenhum dado é enviado a servidor: tudo é processado no navegador e o PDF é baixado pelo próprio usuário.
- Para receber os termos automaticamente (Google Drive, e-mail, banco de dados) é preciso integrar um backend; antes disso, alinhe com o Jurídico/DPO o tratamento de dados pessoais (RG, CPF, imagem de menores) conforme a LGPD.
- Valide o texto final do termo e a validade da assinatura eletrônica simples com o Jurídico da Afya.
