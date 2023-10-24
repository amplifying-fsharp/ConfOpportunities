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
