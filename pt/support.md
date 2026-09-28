# Ajuda do StartWork

> [Deutsch](../support) · [English](../en/support) · [Français](../fr/support) · [Español](../es/support)

O StartWork registra horas de trabalho no Jira. O app roda no seu aparelho e
se comunica apenas com a **sua própria** instância Jira.

**Contato:** [info@iamnotadev.xyz](mailto:info@iamnotadev.xyz)
Resposta geralmente em poucos dias. Pode escrever em português; a resposta
vem em inglês ou alemão.

Para agilizar a ajuda, informe: a versão do app, se você usa Jira Cloud ou
Jira Server/Data Center, e o texto exato da mensagem de erro.

---

## Perguntas frequentes

### Quais versões do Jira são compatíveis?

Jira Cloud (`…atlassian.net`) e também Jira Server e Data Center. No Cloud
você entra com seu e-mail e um token de API; no Server e no Data Center, com
um token de acesso pessoal.

### Onde consigo um token?

**Jira Cloud:** em <https://id.atlassian.com/manage-profile/security/api-tokens>.

**Jira Server / Data Center:** no seu Jira, em *Perfil → Personal Access
Tokens*. Se esse item não aparecer, os administradores do Jira o
desativaram — aí só resta pedir a eles.

### O app diz que meu ticket não existe.

Ou a chave está errada, ou sua conta não tem permissão para ver o ticket.
Você pode conferir as duas coisas abrindo o ticket no próprio Jira.

### Não consigo registrar horas em um ticket.

Se o ticket estiver em um status como “fechado” ou “concluído”, o Jira
bloqueia o registro de horas. Isso também não dá para contornar no próprio
Jira — escolha um ticket aberto.

### Usamos o Tempo. Funciona?

Sim. O StartWork grava um registro de trabalho padrão do Jira, e o Tempo lê
esses registros. **Mas:** se sua empresa exige campos do Tempo (*Work
Attributes*), eles ficam vazios. Se isso basta depende da sua configuração.

### O que acontece com meus dados?

Eles ficam no aparelho. Não há servidor do fornecedor, nem conta, nem
análises. Os detalhes estão na [política de privacidade](./).

### Como apago tudo?

*Ícone de engrenagem → Apagar todos os dados deste aparelho.* Isso remove as
credenciais, seus próprios blocos e todo o histórico. As horas já
registradas no Jira não são afetadas — elas ficam no servidor do Jira.

### O que faz “Refinar”?

O botão envia seu comentário do registro à Anthropic e recebe de volta uma
redação objetiva. Ele vem **desligado** e precisa de duas coisas: sua própria
chave da Anthropic e seu consentimento expresso. Sem as duas, nada sai do
aparelho. Você pode revogar o consentimento a qualquer momento no ícone de
engrenagem.

### Quais idiomas o app fala?

Português, inglês, alemão, francês e espanhol. Ele segue o idioma do seu
iPhone; no ícone de engrenagem você pode escolher um explicitamente.

---

Jira é uma marca da Atlassian, Tempo uma marca da Tempo ehf. O StartWork não
tem vínculo com essas empresas.
