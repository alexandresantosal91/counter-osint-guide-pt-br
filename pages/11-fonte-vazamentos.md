<h1>Determinação da Fonte de Vazamentos</h1>

<h2>Encontrando-se em Vazamentos</h2>

<p align="justify">Existem muitos sites que permitem que você se encontre por telefone, e-mail ou até mesmo pelo nome completo em vazamentos de informações e bases de dados mescladas. Eles devem ser usados com cautela, pois qualquer pesquisa on-line pode ter um propósito adicional de enriquecer dados. Por exemplo, <strong>coletar um endereço IP</strong>, vinculando várias pesquisas de uma pessoa para <strong>coletar informações sobre seu ambiente</strong>.</p>

<p align="justify">Portanto, a opção preferida é sempre a <em>busca independente em arquivos de vazamento</em>.</p>

<p align="justify">Mas pode ser difícil: você precisa encontrar um arquivo (ou muitos arquivos, se precisar de uma busca exaustiva), entender sua estrutura e realizar uma busca eficaz.</p>

<p align="justify">Se você optou pelo caminho mais simples, recomendo usar esses recursos em ordem decrescente de riscos:</p>

<h3>Sites bem conhecidos e seguros</h3>

<p align="justify">Os mais famosos: <a href="https://haveibeenpwned.com/">Have I Been Pwned</a>, apoiado por uma empresa de segurança conhecida e garantindo privacidade.</p>

<p>Outros:</p>

<ul>
    <li><a href="https://monitor.firefox.com/">https://monitor.firefox.com/</a></li>
</ul>


<h3>Alternativas comerciais</h3>

<p align="justify">Eles costumam fornecer acesso shareware, você pode encontrar diferentes sites pelas palavras-chave "verificar" e "vazamento":</p>

<ul>
    <li><a href="https://leakcheck.io/">https://leakcheck.io/</a></li>
    <li><a href="https://checkleaked.cc/">https://checkleaked.cc/</a></li>
</ul>

<h3>Bots no Telegram</h3>

<p align="justify"><a href="https://t.me/PhoneLeaks_bot">https://t.me/PhoneLeaks_bot</a> - busca por fontes de vazamento.</p>

<p align="justify">A maioria dos bots não indica a fonte de onde as informações são obtidas. Lista de alguns recursos: <a href="https://docs.google.com/spreadsheets/d/1XerMPGwaDz1FG1gBumBp6jzOgSqhWcQWgZmhxoT60WA/edit#gid=0">Google Spreadsheet</a>.</p>

<h3>Notificações</h3>

<p align="justify">Alguns dos sites listados acima também podem notificá-lo por e-mail se houver um novo vazamento com seus dados. Recomendo muito usar esse serviço se você leva uma vida virtual ativa.</p>

<h2>Usar alias/endereços de e-mail falsos</h2>

<p align="justify">O Gmail e outros serviços de e-mail mais comuns suportam caracteres especiais para criar alias para sua caixa de correio. O e-mail enviado a um alias chegará ao seu endereço de e-mail principal, mas você verá claramente de onde ele veio no campo Destinatário.</p>

<p>Por exemplo, `soxoj@protonmail.com` é equivalente a `soxoj+gitlab@protonmail.com`:</p>

<p align="center"><img width="800"  src="https://user-images.githubusercontent.com/31013580/193665517-c06dd5d4-1c6b-468d-8a16-34db0e0689a5.png" alt="Email aliases">

<p>É **estritamente recomendado** usar esse recurso em todos os sites onde ele é suportado.</p>

<p>Assim:</p>

<ol align="justify">
    <li>No caso de vazamentos ou spam, você saberá exatamente de onde veio seu e-mail.</li>
    <li>No caso de uma coleta direcionada de informações sobre seu e-mail, as informações de vários sites terão menos probabilidade de serem mescladas em um único dossiê.</li>
</ol>

