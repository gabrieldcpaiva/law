# Guia de Sobrevivência — contestação de compra no cartão, conta de pagamento bloqueada e cobrança com ameaça

> Um guia prático, verificável e reutilizável para o cenário: **o titular de um cartão contesta compras, o lojista tem a conta na credenciadora bloqueada/encerrada com saldo devedor, e passa a pressionar ou ameaçar o comprador.**
>
> **Versão pública, anonimizada.** Nenhum nome, CPF, número de cartão, cidade ou valor real aparece aqui. Substitua os campos entre `[colchetes]` pelos seus dados **apenas na sua cópia local**, nunca em um repositório público.
>
> **Última revisão:** 27 de outubro de 2026.
> **Aplicação:** Brasil (CDC, regras do SFN/BCB, arranjos de pagamento). Exemplos de canais estaduais usam Minas Gerais; adapte para o seu estado.
>
> ⚠️ **Isto é orientação informativa, não consultoria jurídica.** Em caso de ameaça, risco criminal ou disputa judicial, procure advogado ou a **Defensoria Pública** (gratuita para quem não pode contratar advogado).

---

## 🇬🇧 Summary

A chargeback is not undone by the payment platform — **only the card issuer and the card brand can cancel it**. When a seller's account is blocked because of disputes, the useful things you can provide are: (1) the issuer's **protocol numbers** proving the disputes were withdrawn, and (2) a **short, truthful, handwritten declaration** from the cardholder, sent only through a **verified official channel** with a watermark. Never pay twice, never sign a false statement, never hand over unwatermarked ID + card + signature, and never promise the seller you can reactivate his account. If there is a threat, treat that as the priority: don't open the door, preserve evidence, call 190, and file a police report. Where the underlying purchase was medication for a sick child, there is a **free legal route** to obtain it (SUS / Defensoria Pública) — see section 11.

---

## 0. Regra de ouro (leia antes de tudo)

| Faça | Não faça |
|---|---|
| Preserve sua segurança física primeiro | Não receba ninguém em casa, não saia na rua para "conversar" |
| Obtenha **protocolos do emissor** do cartão | Não tente resolver o bloqueio na credenciadora (ela não cancela chargeback) |
| Pague **uma vez** — pela fatura do cartão | Não faça Pix/dinheiro por fora ("cobrir o prejuízo") |
| Assine **somente o que for verdadeiro** | Não invente justificativa nem assine modelo pronto sem conferir |
| Envie documentos com **marca d'água** e por canal oficial | Não mande RG + cartão + assinatura sem proteção por WhatsApp |
| Seja honesto sobre prazos (semanas) | Não prometa "resolve hoje" — isso alimenta o desespero alheio |

---

## 1. Entenda a cadeia (quem pode fazer o quê)

```
TITULAR DO CARTÃO ──(1)──> BANCO EMISSOR ──(2)──> BANDEIRA (Visa/Master)
                                                      │
                                                   (3) │ notificação
                                                      ▼
COMPRADOR <──(5)── LOJISTA <─────(4)──── CREDENCIADORA (ex.: InfinitePay)
```

- **(1)** A contestação (chargeback) é aberta pelo **titular junto ao emissor**.
- **(2)(3)** O emissor aciona a bandeira, que notifica a credenciadora. O valor é **debitado imediatamente do lojista**, antes mesmo de qualquer disputa.
- **(4)** A credenciadora **não consegue reverter** o chargeback diretamente — ela apenas **intermedia o envio de documentos** para a defesa do lojista.
- **(5)** Portanto: **o cancelamento da contestação depende exclusivamente do emissor e da bandeira.**

