# Política de privacidade — StartWork

Versão de 28 de setembro de 2026 · Informações conforme o art. 13 do RGPD

> Esta tradução é fornecida por conveniência. A
> [versão em alemão](https://daddycation.github.io/startwork-datenschutz/)
> é a juridicamente vinculante.
>
> [English](https://daddycation.github.io/startwork-datenschutz/en/) · [Français](https://daddycation.github.io/startwork-datenschutz/fr/) · [Español](https://daddycation.github.io/startwork-datenschutz/es/)

## O essencial em três frases

O StartWork roda no seu aparelho. O fornecedor deste app **não coleta, não
armazena e não recebe nenhum dado seu** — não há servidor do fornecedor, nem
conta, nem análises, nem rastreamento, nem identificadores de publicidade.

Os dados só saem do seu aparelho para destinos **que você mesmo escolhe**.

## 1. Controlador

```
Philip Müller
Theaterstraße 27
09111 Chemnitz
Alemanha

E-mail: info@iamnotadev.xyz
```

Por força do Regulamento dos Serviços Digitais da UE (DSA), os mesmos dados
aparecem como informações do comerciante na página do app na App Store. Isso
é obrigatório para um app pago e não pode ser desativado.

## 2. O que fica salvo no aparelho

| Dados | Onde | Finalidade |
|---|---|---|
| Endereço da sua instância Jira, e-mail (só Cloud), ajustes | Armazenamento do aparelho (iOS: UserDefaults) | para você não ter de digitá-los toda vez |
| Token de acesso do Jira, chave de IA | **Chaves do aparelho** (iOS: Keychain) | login na sua instância Jira |
| Seus registros de horas (ticket, duração, comentário, horário) | Armazenamento do aparelho | visão do dia e dos dias anteriores |

Nada disso é transmitido ao fornecedor. **Base legal:** art. 6.º, n.º 1,
alínea b) do RGPD — sem esses dados o app não cumpre sua finalidade.

## 3. Para onde vão os dados

### 3.1 Sua instância Jira

Ao registrar horas, o StartWork envia a chave do ticket, a duração, o horário
de início e seu comentário **ao servidor Jira que você mesmo informou**. Seu
token é enviado para o login; ao consultar um ticket, é enviada a chave dele.

Quem opera esse servidor e o que acontece lá **não** é definido pelo
fornecedor deste app — normalmente é seu empregador ou a Atlassian. O
operador da instância é responsável por esse tratamento.

### 3.2 Anthropic (opcional, só com seu consentimento)

A função “Refinar” envia **seu comentário do registro junto com a chave e o
título do ticket** à Anthropic (`api.anthropic.com`, Estados Unidos), onde o
texto é processado e devolvido reformulado.

Isso acontece **somente** se você

1. salvou sua própria chave da Anthropic **e**
2. concordou expressamente com a transferência em uma janela separada **e**
3. de fato usa esse botão.

**Base legal:** art. 6.º, n.º 1, alínea a) do RGPD (consentimento). A
transferência para os EUA ocorre com base na relação contratual entre você e
a Anthropic — você usa seu próprio acesso.

**Revogação:** a qualquer momento no ícone de engrenagem, sem justificativa e
sem limitar o restante do app. A revogação vale daí em diante.

Aviso de privacidade da própria Anthropic:
<https://www.anthropic.com/legal/privacy>

### 3.3 Nada mais

Sem análises, sem relatórios de falhas, sem redes de publicidade, sem fontes
ou scripts de servidores de terceiros. O app não contém componentes que abram
uma conexão sem uma ação sua.

## 4. Prazo de armazenamento

Até você apagar. Não há exclusão automática.

**Apagar tudo:** ícone de engrenagem → “Apagar todos os dados deste
aparelho”. Isso remove as credenciais, a chave de IA, seus próprios blocos e
todo o histórico de registros. Se o app for removido, tudo vai junto.

As horas **já registradas no Jira** não são afetadas — elas ficam no
servidor da sua instância e precisam ser apagadas lá.

## 5. Seus direitos

Acesso, retificação, eliminação, limitação, portabilidade e oposição
(arts. 15.º a 21.º do RGPD), além do direito de apresentar reclamação a uma
autoridade de controle (art. 77.º do RGPD).

Na prática: como o fornecedor **não** tem nenhum dado seu, não há nada a
informar nem a apagar. Todos os dados estão no seu aparelho, sob seu
controle. Para dados na sua instância Jira, fale com o operador dela.

## 6. Crianças

O app é voltado a profissionais, não a crianças.

## 7. Alterações

A data no topo é atualizada quando esta política muda. Alterações relevantes
nas transferências de dados exigem novo consentimento.
