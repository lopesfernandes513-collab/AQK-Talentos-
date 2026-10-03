# AKQ Talentos — protótipo

Este pacote contém uma primeira versão navegável do site.

## O que já funciona
- Cadastro de candidatos.
- Pesquisa pública de candidatos.
- Filtro por profissão.
- Planos: 300 Kz, 1.200 Kz/10 dias e 3.600 Kz/30 dias.
- Área de administrador.
- Código do administrador no protótipo: Akq12#
- Dados de demonstração guardados no navegador (localStorage).

## Importante para produção
Este protótipo NÃO deve ser publicado como sistema final.
Para produção, o código de administrador deve ficar no servidor, com palavra-passe com hash e sessão segura.
O pagamento deve ser integrado a um gateway que confirme automaticamente as transações. O IBAN deve ficar numa configuração segura do servidor.
Também devem ser implementados base de dados, autenticação, proteção de dados, logs, notificações, moderação e regras de consentimento para partilha de contactos.