> Frase real dita pela própria credenciadora em resposta pública: *"caso a portadora do cartão reconheça que houve equívoco na contestação, é necessário que ela própria entre em contato com o banco emissor para solicitar o cancelamento do chargeback, uma vez que esse procedimento depende exclusivamente do emissor e da bandeira, não sendo passível de reversão direta por parte da credenciadora."* — [Reclame Aqui](https://www.reclameaqui.com.br/infinite-pay/debito-indevido-por-chargeback-sem-notificacao-previa-e-cerceamento-de-defesa_GKQnoXfalttuZ3-d/)

**Consequência prática:** por **sigilo bancário (LC 105/2001)**, nem você fala pela conta do lojista, nem ele fala pelo cartão do titular. Cada um trata com a **sua** instituição. Você é terceiro nas duas relações.

### Leitura correta dos sintomas

| O que aparece no app do lojista | O que realmente significa |
|---|---|
| `Saldo devedor R$ [X]` | Dívida gerada pelos estornos, geralmente o **valor líquido** das compras (bruto menos taxas da maquininha). Indica que o repasse já ocorreu — **não é "dinheiro dele preso"**. |
| `Você tem N contestações` | Quantidade de disputas ativas. A queda de 6 para 2 indica **baixa parcial** — confirme no emissor. |
| Status `Em processo` | **Disputa em andamento**, não "cancelamento em andamento". Não prove nada. |
| `Reduza suas taxas: R$ [Y] / R$ 20 mil` | Indicador de volume do período. Se as contestações representarem >5% do volume, o antifraude é acionado (bandeiras toleram ~1%–2%). |
| Múltiplas tentativas `Negada` antes de aprovações | Padrão de "teste de cartão". Some a várias contestações e o risco de **descredenciamento** é alto. |

---

## 2. Prioridade zero: ameaça e segurança

Se alguém diz que "vem na sua casa", trate como risco real.

**Ações imediatas**

1. **Não abra o portão, não saia na rua, não receba ninguém.** Mantenha crianças dentro de casa. Carregue o celular.
2. **Não pague e não entregue documentos na porta.**
3. **Preserve tudo:** prints com data/hora visível, áudios encaminhados para um contato de confiança, mensagens originais sem apagar.
4. **Ligue 190** (Polícia Militar) em caso de iminência. **197** (Polícia Civil) para investigação. **192** SAMU, **193** Bombeiros.
5. **Registre Boletim de Ocorrência** — presencialmente na delegacia da sua comarca ou pela **Delegacia Virtual** (em MG: `delegaciavirtual.sids.mg.gov.br`, sem www, ou app **MG App** — [PCMG](https://www.policiacivil.mg.gov.br/pagina/servico-delegacia-virtual), [MG.gov](https://www.mg.gov.br/servico/solicitar-registro-de-ocorrencia-na-delegacia-virtual)). ⚠️ A natureza **"Ameaça"** no formulário online de MG é **restrita a vítimas de violência doméstica/familiar** (mulheres, crianças, adolescentes, idosos 60+) — [MG.gov](https://www.mg.gov.br/servico/solicitar-registro-de-ocorrencia-de-ameaca-violencia-domestica). Para os demais casos, **vá presencialmente**.
6. ** Não ameace de volta.** Isso protege você juridicamente.

**Tipificações possíveis** (para constar no BO, sem fazer acusação temerária): ameaça (art. 147, CP), exercício arbitrário das próprias razões (art. 345, CP), extorsão se houver exigência de dinheiro com ameaça (art. 158, CP), cobrança abusiva/vexatória (art. 42, CDC).

**Fala curta para o 190**

```
"Tem uma pessoa na porta da minha casa fazendo ameaças por causa de uma
cobrança de cartão de crédito. Tem criança dentro de casa. Meu endereço é
[endereço completo]. A pessoa está [na rua / no portão / tentando entrar]."
```

Você **não precisa descrever a compra** para pedir ajuda contra uma ameaça. Mas **nunca minta** para a polícia.

---

## 3. O que NÃO fazer (erros que pioram tudo)

1. **Pagar duas vezes.** Se as compras voltaram a ser cobradas na fatura, um Pix "por fora" faz você pagar de novo — e pode agravar o bloqueio por parecer autofinanciamento.
2. **Assinar declaração falsa.** Dizer "a contestação foi aberta por equívoco de identificação" ou "os produtos foram entregues sem pendência" quando isso não é literalmente verdadeiro é **falsidade ideológica (art. 299, CP)**. É um risco gratuito e desnecessário.
3. **Inventar uma "versão oficial".** Não oriente ninguém a mentir para banco ou credenciadora. Você não é obrigado a **descrever** o produto em nenhum documento — mas também não pode afirmar o que é falso. Reconhecer as compras é suficiente.
4. **Prometer prazo curto ou reativação.** A análise da bandeira leva até **45 dias** (a credenciadora cita até 65 dias em alguns casos Mastercard). A resposta padrão pública sobre contas bloqueadas costuma ser "**não haverá reativação de acesso ou continuidade dos serviços**" — [Reclame Aqui](https://www.reclameaqui.com.br/infinite-pay/conta-bloqueada_wrA5byTSuiszuz38/). Prometer o contrário gera frustração e pressão sobre você.
5. **Mandar RG/CNH + cartão + assinatura sem proteção.** É um kit completo de fraude de identidade.
6. **Acreditar em "Política de Reativação".** Não existe garantia de reativação. O objetivo realista é: **baixar a dívida do chargeback + exigir a destinação do saldo** para conta de mesma titularidade.
7. **Confundir com Pix/MED.** O prazo de 8 dias do **MED** (Mecanismo Especial de Devolução, Res. BCB 103/2021) vale para **Pix**. Este caso é **chargeback de cartão de crédito** — valem as regras da bandeira.

---

## 4. Plano de ação em 3 tempos

### 4.1 Hoje (30 minutos)

- [ ] Travar porta/portão; crianças dentro; celular carregado.
- [ ] Enviar **Mensagem 1** (abaixo) ao lojista — firme, calma, sem dinheiro, sem visita.
- [ ] Enviar **Mensagem 2** ao titular do cartão.
- [ ] Fazer backup de prints e áudios.

### 4.2 Amanhã de manhã (08:00)

- [ ] Ligar para a **Central do emissor** com o titular na linha (roteiro abaixo).
- [ ] Obter **protocolos**: o da ligação do dia anterior e o da ligação atual.
- [ ] Confirmar que **todas** as `[N]` contestações foram canceladas — e não só parte.
- [ ] Pedir confirmação por escrito (SMS/e-mail/registro no app).

### 4.3 Próximos dias

- [ ] Preencher a **declaração** (versão segura, abaixo) com o protocolo real.
- [ ] Confirmar a origem do pedido de documentos da credenciadora (**e-mail oficial** enviado ao e-mail cadastrado do lojista, ou tela `Contestações → Recorrer` no app dele).
- [ ] Enviar documentos **com marca d'água**, por canal oficial.
- [ ] Entregar ao lojista os protocolos + o **modelo de reclamação** (Mensagem 7) para ele direcionar a cobrança à credenciadora — e não a você.
- [ ] Se não resolver em 7 dias: escalar (seção 9).

---

## 5. Mensagem 1 — para o lojista (desescalada)

```
[Nome], entendo seu desespero e não estou fugindo — quero resolver. Mas preciso
ser honesto pra não te enrolar com promessa que não depende de mim.

1) O titular do cartão já ligou para o banco emissor ([emissor]) hoje e pediu o
   cancelamento das [N] contestações: [lista de valores]. Amanhã de manhã ele
   liga de novo comigo na linha para confirmar TODAS e pegar os números de
   protocolo. Assim que eu tiver, te mando.

2) O estorno não depende da credenciadora: segundo a própria [credenciadora],
   o cancelamento do chargeback depende exclusivamente do banco emissor e da
   bandeira [Visa/Mastercard]. O que destrava é o protocolo do emissor, não
   pressão em cima de mim. O prazo da bandeira pode chegar a 45 dias — ninguém
   resolve isso em algumas horas, por mais que a gente queira.

3) Sobre os documentos que você pediu (identidade, cartão, declaração): vou
   providenciar. Só preciso que você me encaminhe ANTES o e-mail oficial que a
   [credenciadora] enviou para o e-mail cadastrado na conta de vocês pedindo
   essa documentação, ou um print da tela Ajustes > Contestações > Recorrer do
   seu app. Eu mando tudo com marca d'água e só por canal oficial, porque são
   dados pessoais do titular e preciso protegê-los (LGPD).

4) Não vou fazer Pix nem entregar dinheiro. As [N] compras voltaram a ser
   cobradas normalmente na fatura e o valor será creditado para você pelo
   sistema. Se eu pagar por fora, pago duas vezes e ainda posso travar mais a
   sua conta.

5) Sobre a conta bloqueada/encerrada: isso é entre você e a [credenciadora], e é
   aí que você precisa cobrar. Pela Resolução BCB 96/2021, art. 12, eles devem
   avisar por escrito, informar os motivos, dar prazo de até 30 dias e
   transferir eventual saldo para uma conta da SUA titularidade. Vale registrar
   reclamação na Ouvidoria, no Consumidor.gov.br, no Banco Central e no Procon.
   Eu te passo o texto pronto, é só preencher.

6) Por favor, não venha aqui em casa. Tem criança aqui e isso só piora tudo. Não
   vou abrir o portão e não vou receber ninguém. Qualquer conversa, vamos por
   mensagem ou, se você fizer questão, num lugar público e com mais uma pessoa
   junto. Me manda o e-mail oficial deles que eu corro com a documentação.
```

---

## 6. Mensagem 2 — para o titular do cartão (sem culpa)

```
[Tratamento], obrigado por ter ligado no banco hoje de manhã, isso já ajudou
muito. Só falta um detalhe chato: eram [N] compras no mesmo link ([lista de
valores]) e a atendente pode ter dado baixa em algumas e esquecido outras. Por
causa disso o aplicativo do vendedor travou e ele está me cobrando.

Me ajuda em duas coisas rápidas amanhã cedo, por favor:

1) A gente liga junto no [0800 da central, 24h]. Você só precisa confirmar seus
   dados e falar: "autorizo [seu nome] a falar em meu nome nesta ligação". Eu
   pergunto se as [N] contestações foram canceladas e anoto os protocolos.
   Deixa RG, CPF e o cartão do lado do telefone.

2) Preciso que você escreva À MÃO, numa folha, um textinho curto que eu já
   deixei pronto, e assine embaixo igual ao seu RG. É só dizer que você
   reconhece as [N] compras e pediu o cancelamento das contestações. Não
   precisa descrever o que foi comprado. Depois eu tiro uma foto e mando pelo
   canal oficial do banco.

Não é nada contra você e não tem nenhum custo. É só um papel pra destravar o
aplicativo do rapaz. Eu faço tudo junto com você.
```

---

## 7. Roteiro de ligação para o emissor

**Boa prática:** ligue pelo número que está **no verso do cartão** ou no app oficial. Confirme os 0800s no site do emissor — nunca use número recebido por mensagem de terceiro.

```
"Boa dia. O titular é [NOME COMPLETO], cartão [BANDEIRA] [EMISSOR] final
[4 DÍGITOS]. Ele(a) está aqui comigo e autoriza que eu fale em nome dele(a)
nesta ligação." [titular confirma os dados de segurança]

"Preciso confirmar o cancelamento das [N] contestações abertas em [DATA] sobre
as compras por link de pagamento de [DATA], nos valores de [lista de valores]
(total R$ [TOTAL]).

Por favor:
1) Confirme se TODAS as [N] contestações foram canceladas — e não apenas parte.
   Se faltar alguma, cancele agora, por favor.
2) Informe o protocolo DESTA ligação e também o protocolo da ligação de
   [DATA] (a gravação fica guardada por no mínimo 90 dias — Decreto
   11.034/2022).
3) Confirme que as [N] compras continuarão sendo cobradas normalmente na fatura.
4) Confirme se o cancelamento já foi comunicado à bandeira e à credenciadora,
   e qual o prazo estimado de baixa.
5) Envie a confirmação por escrito (e-mail/SMS) ou indique onde vejo isso no app."
```

**Anote:** data/hora, nome do atendente, **todos os protocolos**.

Se houver recusa: peça o supervisor, registre o protocolo da recusa e escale na ordem da seção 9.

---

## 8. Declaração — versão segura e verdadeira

**Regras antes de escrever**

- Escrita **à mão, pelo próprio titular**, caneta, papel limpo, sem rasuras.
- **Somente o que for verdadeiro.** Não invente motivo ("equívoco de identificação"), não afirme entrega inexistente, **não descreva o produto**.
- **Não invente protocolo.** Deixe em branco e preencha depois da ligação.
- **CPF:** apenas na via destinada ao **emissor**. Omita na via que for para a credenciadora.
- **Nunca assine folha em branco** nem modelo pronto sem conferir cada frase.

```
DECLARAÇÃO DE RECONHECIMENTO DE COMPRA
E PEDIDO DE CANCELAMENTO DE CONTESTAÇÃO

Eu, [NOME COMPLETO DO TITULAR], titular do cartão de crédito
[BANDEIRA] [EMISSOR], final [4 DÍGITOS], declaro que reconheço
como legítimas as [N] ([N por extenso]) compras realizadas por
link de pagamento em [DATA], nos valores de [lista de valores]
(total de R$ [TOTAL]).

Solicitei a [EMISSOR], em [DATA], o cancelamento integral das
contestações abertas sobre essas transações, e autorizo que elas
sejam mantidas e cobradas normalmente em minha fatura.

Protocolo do pedido de cancelamento: ______________________.

Declaro que as informações acima são verdadeiras. Este documento
destina-se exclusivamente à análise das contestações junto à
[EMISSOR], à bandeira [BANDEIRA] e à [CREDENCIADORA]. Não autorizo
qualquer outra utilização dos meus dados pessoais (LGPD, Lei
13.709/2018).

[CIDADE/UF], [DATA POR EXTENSO].


______________________________________________
[NOME COMPLETO DO TITULAR]
(assinatura igual à do documento de identidade)
```

### Como enviar documentos sem criar risco de fraude

O pedido de **identidade + foto do cartão + declaração manuscrita** é legítimo: é exatamente o checklist publicado pela credenciadora — *"Foto do cartão: mostre apenas os 4 últimos dígitos e o nome do titular. Oculte as outras informações (nada de CVV ou número completo)"* e *"Declaração manuscrita: peça pro cliente escrever à mão uma autorização pra compra. Combine isso com a foto do cartão e do documento de identificação"* — [Central de Ajuda InfinitePay](https://ajuda.infinitepay.io/pt-BR/articles/5797557-quais-documentos-posso-solicitar-ao-fazer-uma-venda-online). O caminho oficial de defesa é **App → Ajustes → Contestações → tocar na contestação → Recorrer → anexar documentos → Enviar documentos** — [Central de Ajuda](https://ajuda.infinitepay.io/pt-BR/articles/5832039-como-acompanhar-as-contestacoes-recebidas-pelo-meu-estabelecimento). O prazo contratual para o lojista apresentar documentos pode ser de apenas **2 dias úteis** — [Contrato de Afiliação, cláusula 12.1](https://www.infinitepay.io/legal/contrato-de-afiliacao).

Mas é **também** um kit clássico de fraude de identidade. Então:

✅ **Faça**

- **Confirme a origem.** Peça o **e-mail oficial** enviado ao e-mail cadastrado do lojista (é assim que a credenciadora solicita documentos — [exemplo](https://www.reclameaqui.com.br/infinite-pay/cobranca-indevida-por-contestacao-de-compra_TOS94BN3AuEjEZSe/)) ou print da tela `Contestações → Recorrer/Pendências` no app dele. Se o pedido chegou só por **mensagem encaminhada**, confirme por **ligação de voz** antes de enviar qualquer coisa.
- **Marca d'água em diagonal sobre TODAS as fotos:**
  `USO EXCLUSIVO — CONTESTAÇÃO [CREDENCIADORA]/[EMISSOR] — PROTOCOLO ______ — [DATA] — CÓPIA SEM VALOR COMERCIAL`
- **Minimize:** no cartão, **só nome + 4 últimos dígitos**; cubra número, validade e **CVV**. Na identidade, prefira cobrir parcialmente CPF e número do RG mantendo foto e nome legíveis.
- **Canal oficial:** o próprio lojista anexa no app dele; você envia ao emissor pelo protocolo da ligação.
- **Guarde cópia** de tudo enviado, com data/hora. Depois, o titular pode pedir **exclusão dos dados** (LGPD, art. 18).

❌ **Não faça**

- Manda RG/CNH + cartão + assinatura **sem marca d'água** para um número de WhatsApp/Messenger.
- Enviar **CVV, número completo, validade, senha, CPF em texto solto** no chat.
- Assinar **folha em branco**.
- Enviar selfie com documento, comprovante de residência ou dados bancários do titular.

> **Nota:** a apresentação de documentos **não garante** a reversão da contestação — a própria credenciadora ressalta isso. A decisão é da bandeira e do emissor.

---

## 9. Escalonamento (quando a ligação não resolve)

**Ordem recomendada** — guarde o protocolo de cada etapa:

1. **Central de Atendimento / SAC do emissor** (24h, gratuito). Prazo de resposta: **7 dias corridos** — Decreto 11.034/2022, art. 13 ([Planalto](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/decreto/d11034.htm)).
2. **Ouvidoria do emissor** — resposta em até **10 dias úteis** (Res. CMN 4.860/2020). Exige protocolo válido do atendimento primário.
3. **Ouvidoria da credenciadora** — mesmo prazo de 10 dias úteis ([Central de Ajuda InfinitePay](https://ajuda.infinitepay.io/pt-BR/articles/13560072-como-e-quando-falar-com-a-ouvidoria-da-infinitepay)).
4. **Consumidor.gov.br** (plataforma oficial do Ministério da Justiça).
5. **Banco Central do Brasil → "Registrar reclamação"** (bcb.gov.br). A reclamação é encaminhada à instituição, que responde em prazo regulamentar.
6. **Procon** municipal/estadual.
7. **Juizado Especial Cível** da sua comarca (até 20 salários mínimos, sem advogado; com pedido de **tutela de urgência** se houver risco).
8. **Defensoria Pública** — gratuita, para quem não pode contratar advogado ([unidades DPMG](https://defensoria.mg.def.br/unidades/)).

### Modelo de reclamação do titular → emissor

```
ASSUNTO: Confirmação de cancelamento de [N] contestações — cartão final [4 DÍGITOS]

Eu, [NOME COMPLETO], titular do cartão [BANDEIRA] [EMISSOR] final [4 DÍGITOS],
venho solicitar:

1) Confirmação por escrito de que TODAS as [N] contestações abertas em [DATA]
   sobre as compras por link de pagamento de [DATA] ([valores] — total
   R$ [TOTAL]) foram integralmente canceladas, com manutenção das cobranças
   em minha fatura.
2) Envio dos números de protocolo da ligação de [DATA] e desta solicitação,
   bem como cópia/gravação do atendimento.
3) Comprovação de que o cancelamento foi comunicado à bandeira e à
   credenciadora, com prazo estimado de baixa.

Fundamento: CDC, art. 6º, III e art. 14; Súmula 479 do STJ; Decreto
11.034/2022, art. 13 (7 dias corridos); Res. CMN 4.860/2020 (Ouvidoria).
Sem atendimento, encaminharei reclamação à Ouvidoria, ao Consumidor.gov.br,
ao Banco Central e ao Procon, sem prejuízo das medidas judiciais cabíveis.

Aguardo resposta conclusiva em 7 (sete) dias corridos.

[Nome, CPF, telefone, e-mail, cidade/data, assinatura]
```

### Modelo de reclamação do lojista → credenciadora

> Entregue este texto ao lojista. É o caminho produtivo para ele — e tira a pressão de cima de você.

```
ASSUNTO: Encerramento de conta / saldo devedor de R$ [X] por chargebacks
         cancelados pelo emissor — pedido de reanálise e destinação de saldo

Sou titular da conta lojista [nome/CNPJ] na [CREDENCIADORA]. Em [DATA],
[N] transações por link de pagamento de [DATA] ([valores] — total R$ [TOTAL])
sofreram contestação pelo portador do cartão. O portador RECONHECEU as compras
e solicitou ao banco emissor ([EMISSOR]), em [DATA], o cancelamento integral
das contestações (Protocolo nº ____________).

Requeiro:
1) Indicação por escrito das operações consideradas irregulares, da cláusula
   específica descumprida e da justificativa técnica do bloqueio/encerramento.
2) Memória de cálculo discriminada do saldo devedor de R$ [X] e a baixa desse
   débito tão logo os chargebacks cancelados sejam compensados.
3) Transferência de eventual saldo remanescente para conta de MINHA
   titularidade (mesmo CPF/CNPJ), nos termos da Resolução BCB 96/2021,
   art. 12, II.
4) Cumprimento do rito do art. 12 da Res. BCB 96/2021: comunicação prévia da
   intenção de rescindir com os motivos, prazo de até 30 dias corridos,
   informações sobre o saldo devedor e comunicação da data de encerramento.
5) Esclarecimento sobre a retenção de valores por 120 dias: trata-se de
   política interna de risco, não de regra legal absoluta, e deve ser
   concretamente justificada ([análise](https://perdiacesso.com.br/AC/mancio-lima/servico/176-dinheiro_retido_-_infinitepayem-mancio-lima---ac.html)).
   Requeiro liberação antecipada ou indicação de data certa de liberação.
6) Reanálise do descredenciamento definitivo, tendo em vista que as
   contestações foram retiradas pelo próprio portador.

Anexos: prints do app, protocolo do emissor, declaração de reconhecimento de
compra, comprovantes/nota fiscal, contrato/recibo, comprovante de entrega
quando houver, trocas de mensagens com o cliente.

Fundamento: CDC (arts. 6º, III e VIII; 14; 51), Súmula 479 do STJ, Resolução
BCB 96/2021 ([art. 12](https://legismap.com.br/leis-e-normas/resolucao-bcb-n-096-de-19-05-2021)),
Res. CMN 4.860/2020 (Ouvidoria — até 10 dias úteis). Sem solução, registrarei
reclamação no Banco Central, no Consumidor.gov.br, no Procon e adotarei medida
no Juizado Especial Cível, com pedido de tutela de urgência.

[Nome, CPF/CNPJ, e-mail cadastrado, telefone, data, assinatura]
```

---

## 10. Checklist de provas

- [ ] Prints de todas as telas do app do lojista (contestações, saldo devedor, histórico, barra de volume).
- [ ] Conversa completa no WhatsApp/Messenger **com data/hora visível**, inclusive mensagens encaminhadas.
- [ ] Todos os áudios, com cópia em outro número de confiança.
- [ ] Fatura do cartão (antes e depois) com as compras.
- [ ] **Protocolos das ligações** com o emissor (data/hora, nome do atendente).
- [ ] Cópia da declaração assinada e de todos os documentos enviados (com marca d'água).
- [ ] Comprovante do BO (REDS) se houver ameaça.
- [ ] Protocolos de SAC, Ouvidoria, Consumidor.gov.br, BACEN e Procon.

---

## 11. A parte que realmente importa: conseguir o medicamento de forma legal e gratuita

Se a compra que originou tudo era um **medicamento para uma criança**, existe um caminho seguro, gratuito e rápido — e ele evita que você volte a precisar de fornecedores informais (que além do risco jurídico oferecem risco sanitário: produto sem registro, sem procedência e sem eficácia garantida).

### Rota administrativa (comece aqui, hoje)

1. **Leve a criança a uma UBS / unidade de saúde do SUS** e peça:
   - **receita médica atualizada**;
   - **relatório médico detalhado** com CID, diagnóstico, justificativa clínica, posologia, tempo de tratamento e urgência;
   - exames previstos no protocolo clínico da doença.
   O relatório é o documento mais importante de todos.
2. **Peça o medicamento na farmácia da atenção básica / Farmácia de Minas** (ou equivalente no seu estado). Para medicamentos do **Componente Especializado da Assistência Farmacêutica (CEAF)**, o pedido é gratuito e pode ser aberto pelo **MG App / Cidadão MG** em `Saúde → Medicamentos → Solicita medicamento especializado`, ou presencialmente na farmácia de referência do município — [Governo de Minas](https://www.mg.gov.br/servico/solicitar-medicamentos-especializados), [Farmácia Digital SES-MG](https://www.saude.mg.gov.br/farmaciadigital/). Leve CPF, comprovante de endereço, **Cartão Nacional do SUS (CNS)**, receita, relatório e exames.
3. **Guarde o protocolo do pedido administrativo** — ele é necessário para a via judicial.
4. Se não houver resposta, registre reclamação na **Ouvidoria do SUS** (municipal, estadual ou federal) e peça ajuda ao **serviço social** da unidade.

### Rota gratuita com advogado (Defensoria Pública)

A **Defensoria Pública** atua na área de **Saúde** e é gratuita para quem não pode contratar advogado — [DPMG Saúde](https://defensoria.mg.def.br/areas-de-atuacao/saude/). Ela resolve muito caso **sem processo judicial**, por cooperação técnica com as secretarias de saúde. Em MG há ainda o ponto de apoio **ReMediar**, que faz doação de medicamentos mediante receita e relatório médico — [DPMG: como conseguir medicamentos](https://defensoria.mg.def.br/saber-direito/como-conseguir-medicamentos-pela-defensoria-publica/). Procure a unidade da sua comarca ([unidades DPMG](https://defensoria.mg.def.br/unidades/)) ou a Defensoria na Assembleia Legislativa ([ALMG — Espaço Cidadania](https://www.almg.gov.br/servicos/espaco-cidadania/defensoria-publica/)).

### Rota judicial (quando há urgência)

Se a condição clínica não permite esperar, a Defensoria pode ajuizar **ação de obrigação de fazer com pedido de tutela de urgência (liminar)**, que pode ser concedida antes mesmo da contestação, com multa diária em caso de descumprimento — [modelo do Núcleo de Saúde da DPMG](https://www.tjmg.jus.br/lumis/portal/file/fileDownload.jsp?fileId=8ACC82D28F31C8B3018F39E864FA5527). Documentos típicos: RG/CPF da criança e do responsável, comprovante de residência, Cartão do SUS, receita, **relatório médico circunstanciado**, exames, prova do pedido/negativa administrativa e orçamentos.

⚠️ **Seja realista quanto ao medicamento não incorporado ao SUS.** Após os **Temas 6 e 1.234 da repercussão geral do STF**, o fornecimento judicial de medicamento fora da lista exige requisitos cumulativos — laudo médico fundamentado comprovando imprescindibilidade e ineficácia das alternativas do SUS, incapacidade financeira, **registro na ANVISA**, evidência científica de alto nível e negativa administrativa prévia — [TJMG](https://www5.tjmg.jus.br/jurisprudencia/relatorioEspelhoAcordao.do?inteiroTeor=true&ano=25&ttriCodigo=1&codigoOrigem=0000&numero=003732&sequencial=002&sequencialAcordao=0). Ou seja: **medicamento sem registro no Brasil praticamente não é obtenível pela via judicial** — mais um motivo para não depender do mercado informal. Se o remédio prescrito não tem registro, peça ao médico para indicar a **alternativa terapêutica registrada e disponível no SUS**.

> Se você já comprou algo de origem informal: **não jogue fora e não use sem orientação** — leve a embalagem ao médico ou a um farmacêutico da UBS para avaliar. E não faça declarações sobre isso sem orientação de advogado/Defensoria; você tem o direito de permanecer em silêncio sobre o que possa te incriminar, **sem mentir**.

---

## 12. Fundamentação legal (resumo)

| Tema | Norma |
|---|---|
| Responsabilidade objetiva do fornecedor | CDC (Lei 8.078/90), art. 14 |
| Informação clara; inversão do ônus da prova | CDC, art. 6º, III e VIII |
| Cláusulas abusivas; cobrança vexatória | CDC, arts. 51 e 42 |
| Fraudes e delitos de terceiros (fortuito interno) | Súmula 479 do STJ |
| Sigilo bancário | LC 105/2001 |
| Proteção de dados pessoais | LGPD (Lei 13.709/18), arts. 6º e 18 |
| Encerramento de conta de pagamento | Res. **BCB 96/2021, art. 12** — comunicação, motivos, até 30 dias, destinação do saldo ([texto](https://legismap.com.br/leis-e-normas/resolucao-bcb-n-096-de-19-05-2021), [análise](https://conjur.com.br/2026-set-09/contraditorio-no-encerramento-unilateral-de-contas-de-pagamento/)) |
| Ouvidoria | Res. CMN 4.860/2020 — até 10 dias úteis |
| SAC | Decreto 11.034/2022, art. 13 — 7 dias corridos; gravação por 90 dias; registro por 2 anos ([Planalto](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/decreto/d11034.htm), [PDF Procon-SP](https://www.procon.sp.gov.br/wp-content/uploads/2022/10/DECRETO_11034_2022.pdf)) |
| Pix MED (****não se aplica a chargeback****) | Res. BCB 103/2021 |
| Ameaça / exercício arbitrário / extorsão / falsidade ideológica | CP, arts. 147, 345, 158, 299 |
| Prazo para contestar compra | Até 90 dias da transação (regras da bandeira / termos da credenciadora) |

**Atenção sobre o Decreto do SAC:** um novo decreto (nº 13.135/2026) foi publicado em 26/10/2026 e entra em vigor 20 dias depois, revogando o Decreto 11.034/2022. Ele mantém a resposta em 7 dias corridos e reforça atendimento humano, cobrança indevida suspensa em até 48h e cobrança indevida imediata — [Ministério da Justiça](https://www.gov.br/mj/pt-br/assuntos/noticias/novo-decreto-do-sac-amplia-protecao-ao-consumidor-e-estabelece-regras-de-atendimento).

---

## 13. Prazos em uma tabela

| O quê | Prazo |
|---|---|
| Resposta do SAC | 7 dias corridos |
| Retorno da Ouvidoria | Até 10 dias úteis |
| Lojista apresentar documentos na disputa | Até 2 dias úteis (cláusula contratual — confirme no seu contrato) |
| Análise da contestação pela bandeira | Até 45 dias (até 65 em alguns casos) |
| Prazo para o portador contestar | Até 90 dias da transação |
| Retenção de saldo pela credenciadora | Até 120 dias (política interna, questionável) |
| Encerramento de conta de pagamento | Comunicação + até 30 dias corridos (Res. BCB 96/2021) |
| Registro de ocorrência online | Até 30 dias do fato (alguns tipos) — faça quanto antes |

---

## 14. Fontes

**Credenciadora / chargeback**

- [Central de Ajuda InfinitePay — Como acompanhar as contestações / Recorrer](https://ajuda.infinitepay.io/pt-BR/articles/5832039-como-acompanhar-as-contestacoes-recebidas-pelo-meu-estabelecimento)
- [Central de Ajuda InfinitePay — Quais documentos posso solicitar ao fazer uma venda online](https://ajuda.infinitepay.io/pt-BR/articles/5797557-quais-documentos-posso-solicitar-ao-fazer-uma-venda-online)
- [Central de Ajuda InfinitePay — O que acontece se meu estabelecimento tiver uma venda contestada](https://ajuda.infinitepay.io/pt-BR/articles/3944818-o-que-acontece-se-meu-estabelecimento-tiver-uma-venda-contestada)
- [InfinitePay — Chargeback: como reverter uma contestação de venda](https://www.infinitepay.io/blog/chargeback-como-reverter-uma-contestacao-de-venda)
- [InfinitePay — Como e quando falar com a Ouvidoria](https://ajuda.infinitepay.io/pt-BR/articles/13560072-como-e-quando-falar-com-a-ouvidoria-da-infinitepay)
- [Termos de Uso](https://www.infinitepay.io/legal/termos-de-uso) · [Contrato de Afiliação](https://www.infinitepay.io/legal/contrato-de-afiliacao)
- [Reclame Aqui — "cancelamento depende exclusivamente do emissor e da bandeira"](https://www.reclameaqui.com.br/infinite-pay/debito-indevido-por-chargeback-sem-notificacao-previa-e-cerceamento-de-defesa_GKQnoXfalttuZ3-d/)
- [Reclame Aqui — "não haverá reativação de acesso"](https://www.reclameaqui.com.br/infinite-pay/conta-bloqueada_wrA5byTSuiszuz38/)
- [Reclame Aqui — retenção de 120 dias](https://www.reclameaqui.com.br/infinite-pay/bloqueio-de-conta-e-retencao-de-saldo-na-infinity-pay_QLJPglGsce79VpSe/) · [análise: não é regra legal absoluta](https://perdiacesso.com.br/AC/mancio-lima/servico/176-dinheiro_retido_-_infinitepayem-mancio-lima---ac.html)
- [Reclame Aqui — solicitação de documentos por e-mail cadastrado](https://www.reclameaqui.com.br/infinite-pay/cobranca-indevida-por-contestacao-de-compra_TOS94BN3AuEjEZSe/)

**Emissor (exemplo: Cartões Renner / Realize)**

- [Renner — telefones oficiais](https://atendimento.lojasrenner.com.br/s/article/Informa%C3%A7%C3%B5es-sobre-o-Cart%C3%A3o-Renner) · [Realize — Cartões Renner](https://www.realizesolucoesfinanceiras.com.br/cartoes-renner/) · [Realize — Ouvidoria](https://www.realizesolucoesfinanceiras.com.br/perguntas-frequentes/sr-page-meu-cartao)
- [Reclame Aqui — contestação tratada exclusivamente pela central](https://www.reclameaqui.com.br/lojas-renner/compra-nao-reconhecida-na-centauro-e-impossibilidade-de-cancelamento-pelo-aplicativo_c6nsLgUd3upmGGl3/)

**Regulação e defesa do consumidor**

- [Planalto — Decreto 11.034/2022](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/decreto/d11034.htm) · [MJ — novo decreto do SAC (2026)](https://www.gov.br/mj/pt-br/assuntos/noticias/novo-decreto-do-sac-amplia-protecao-ao-consumidor-e-estabelece-regras-de-atendimento)
- [Resolução BCB 96/2021, art. 12](https://legismap.com.br/leis-e-normas/resolucao-bcb-n-096-de-19-05-2021) · [ConJur — contraditório no encerramento unilateral](https://conjur.com.br/2026-set-09/contraditorio-no-encerramento-unilateral-de-contas-de-pagamento/)
- [Consumidor.gov.br](https://www.consumidor.gov.br) · [Banco Central — registrar reclamação](https://www.bcb.gov.br)

**Segurança pública (MG — adapte ao seu estado)**

- [PCMG — Delegacia Virtual](https://www.policiacivil.mg.gov.br/pagina/servico-delegacia-virtual) · [MG.gov — registro online](https://www.mg.gov.br/servico/solicitar-registro-de-ocorrencia-na-delegacia-virtual) · [limitação da natureza "Ameaça"](https://www.mg.gov.br/servico/solicitar-registro-de-ocorrencia-de-ameaca-violencia-domestica)

**Saúde / medicamentos**

- [Governo de Minas — Solicitar Medicamentos Especializados (CEAF)](https://www.mg.gov.br/servico/solicitar-medicamentos-especializados) · [SES-MG — Farmácia Digital](https://www.saude.mg.gov.br/farmaciadigital/)
- [DPMG — Saúde](https://defensoria.mg.def.br/areas-de-atuacao/saude/) · [DPMG — como conseguir medicamentos (ReMediar)](https://defensoria.mg.def.br/saber-direito/como-conseguir-medicamentos-pela-defensoria-publica/) · [DPMG — unidades](https://defensoria.mg.def.br/unidades/)
- [DPMG/TJMG — modelo de ação com tutela de urgência](https://www.tjmg.jus.br/lumis/portal/file/fileDownload.jsp?fileId=8ACC82D28F31C8B3018F39E864FA5527)
- [TJMG — requisitos dos Temas 6 e 1.234 do STF](https://www5.tjmg.jus.br/jurisprudencia/relatorioEspelhoAcordao.do?inteiroTeor=true&ano=25&ttriCodigo=1&codigoOrigem=0000&numero=003732&sequencial=002&sequencialAcordao=0)

---

## 15. Aviso final

Este guia foi montado a partir de fontes oficiais e respostas públicas de instituições, verificadas em **27/10/2026**. Regras internas de credenciadoras, prazos de bandeira e procedimentos de SAC mudam — **confirme sempre nos canais oficiais** (número no verso do cartão, app oficial, e-mail cadastrado).

Nada aqui substitui advogado. Em situação de ameaça, risco à integridade, exposição criminal ou necessidade de medida judicial, procure a **Defensoria Pública** ou um advogado de sua confiança. E, acima de tudo: **cuide primeiro da sua segurança e da criança**. O resto se resolve com protocolo, papel e paciência.
