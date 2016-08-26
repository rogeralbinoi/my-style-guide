# HTML

## Regras gerais

**Doctype**

Recomendado:

    <!doctype html>

Não recomendado:

    <!DOCTYPE html>

**Fechar todas as tags**

Não recomendado:

    <ul>
      <li> Foo
      <li> Bar
    </ul>

Recomendado:

    <ul>
      <li>Foo</li>
      <li>Bar</li>
    </li>

**Evitar uso de caminho absoluto para referências de arquivos**

Não recomendado:

    <img src="/images/bar.png" alt="Foo Bar">
Recomendado:

    <img src="../images/bar.png" alt="Foo Bar">

**Omitir protocolo para recursos externos**

Não recomendado:

    <script src="https://foo.com/bar.js"></script>

Recomendado:

    <script src="//foo.com/bar.js"></script>

**Não esquecer do atributo lang na tag html**

Não recomendado:

        <html>

Recomendado:

        <html lang="pt">

**Omitir tag head**

    <html>
      <title>Foo bar</title>
      <body>
        <h1>Foo bar</h1>
      </body>
    </html>

## Formatação

**Indentação com dois espaços**

Não usar tabs ou misturar tabs com espaços.

    <section>
      <h1>Foo</h1>
    </section>
**Usar sempre lowercase**

Todo o código html deve ser em lowercase, apenas valores de propriedades podem ser capitalizadas quando necessário.

Não recomendado:

    <UL>
      <Li>foo</Li>
      <Li>bar</Li>
    </UL>

Recomendado:

    <ul>
      <li>foo</li>
      <li>bar</li>
    </ul>

Recomendado:

    <img src="../foo/bar.png" alt="Foo Bar">

**Remover espaços em branco**

Não recomendado:

    <p>Lorem ipsum. </p>

Recomendado:

    <p>Lorem ipsum.</p>

**Validar HTML pelo [w3c validator](https://validator.w3.org/)**
