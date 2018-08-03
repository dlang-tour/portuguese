# Executar um programa escrito em D localmente

A linguagem D tem um compilador, `dmd`, uma ferramenta para executar código D
em forma de _script_, `rdmd`, e um _package manager_, `dub`.

### DMD Compiler
### O compilador DMD

O _DMD_ compila ficheiros D e cria um executável.
No terminal, pode ser invocado com apenas o nome do ficheiro:

    dmd hello.d

Existem várias opções que permitem mudar o comportamento do _DMD_.
A descrição das _flags_ disponíveis pode ser encontrada na
[documentação online](https://dlang.org/dmd.html#switches) ou executando
`dmd --help`.

### Compilação em tempo real usando o `rdmd`

A ferramenta `rdmd`, distribuida junto com o compilador DMD, vai compilar todas
as dependencias e vai executar automáticamente a aplicação:

    rdmd hello.d

Em sistemas UNIX, a seguinte _shebang_ pode ser colocada `#!/usr/bin/rdmd`
na primeira linha do ficheiro para permitir uma utilização em forma de script.

A descrição das _flags_ disponíveis pode ser encontrada na
[documentação online](https://dlang.org/rdmd.html) ou executando `rdmd --help`.

### O _package manager_ `dub`

O _package manager_ padrão da linguagem D é o [`dub`](https://code.dlang.org).
Quando o `dub` é instalado localmente, um novo projeto `hello` pode ser criado
usando o seguinte comando num terminal:

    dub init hello

Executar `dub` dentro desta pasta vai fazer o download de todas as
dependências, compilar a aplicação e logo depois executá-la.
`dub build` irá compilar o projeto.

A descrição dos comandos disponíveis pode ser encontrada na
[documentação online](https://code.dlang.org/docs/commandline) ou executando
`dub help`.

Todos os _packages_ disponíveis podem ser encontrados usando a
[interface web](https://code.dlang.org) do dub.

