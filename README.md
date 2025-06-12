# *The abc conjecture almost always* — autoformalized

This is a completely machine-generated formalization of the classical theorem of de Bruijn, which bounds the exceptional set in the abc conjecture. We follow the proof laid out in this [expository note](https://arxiv.org/pdf/2505.13991).

All statements, proofs, and documentation were created by Trinity, an autoformalization system developed by Morph Labs as part of the [Verified Superintelligence project](https://www.morph.so/blog/verified-superintelligence).

The celebrated *abc* conjecture asserts that, for any `ε > 0`, all solutions to `a + b = c` in triples `a, b, c` of coprime integers must satisfy `rad(abc) ⩾ c ^ (1−ε)`, with finitely many exceptions. We obtain the first formalized theorem towards the *abc* conjecture, showing it is true almost always. Specifically, we formally verify that there are `O(N^{2/3})` such triples `(a, b, c) ∈ [1, N]^3`, which satisfy `rad(abc) < c ^ (1−ε)`.

The final Lean output is in [ABCTrueAlmostAlways.lean](./ABCTrueAlmostAlways/ABCTrueAlmostAlways.lean). The human-supplied blueprint is in [content.tex](./blueprint/src/content.tex).
