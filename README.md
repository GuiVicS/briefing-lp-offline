# Briefing da landing page (offline)

Formulário com todas as perguntas da LP do gerar-lojas (Você, Identidade visual, Landing page, Conteúdo e integrações, Para finalizar). Não usa banco de dados: tudo fica no **IndexedDB** do navegador, inclusive os anexos.

## Como usar
1. Abra o `index.html` no navegador (duplo clique serve) ou publique a pasta em qualquer hospedagem estática.
2. Preencha. Salva sozinho a cada alteração.
3. Clique em **Gerar ZIP**. O ZIP traz:
   - `README.md` com o briefing completo;
   - um `.md` por seção (`01-voce.md` … `05-finalizar.md`);
   - `anexos/<pasta>/` com logo, fontes, textos, fotos e vídeos, depoimentos etc.;
   - `briefing.json` para reabrir e editar depois.
4. Para editar depois: abra de novo no mesmo navegador (continua de onde parou) ou, em outro computador, **Meus briefings → Importar ZIP**.

Em **Meus briefings** dá para ter vários briefings, duplicar e excluir.

`jszip.min.js` (v3.10.1, MIT) vai junto para funcionar sem internet.
