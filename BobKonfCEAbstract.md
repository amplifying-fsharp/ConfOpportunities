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

Additional Speaker: Ronald

3-5 take home ideas:
  -creating a DSL with F# CEs is time well spend in regards to
    - correctness
    - productivity
    - communication with the business client

Additional material:
  - https://amplifying-fsharp.github.io/

Is it worth mentioning that there are two types of CEs, the standard effect ones and custom DSLs?


## Abstract (German)

Zugegeben: Eine gute Programmiersprache ist typischerweise viel mehr als nur die Summe ihrer einzelnen Features. Und dennoch lohnt sich manchmal der genauere Blick - so wie z.B. auf "Computation Expressions" (CEs) aus F#, mit denen ein Sprachelement existiert, das es schafft, Flexibilität und Einfachheit auf erstaunliche Art und Weise miteinander zu verbinden. Hört sich an wie ein nettes, theoretisches Spielchen? Das sind sie ganz sicher - und viel mehr noch: Ein praktisches und viel verwendetes Konzept in Libraries und im F#-Compiler selbst. Während ähnliche Ideen wie die aus Haskell bekannte "do"-Notation Sprachunterstützung für Monaden bietet, gehen CEs wesentlich weiter, indem sie es ermöglichen, idiomatische Sprachkonstrukte, aber auch Dinge wie die Art der Ausführung, Evaluierung oder der Aufbau von Bindungskontexten für bestimmte Berechnungen selbst zu definieren. Im Vergleich zu alternativen Konzepten wie z.B. Sprachmakros oder CompilerpluginsDabei entstehen dabei jedoch keine "Sprachen in der Sprache", durch die eine gemeinsame "Basis der Verständlichkeit" beteiligter Entwickler erodieren würde. Vielmehr bleibt der ursprüngliche, prinzipielle Charakter aller Sprachkonstrukte aus Sicht des Benutzers weitestgehend erhalten, so dass sich CEs nach Meinung der Autoren im Sweet-Spot zwischen Sprachflexibilität und möglichst schneller Übernahme (adoption) befinden.

Der Vortrag beleuchtet die theoretischen und praktischen Grundlagen von CEs, gibt einen kurzen Überblick bestehender Implementierungen (wie z.B. List-Comprehensions, async/await, SQL-like Queries, React-like UIs, "data-as-computation" DSLs) und skizziert eine Verwendungsmöglichkeit durch eine kurze Live-Coding-Session.

## Abstract (English)

Granted: A good programming language is typically much more than just the sum of its individual features. And yet, sometimes it's worth taking a closer look - such as at "Computation Expressions" (CEs) from F#, with which a language element exists that manages to combine flexibility and simplicity in an amazing way. Sound like a nice, theoretical little game? They certainly are - and much more: a practical and much-used concept in libraries and in the F# compiler itself. While similar ideas like the "do" notation known from Haskell provide language support for monads, CEs go much further by allowing to define idiomatic language constructs, but also things like the way of execution, evaluation or the construction of binding contexts for certain computations themselves. Compared with alternative concepts such as e.g. language macros or compiler plugins, it's not possible to develop "languages in the language" evolve, by which a "basis of common understanding" of the language itself would erode. Rather, the original, principled character of all language constructs from the user's point of view remains largely intact, so that CEs are, in the speaker's opinion, sit in the sweet spot between versatility and quick and easy adoption.

The talk highlights the theoretical and practical foundations of CEs, gives a brief overview of existing implementations (such as list comprehensions, async/await, SQL-like queries, React-like UIs, "data-as-computation" DSLs), and outlines a possible use through a short live coding session.
