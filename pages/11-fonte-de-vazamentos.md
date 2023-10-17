# Determinando a fonte do vazamento

## Encontrando-se em vazamentos

Existem muitos sites que permitem que você se encontre por telefone, e-mail ou até mesmo nome completo em vazamentos de informações e bancos de dados mesclados. Eles devem ser usados com cautela, porque qualquer pesquisa online pode ter um propósito adicional de enriquecer dados. Por exemplo, **coletar um endereço IP**, vincular várias pesquisas de uma pessoa para **coletar informações sobre seu ambiente**.

Portanto, a opção preferida é sempre *pesquisa independente em arquivos de vazamento*.

Mas pode ser difícil: você precisa encontrar um arquivo (ou muitos arquivos se precisar de uma pesquisa exaustiva), entender sua estrutura, realizar uma pesquisa eficaz.

Se você escolheu o caminho mais simples, então eu recomendo usar tais recursos em ordem decrescente de riscos:

#### Sites seguros conhecidos

O mais famoso: Have I Been Pwned, apoiado por um conhecido
guarda de segurança e dando garantias de privacidade.

Outros:
- https://monitor.firefox.com/

#### Alternativas comerciais

Eles costumam dar acesso shareware, você pode encontrar diferentes sites pelas palavras-chave check, leak:

- https://leakcheck.io/
- https://checkleaked.cc/

#### Bots no Telegram

- https://t.me/PhoneLeaks_bot - busca por fontes de vazamento

A maioria dos bots não indica a fonte de onde as informações são obtidas. Lista de alguns recursos:
Planilha Google.


#### Notificações

Alguns dos sites listados acima também podem notificá-lo por e-mail se houver um novo vazamento com seus dados. Eu recomendo fortemente o uso de tal serviço se você levar uma vida virtual ativa.

## Usando aliases/endereços de e-mail falsos

Gmail e outros serviços de correio mais comuns suportam caracteres especiais para criar aliases para sua caixa de correio. O correio enviado para um alias virá para o seu endereço de e-mail principal, mas você verá claramente de onde veio no campo Destinatário.

Por exemplo, `soxoj@protonmail.com` é equivalente a `soxoj+gitlab@protonmail.com`:

<img width="311" alt="Aliases de Email" src="https://user-images.githubusercontent.com/31013580/193665517-c06dd5d4-1c6b-468d-8a16-34db0e0689a5.png">

É **estritamente recomendado** usar este recurso em todos os sites onde ele é suportado.
Assim:
1. Em caso de vazamentos ou spam, você saberá exatamente de onde veio seu correio.
2. Em caso de coleta direcionada de informações sobre seu e-mail, as informações de vários sites serão menos prováveis de serem mescladas em um único dossiê.


Naturalmente, a colheita de vazamentos costuma usar normalização de correio: removendo partes semelhantes de aliases e limpando o excesso. Portanto, só podemos falar sobre mitigação de risco, não proteção cem por cento.

Deve-se fazer uma menção especial ao fornecimento de endereços postais **para envio de recibos** para compras online.

```
De acordo com o parágrafo 2 do Art. 1.2 da lei № 54-FZ, o recibo deve ser enviado eletronicamente se o comprador tiver fornecido seu número de assinante ou um endereço de e-mail antes do pagamento.
```

Isso é usado por grandes bots do Telegram como o Eye of God: eles armazenam todas as suas informações de pagamento, **conectadas ao e-mail especificado**, para as informações que o bot fornece.

Portanto, se você não estiver interessado no recibo, então forneça um endereço postal conscientemente errado apontando para a fonte do vazamento, por exemplo, eyeofgod@receipt.com. Ou use os aliases mencionados acima, revelando explicitamente onde a caixa de entrada foi listada.

## Usando diferentes nomes para rastreamento

Então, se você não estiver interessado no recibo, forneça um endereço de correio conscientemente errado apontando para a fonte do vazamento, por exemplo, eyeofgod@receipt.com. Ou use os aliases mencionados acima, expondo explicitamente onde a conta de e-mail foi listada.

Os sites têm abordagens diferentes para a precisão dos nomes e sobrenomes das contas. Alguns exigem que coincidam com os dados do passaporte (por exemplo, no VK), alguns só os verificam contra documentos em caso de transações financeiras, e a maioria não valida nada.

Você pode usar os truques listados abaixo dependendo da rigidez das regras do serviço (ToS, Termos de Serviço). Mas antes de usá-los, eu recomendo fortemente que você estude quais sanções são possíveis se você especificar um nome inválido e avalie esses riscos para si mesmo.

#### Use nomes/sobrenomes que sejam consonantes ou comecem com as mesmas letras do site/empresa.
Dessa forma, se esse nome for vazado em conjunto com um número ou correio, você saberá de onde veio a informação:

- McDonald's: _Maxim_
- VKontakte: _Vova_
- Odnoklassniki: _Oleg_

#### Use variações do nome em cirílico ou latim
Primeiro de tudo, isso se aplica à forma completa/abreviada do nome:

- Alexander
- Sasha
- Sanya
- Shura

Mas por causa das diferenças de idioma, um nome pode ter várias formas "latinas".
Até mesmo os bancos costumam dar a opção de escolher a transliteração correta dos nomes.
Assim, o nome "Anatoly" pode ser expresso como:

- Anatoly
- Anatolii
- Anatoliy

---

<details>
  <summary>🥷 Nível avançado</summary>
  </br>
### Usando BitWarden para gerar aliases de e-mail

O gerenciador de senhas BitWarden permite que você gere aliases de e-mail aleatórios com um plus, bem como endereços de caixa de correio catch-all e até mesmo caixas de correio para encaminhamento.

Leia mais sobre esses recursos na seção "🥷 Nível avançado" da seção Caixa de Correio.

!imagem

</details>

[⬅️ Anterior](./10-vazamentos-dados.md) | [⏫ Tabela de conteúdos](../README.md) | [Próximo ➡️](12-tokens-canary.md)