# Gestão Operacional — painel administrativo (protótipo)

## Executar
1. Instale Node.js LTS.
2. Abra o terminal nesta pasta.
3. Execute `npm install` e depois `npm run dev`.

## Funcionalidades da demonstração
- Base centralizada fictícia de colaboradores do estado de São Paulo.
- Cadastro e edição de colaboradores.
- Filtros por regional, equipe e situação; busca por nome, matrícula, equipe e supervisor.
- Indicadores de ativos, férias e afastados.
- Exportação CSV dos resultados filtrados.
- Interface responsiva e navegação dos módulos.

## Limitações importantes
Os dados são fictícios. Cadastro, edição e remoção funcionam apenas na memória do navegador e são perdidos ao recarregar. Ainda não existe autenticação, banco de dados, sincronização entre usuários, auditoria nem bloqueio real de acesso por regional. As permissões exibidas são uma proposta de arquitetura, não controles de segurança implementados. Para produção, conectar um backend (por exemplo, Supabase), configurar autenticação e políticas de acesso no servidor/banco e nunca inserir chaves privadas no frontend.
