### 1. 一句话解释zkp

> 来自WikiPedia 的解释
> ZKP(  **zero-knowledge proof**  ) is a method by which one party (the prover) can prove to another party (the verifier) that a given statement is true while the prover avoids conveying any additional information apart from the fact that the statement is indeed true.

一句话来解释:

我是一个prover(证明人)，我有一个秘密，你是一个verifier(验证人)，目前只有我知道这个秘密，我能向你证明"我知道这个秘密"，而不用向任何人透露这个秘密。

* 我有某个wallet的private key,无需向你展示这个private key而使你信服我有这个wallet 的privatekey
* 我有[四色地图](https://en.wikipedia.org/wiki/Four_color_theorem) 的解决方案，无需向你展示最终结果，而让你信服我能做出一个四色方案的解决方式(地图相邻区域无相同颜色)

<img src="image/01-01.png" style="zoom:150%;" />