<p align="justify">Naturalmente, a coleta de vazamentos frequentemente usa a normalização de e-mails: remoção de partes semelhantes de alias e limpeza do excesso. Portanto, só podemos falar sobre mitigação de riscos, não uma proteção de cem por cento.</p>

<p align="justify">Deve ser feita uma menção especial sobre o fornecimento de endereços de e-mail **para o envio de recibos** para compras on-line.</p>

<blockquote align="justify">
    De acordo com o parágrafo 2 do art. 1.2 da lei nº 54-FZ, o recibo deve ser enviado eletronicamente se o comprador tiver fornecido seu número de assinante ou um endereço de e-mail antes do pagamento.
</blockquote>

<p align="justify">Isso é usado por grandes bots do Telegram como o Eye of God: eles armazenam todas as informações de pagamento, **conectadas ao e-mail especificado**, às informações que o bot fornece.</p>

<p align="justify">Portanto, se você não estiver interessado no recibo, forneça um endereço de e-mail deliberadamente incorreto apontando para a fonte do vazamento, por exemplo, eyeofgod@receipt.com. Ou use os aliases mencionados, revelando explicitamente onde a caixa de entrada foi listada.</p>

<h2>Usar nomes diferentes para rastreamento</h2>

<p align="justify">Portanto, se você não estiver interessado no recibo, forneça um endereço de e-mail deliberadamente incorreto apontando para a fonte do vazamento, por exemplo, eyeofgod@receipt.com. Ou use os aliases mencionados, revelando explicitamente onde a caixa de entrada foi listada.</p>

<p align="justify">Os sites têm abordagens diferentes para a precisão dos nomes e sobrenomes das contas. Alguns exigem que eles coincidam com os dados do passaporte (por exemplo, no VK), alguns os verificam apenas em documentos em caso de transações financeiras, e a maioria não os valida de forma alguma.</p>

<p align="justify">Você pode usar os truques listados abaixo, dependendo da rigidez das regras do serviço (ToS, Termos de Serviço). Mas antes de usá-los, aconselho fortemente a estudar quais sanções são possíveis se você especificar um nome inválido e avaliar esses riscos por conta própria.</p>

<h3>Usar nomes/sobrenomes que sejam consonantes ou comecem com as mesmas letras do site/empresa.</h3>

<p align="justify">Dessa forma, se esse nome for vazado em conjunto com um número ou e-mail, você saberá de onde veio a informação:</p>

<ul>
    <li>McDonald's: _Maxim_</li>
    <li>VKontakte: _Vova_</li>
    <li>Odnoklassniki: _Oleg_</li>
</ul>

<h3>Usar variações do nome em cirílico ou latino</h3>

<p>Isso se aplica principalmente à forma completa/abreviada do nome:</p>

<ul>
    <li>Alexander</li>
    <li>Sasha</li>
    <li>Sanya</li>
    <li>Shura</li>
</ul>

<p align="justify">Mas devido a diferenças de idioma, um nome pode ter várias formas "latinas". Até mesmo os bancos frequentemente oferecem a opção de escolher a transliteração correta dos nomes. Portanto, o nome "Anatoly" pode ser expresso como:</p>

<ul>
    <li>Anatoly</li>
    <li>Anatolii</li>
    <li>Anatoliy</li>
</ul>

<hr>

<details align="justify">
    <summary>🥷 Nível Avançado</summary>
    <p>Usando o gerenciador de senhas BitWarden para gerar alias de e-mail</p>
    <p>O gerenciador de senhas BitWarden permite que você gere alias de e-mail aleatórios com um sinal de adição, bem como endereços de caixa de correio catch-all e até caixas de correio para encaminhamento.</p>
    <p>Leia mais sobre esses recursos na seção "🥷 Nível Avançado" da seção de <a href="email.md">Caixa de Correio</a>.</p>
    <img src="../img/bitwarden_en.png" alt="imagem">
</details>

<hr>

[⬅️ Anterior](./10-vazamentos-dados.md) | [⏫ Tabela de conteúdos](../README.md) | [Próximo ➡️](./12-tokens-canary.md)