# SKOFICIAL

Site estático de links oficiais, pronto para publicar no GitHub Pages.

## Publicar

1. Crie um repositório no GitHub (por exemplo, `skoficial`).
2. Envie `index.html` e este `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/(root)`, depois clique em **Save**.
5. Aguarde a publicação. O endereço aparecerá nessa mesma seção do GitHub Pages.

## Segurança e privacidade

- O site não tem formulário, conta, analytics, rastreador ou backend.
- Os scripts e estilos são locais ao arquivo e a política CSP restringe recursos externos.
- Links externos usam `noopener noreferrer` e `no-referrer`; ao clicar, o visitante ainda se conecta ao serviço de destino.
- O GitHub Pages não permite configurar cabeçalhos HTTP personalizados por este projeto. A CSP está declarada no HTML; proteções que dependam de cabeçalhos do servidor precisam ser configuradas em uma hospedagem que ofereça esse recurso.
- Não coloque senhas, tokens ou dados privados no repositório.
