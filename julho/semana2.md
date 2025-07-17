### 🗓 Semana 2 — 08 a 12 de julho de 2025

**Tarefas realizadas:**
- Desenvolvimento da interface tipo **wizard** para o cadastro de torneios.
- Refatoração e ajustes finos nas **rotinas de gravação de tempo no ranking**, garantindo que dados incorretos não fossem salvos.
- Melhorias na **pesquisa da tela de mapa**, com respostas mais rápidas e relevantes.
- Geração de nova versão com modificações validadas.
- Melhorias na **pesquisa da tela de trilhas**, agora com normalização de texto (sem acentos e case insensitive).
- Tornado o **campo de categoria obrigatório** no formulário de perfil de usuário.
- Ajustado o filtro das trilhas com regras mais flexíveis e consistentes.

**Aprendizados:**
- Criação de formulários em etapas com navegação progressiva (wizard).
- Refino de validações em cascata e atualizações incrementais de UI.
- Implementação de busca com normalização e filtros por palavras-chave.
- Validação de `DropdownButtonFormField` com tratamento para valores inválidos.

**Desafios enfrentados:**
- Sincronizar etapas do cadastro de torneio sem quebra de fluxo.
- Evitar que erros de gravação passassem despercebidos em cenários de uso real.
- Garantir que filtros e pesquisas funcionassem bem com grandes volumes de dados.

**Observações:**
- A semana focou em fortalecer a confiabilidade da gravação de dados e em melhorar a experiência de navegação e cadastro.
