# Instalar o D localmente

O compilador de referência da linguagem D chama-se DMD (Digital Mars D).
Existem outros compiladores, sendo os mais relevantes o
[LDC](https://github.com/ldc-developers/ldc) (compilador para D basedado na
[LLVM](http://llvm.org)) e o [GDC](https://gdcproject.org) (compilador para D
baseado no [GCC](https://gcc.gnu.org/)).
Informação mais detalhada está disponível na
[página da wiki sobre Compiladores](https://wiki.dlang.org/Compilers), mas para
pessoas novas à linguagem é recomendado instalar o DMD.

## Download e Instalação

A [página de downloads do D](https://dlang.org/download.html) tem informação
sobre as várias implementações da linguagem e contém links para _packages_
pré-compilados e específicos aos vários sistemas operativos prontos para fazer
o dowload e instalar.

Como alternativa aos _packages_ específicos ao sistema operativo, também está
disponível um [_script_ de instalação](https://dlang.org/install.html) para
qualquer sistema baseado em Posix (Linux, FreeBSD, MacOS) que pode instalar
várias implementações diferentes (incluindo várias versões) localmente sem
ser necessário permissões de administrador.
Informação mais detalhada encontra-se na
[documentação do _script_ de instalação](https://dlang.org/install.html).

## Configuração do editor

Para usar o D não é necessário nenhum IDE muito sofisticado, o que é muito raro.
Contudo, programar em D é melhor quando usamos o nosso editor favorito. Existem
_plugins_ que adicionam suporte para D pelo menos para os seguintes editores:

- [Atom](https://github.com/Pure-D/atomize-d)
- [Eclipse](http://ddt-ide.github.io)
- [Emacs](https://github.com/Emacs-D-Mode-Maintainers/Emacs-D-Mode)
- [IntelliJ](https://github.com/intellij-dlanguage/intellij-dlanguage)
- [Sublime Text](https://github.com/yazd/DKit)
- [Vim](https://wiki.dlang.org/D_in_Vim)
- [VS Code](https://marketplace.visualstudio.com/items/webfreak.code-d)
- [__Visual Studio__](http://rainers.github.io/visuald/visuald/StartPage.html)

Também existem _IDEs_ dedicados ao D:

- [Coedit](https://github.com/BBasile/Coedit)
- [Dlang IDE](https://github.com/buggins/dlangide)

A wiki do D tem uma descrição mais completa dos
[editores](https://wiki.dlang.org/Editors) e
[_IDEs_](https://wiki.dlang.org/IDEs) disponiveis.

