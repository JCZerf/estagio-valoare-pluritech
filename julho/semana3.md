### 🗓 Semana 3 — 15 a 19 de julho de 2025

**Tarefas realizadas:**
- **Correção do erro** que impedia o carregamento correto do mapa na tela de trilhas.
- Melhoria na performance geral com **carregamento assíncrono das trilhas** usando `Future.wait` em batches de 5 trilhas.
- **Fix da tela cinza** que ocorria ao carregar cidades com trilhas vazias.
- Modificada a rotina de gravação para **bloquear a saída da tela** até que a trilha seja salva com sucesso.
- Prevenção contra gravação de trilhas com **coordenadas vazias**, evitando falhas silenciosas.
- Exibição da **data e hora da atividade** e do **nome do usuário logado** nos detalhes da trilha.
- Implementada **normalização de texto nas buscas** por trilha e cidade.
- Corrigida a configuração do mapa OSM com `NetworkTileProvider` e `userAgentPackageName` para evitar falhas no carregamento dos tiles.
- Inclusão de validações avançadas no salvamento de tempo:
  - Bloqueio de gravação com tempo superior ao bestTime atual.
  - Validação para impedir duplicações (`fullTime`).
  - Transação `runTransaction` aplicada para garantir consistência.

**Aprendizados:**
- Manipulação segura da navegação com `WillPopScope` para evitar perda de dados.
- Implementação de carregamento progressivo com atualização incremental da UI.
- Boas práticas de otimização visual e correção de renderizações incompletas.
- Uso de `runTransaction` no Firestore para manter a integridade de dados em gravações complexas.

**Desafios enfrentados:**
- Garantir performance sem comprometer consistência dos dados e UX.
- Manter a responsividade da interface mesmo com dados grandes e carregamento em lote.
- Tratar falhas silenciosas e evitar trilhas “órfãs” ou incompletas no banco de dados.

**Observações:**
- Essa semana consolidou melhorias profundas no fluxo de trilhas, gravação e visualização, elevando a robustez do app a um novo nível.
