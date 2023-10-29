- Introduction to CE in F#
- Compiler support/Desugaring/etc.
- Write your own CE
- Applications
- Theoretical Outlook for future extensions of the Language support
- Compare to other programming language features
- Pros/Cons (e.g. Performance)

References
https://tomasp.net/academic/papers/computation-zoo/computation-zoo.pdf

- In contrast to alternative approaches such as compiler plugins, macro- or template-based metaprogramming, computation expressions limit / restrict the possibilities in terms of AST-rewriting, parser tweaking or similar. This has the advantage that no new (sub)-language is created and has to be learned. Rather, well-known idiomatic language constructs are reinterpreted in the context of a computation, but without losing their original character.



The following is the discrete content to post to the CFC form:

Proposal title: Computational expressions in F#

Session type: Tutorial (90 minutes)

Language: English

Abstract:
With Computational Expressions (CE) F# offers a (nearly) unique language feature to create Domain Specific Languages (DSLs).
Furthermore, a CE allows to express ideas in a clear concise way. The use cases range from business-oriented DSLs to monad support.

In this tutorial we will show
- how to write a CE from scratch
- what the compiler is doing behind the scenes
- give real world examples of successful CEs in the industry
- convey how much fun the can be

We will give an outlook to possible future extensions to the current CE support of F# and how they could be used for type level programming.

Additional Speaker: Roland

3-5 take home ideas:
  -creating a DSL with F# CEs is time well spend in regards to
    - correctness
    - productivity
    - communication with the business client

Additional material:
  - https://amplifying-fsharp.github.io/
