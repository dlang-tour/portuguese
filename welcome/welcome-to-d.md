# Bem-vindo ao D

Bem-vindo ao tour interativo da *linguagem de programação D*.

{{#dmanmobile}}

Esta tour dá uma visão geral desta __poderosa__ e __expressiva__
linguagem que compila diretamente para __eficiente__ código __nativo__ de máquina.

{{/dmanmobile}}

### O que é D?

D é o culminar de _décadas de experiência implementando compiladores_
para diversas linguagens e tem um grande número de
[funcionalidades únicas](http://dlang.org/overview.html):

{{#dmandesktop}}

- Construção de _alto nível_ para uma modelagem poderosa
- _alta performance_, linguagem compilada
- tipagem estática
- interface direta para APIs do sistema operacional e hardware
- tempo de compilação incrivelmente rápido
- permite programação com memory-safe (SafeD)
- _manutenível_, código _fácil de entender_
- baixa curva de aprendizado (sintaxe semelhante a C, Java e outras linguagens)
- compatível com interface binário em C
- compatibilidade limitada com interface binário em C++
- multi-paradigma (imperativo, estruturado, orientado a objetos, genérica, programação funcional pura, e mesmo assembly)
- prevenção de erros embutido (contratos, testes uniários)

... e muitas outras [funcionalidades](http://dlang.org/overview.html).

{{/dmandesktop}}

### Sobre o tour

Cada seção vem com um código-fonte de exemplo que pode ser modificado e usado
para experimentar as funcionalides da linguagem D.
Clique no botão run (ou `Ctrl-enter`) para compilar e executa-ló.

### Contribuindo

Este tour tem o [código aberto](https://github.com/dlang-tour) e ficamos felizes
com pull requests para torná-lo melhor.

## {SourceCode}

```d
import std.stdio;

// Vamos começar!
void main()
{
    writeln("Hello World!");
}
```
