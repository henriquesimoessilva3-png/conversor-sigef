# Conversor SIGEF — Memorial Descritivo PDF → Word

Ferramenta para converter automaticamente Memoriais Descritivos do SIGEF/INCRA em arquivos Word (.docx) com a descrição literária do perímetro.

**Acesse**: https://henriquesimoessilva3-png.github.io/conversor-sigef/

## Como funciona

1. Selecione o PDF do Memorial Descritivo do SIGEF.
2. A ferramenta extrai automaticamente cabeçalho, vértices, coordenadas, azimutes e distâncias.
3. Para cada confrontação detectada (estrada, rio, imóvel privado, etc.), preencha o texto-conector completo (com CPF, RG, COMARCA quando aplicável).
4. Os textos digitados ficam salvos no navegador (`localStorage`) e são reaproveitados nos próximos PDFs.
5. Clique em "Gerar e baixar .docx".

## Privacidade

Tudo roda no seu navegador. Nenhum PDF, dado de cartório ou texto digitado é enviado para qualquer servidor. As bibliotecas (pdf.js, JSZip) são carregadas via CDN público no primeiro acesso.

## Formato gerado

- Arial 12pt, justificado
- A4, margens 2,5cm × 3cm
- Parágrafo único com a descrição completa do perímetro
