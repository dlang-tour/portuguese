# Bem-vindo ao D

Bem-vindo ao tour interativo da *linguagem de programação D*.

{{#dmanmobile}}

Esta tour dá uma visão geral desta __poderosa__ e __expressiva__
linguagem que compila diretamente para código de máquina __nativo__
__eficiente__.

{{/dmanmobile}}

### O que é o D?

D é o culminar de _décadas de experiência em implementação de compiladores_
para múltiplas linguagens. Esta linguagem tem um grande número de
[características únicas](http://dlang.org/overview.html):

{{#dmandesktop}}

- construção em _high level_ que proporciona um alto poder de modelação
- _alta performance_, linguagem compilada
- suporta definições estáticas
- interface direta com APIs do sistema operativo e hardware
- tempo de compilação incrivelmente rápido
- permite programação em modo memory-safe (SafeD)
- _manutenção fácil_, código _fácil de entender_
- baixa curva de aprendizagem (sintaxe semelhante a C, Java e outras linguagens)
- compatível com a interface binária do C
- compatibilidade limitada com a interface binária do C++
- multi-paradigma (imperativa, estruturada, orientada a objetos, genérica, programação funcional pura, e mesmo assembly)
- deteção de error automática (contratos, _unittests_)

... e muitas outras [funcionalidades](http://dlang.org/overview.html).

{{/dmandesktop}}

### Sobre o tour

Cada secção inclui um código exemplo que pode ser modificado e usado para
experimentar as características da linguagem D.
Para compilar o código e executá-lo, basta clicar no botão "Run"
(ou `Ctrl-enter`).

### Contribuições

O tour da linguagem D é [_open source_](https://github.com/dlang-tour).
Para contribuir basta abrir um _pull request_
com pull requests para torná-lo melhor.

## {SourceCode}

```d
import std.stdio;

void main()
{
    // Vamos começar!
    writeln("Hello World!");

    // Um exemplo para programadores exprientes:
    // Dadas três arrays, sem alocar memória nova,
    // ordene todas as arrays por ordem numérica.
    int[] arr1 = [4, 9, 7];
    int[] arr2 = [5, 2, 1, 10];
    int[] arr3 = [6, 8, 3];
    sort(chain(arr1, arr2, arr3));
    writefln("%s\n%s\n%s\n", arr1, arr2, arr3);
    // Para aprender mais sobre isto, veja a
    // página "Algoritmos de Range" em "Gemas"
}
```
