# Declaração de Comparecimento

Gerador da **Declaração de Comparecimento** (CRAS · Prefeitura de São Sebastião) em A4, com pré-visualização ao vivo, histórico local e instalação como app (PWA).

## Como usar
1. Preencha nome, nascimento, RG, data e horário do atendimento.
2. A folha ao lado atualiza na hora. Use **Imprimir / PDF** (escolha "Salvar como PDF" para gerar o arquivo).
3. **Salvar no histórico** guarda no navegador; use **Exportar backup** de vez em quando.

## Publicar no GitHub Pages
Envie todos os arquivos desta pasta para a raiz do repositório e ative *Settings → Pages → Deploy from a branch → main / root*.

## Qualidade
- O texto da folha é vetorial (nítido em qualquer zoom e na impressão).
- `assets/cabecalho.png`: ampliado 4× e suavizado a partir do modelo. `assets/rodape.png`: original de 2048 px.
- Se tiver o cabeçalho em alta resolução ou SVG, basta substituir `assets/cabecalho.png`.
- Para publicar uma nova versão, mude `VERSION` em `sw.js`.
