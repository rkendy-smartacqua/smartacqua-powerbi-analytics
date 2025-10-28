# Página Power BI com Google Analytics

Esta página permite monitorar o uso do seu relatório Power BI público usando o Google Analytics (GA4).

## 🧭 Passos rápidos

1. **Abra o arquivo `index.html`** no navegador → o relatório será exibido.
2. **Acesse o Google Analytics → Relatórios → Tempo real** → visualize acessos em tempo real.
3. **Publique no GitHub Pages:**
   - Crie um repositório no GitHub (ex: `smartacqua-pbi-report`).
   - Faça upload dos arquivos deste .zip (`index.html` e `README.md`).
   - Vá em *Settings → Pages → Source → main branch /root* → salve.
   - Seu site ficará disponível em `https://<usuario>.github.io/smartacqua-pbi-report/`.

## 🧩 Customização
- Para alterar o relatório Power BI, substitua o link dentro da tag `<iframe>`.
- Para alterar o código GA4, mude o valor em `gtag('config', 'G-XXXXXX');`.
