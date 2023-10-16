# Senha

Princípio fundamental: **Nunca use senhas iguais ou semelhantes**

Por dois motivos:
- Se alguém tiver seu e-mail e senha do site 1, certamente tentará usá-los no site 2 - e isso não diz respeito a você pessoalmente, o mercado de contas hackeadas é muito grande, e isso é uma mercadoria.
- Se os dados de suas contas juntamente com as senhas vazarem em [vazamentos](./breaches.md), será possível comparar até mesmo e-mails e números de telefone completamente diferentes ([bom exemplo](https://meduza.io/feature/2022/02/07/eto-pohozhe-na-krik-dushi-no-ya-ne-znayu-o-chem-on-krichit)).

Mas como lembrar de muitas senhas? E onde obtê-las?
Recomendo que você não trate todas as senhas como dados que devem estar sempre em sua cabeça. Economize espaço na sua memória.

A maneira mais ótima é criar uma frase de senha suficientemente longa para a loja de senhas (ou para a conta na qual
seu navegador está vinculado, onde todas as senhas são armazenadas).

*Esta seção será atualizada*

## Como criar senhas fortes

As diretrizes padrão para o uso de 8 caracteres que incluem caracteres especiais, letras, números não funcionam! Afinal, `P@ssw0rd` também atende a esses requisitos, e esta não é a melhor senha, então vamos analisar os métodos para criar senhas fortes.

### Três palavras aleatórias
Existe um método simples, mas eficaz, para criar senhas - o método de 3 palavras aleatórias.

O que é esse método? Quando nos registramos em uma nova conta, simplesmente inventamos 3 palavras aleatórias e as usamos como nossa senha, por exemplo: `NETWORKINGHYGIENEDEVELOPMENT`
concorda, é muito mais fácil de lembrar do que:
`asndjBDHJBSDhjSBADHJadbzhjF`, e será bastante difícil resolver isso com uma simples pesquisa no dicionário.

Essas senhas podem ser fortalecidas usando [LEET](https://ru.wikipedia.org/wiki/Leet), substituindo *algumas* letras por números, ou seja, nossa senha terá a seguinte forma:
`N3TW0RKHY6I3N3D3V3L0PM3NT`
Assim, nossa senha se torna mais estável, e sua complexidade para memorização não aumenta muito, e se você já estava familiarizado com [LEET](https://ru.wikipedia.org/wiki/Leet), antes disso, será ainda mais fácil.

Para maior durabilidade, você pode separar as palavras usando diferentes caracteres especiais, como: `-`, `~`, `=`.

### Palavras em russo com layout em inglês
Outro método simples, mas eficaz, é o uso de palavras aleatórias em russo com layout em inglês.

Basta pegar palavras aleatórias em russo e escrevê-las no layout em inglês, por exemplo, de `ехалгрекачерезреку` podemos obter o seguinte `t[fkuhtrfxthtphtre`.

Isso parece interessante e bastante estável, mas você pode adicionar símbolos/números no final, por exemplo:
`t[fkuhtrfxthtphtre123!`
`t[fkuhtrfxthtphtre34345!`

*Esta seção será atualizada*

## Gerenciadores de Senhas
Isso é algo que todos devem usar! Lembremos o princípio principal da primeira linha e a pergunta vem imediatamente à mente - "Bem, e agora, lembrar de 100 senhas!?!?". Não, você não precisa lembrar de 100 senhas, é necessária apenas uma, esta é a senha do gerenciador de senhas.

O gerenciador de senhas permitirá que você gere senhas fortes e as armazene em um único, e, o mais importante, em um lugar seguro.

Uma visão geral dos gerenciadores de senhas populares pode ser encontrada neste artigo - [Visão geral dos gerenciadores de senhas](https://habr.com/ru/company/cloud4y/blog/581916/)

A recomendação pessoal dos compiladores do manual será o serviço [Bitwarden](https://bitwarden.com/). Para uso pessoal, será suficiente com sua cabeça, a versão gratuita inclui o armazenamento de um número ilimitado de senhas, uso em um número ilimitado de dispositivos e todas as funções básicas dos gerenciadores de senhas. Além de armazenar senhas, você também pode armazenar os números de seus cartões bancários e notas. O gerador de senhas permite que você gere uma senha forte e a verifique em busca de vazamentos, o que é, sem dúvida, uma das "Características Matadoras".

### LessPass

E se for difícil para você armazenar senhas e sincronizá-las entre diferentes dispositivos? Os gerenciadores de senhas vêm ao resgate sem a necessidade de armazenar nada!

LessPass não é o único programa desse tipo, mas um dos mais famosos. Seu conceito é que a geração de senhas descartáveis ocorre na hora
usando uma função, cujo resultado é sempre o mesmo, desde que os parâmetros sejam os mesmos.

O programa precisa ser informado:
- senha mestra
- login no site
- endereço do site

Depois disso, ele gerará sua senha sem enviar nenhum dado ou salvar algo em qualquer lugar.
A qualquer momento, em qualquer dispositivo, você pode executar este programa - e obter sua senha para um site específico.

<img width="499" alt="imagem" src="https://user-images.githubusercontent.com/31013580/194948775-cfe3987f-acde-456a-a78b-5281dd06171e.png">

<img width="499" alt="imagem" src="https://user-images.githubusercontent.com/31013580/194949724-dc26b60c-4607-40cf-a101-ead867dea009.png">

## Materiais úteis e links para fontes

- [Free LessPass password Manager runs on pure function](https://www.pvsm.ru/open-source/207324)
---

[⬅️ Anterior](./7-endereco-fisico.md) | [⏫ Tabela de conteúdos](../README.md) | [Próximo ➡️](./photo.md)
