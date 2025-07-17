### 🗓 Semana 4 — 24 a 28 de junho de 2025

**Tarefas realizadas:**
- Implementada a lógica de **filtro por categorias** na tela de ranking:
  - Permite visualizar rankings separados por categorias como "Iron", "Gold", "Silver", etc.
  - Filtro dinâmico com atualização automática da lista exibida.
- Desenvolvida a base da funcionalidade de **compartilhamento do ranking por categoria**.
- Realizados diversos **testes manuais** e ajustes na filtragem e no layout do print.
- Implementada a **validação da gravação de trilhas**, incluindo:
  - Exibição de **pop-ups explicativos** para erros de tempo inválido.
  - Ajuste na **formatação de distância e tempo** para exibição no ranking.
- Concluída a **implementação do print do ranking filtrado por categoria**, com cabeçalho adaptado.

**Aprendizados:**
- Combinação de `Dropdown`, `setState` e estrutura condicional para filtragem dinâmica.
- Uso de `RepaintBoundary` e `captureFromWidget` para gerar imagens exportáveis.
- Feedback visual com `AlertDialog` e `SnackBar` para instruir o usuário.
- Padronização de dados para visualização pública.

**Desafios enfrentados:**
- Evitar gravação de trilhas incompletas ou inconsistentes.
- Garantir clareza e legibilidade na imagem gerada para compartilhamento.
- Ajustar responsividade da interface com base em diferentes tamanhos de lista.

**Observações:**
- Essa semana consolidou funcionalidades-chave do ranking e do compartilhamento, com foco em confiabilidade e boa experiência de usuário.
