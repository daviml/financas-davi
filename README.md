# Minhas Finanças

App de controle financeiro pessoal (gastos do dia a dia, contas do mês, orçamento, dívidas e reserva).
Roda no navegador e pode ser instalado no celular como app (PWA).

- **App:** publicado pelo GitHub Pages a partir deste repositório (só código, sem dados).
- **Dados:** ficam em um repositório **privado** separado (`dados.json`), sincronizados pelo próprio app.

## Conectar um aparelho
1. Abra o app → **Ajustes & backup** → **Sincronizar entre aparelhos**.
2. Repositório: `usuario/repositorio-de-dados`.
3. Token: fine-grained, acesso só ao repositório de dados, permissão **Contents: Read and write**.
   No celular, cole o **código de conexão** copiado no computador.

## Instalar no celular
Abra o endereço do GitHub Pages no Chrome → menu ⋮ → **Instalar app** / **Adicionar à tela inicial**.
