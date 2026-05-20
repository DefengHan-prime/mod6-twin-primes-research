# mod6-twin-primes-research
基于模6算法的孪生素数猜想初等证明研究 / Twin Primes Research Based on Modulo 6 Algorithm

## 项目简介 / About This Project
本项目是基于**模6筛法**（`6n±1` 双链生成规则）对孪生素数猜想的一项**纯初等证明尝试**，完全不依赖解析数论、代数数论或未证明的猜想。核心创新在于提出了「阶乘荒漠」与「素数平方根判定」框架，证明了任意两级阶乘荒漠之间必存在素数，并推导出孪生素数对的联合判定式。

This project is a purely elementary attempt to prove the Twin Prime Conjecture based on the **modulo 6 sieve** (`6n±1` double chain generation rule), without relying on analytic number theory, algebraic number theory, or any unproven conjectures. The core innovation lies in the framework of "factorial deserts" and "prime square root criterion", proving that there exists at least one prime between any two consecutive factorial deserts, and deriving a joint congruence criterion for twin primes.

---

## 文件说明 / File Description
- `Elementary Proof of the Twin Prime Conjecture.tex`：论文LaTeX源码（英文）
- `Elementary Proof of the Twin Prime Conjecture.pdf`：编译后的论文PDF（英文）
- `孪生素数猜想的初等证明.tex`：论文LaTeX源码（中文）
- `孪生素数猜想的初等证明.pdf`：编译后的论文PDF（中文）
- `README.md`：项目说明文档
- `LICENSE`：开源许可（MIT）

---

## 核心结论 / Core Results
1.  **阶乘荒漠素数存在性**：任意两个连续阶乘荒漠之间，至少存在一个素数。
2.  **孪生素数判定**：基于威尔逊定理，给出了孪生素数对的联合同余判定式。
3.  **模6筛法的推广**：提出基于 `6n±1` 规则的双链素数生成模型，优化了素数筛选的效率。

---

## 开源许可 / License
本项目采用 [MIT License](LICENSE) 开源，欢迎交流与引用，但请遵守开源协议，注明出处。

This project is open-sourced under the [MIT License](LICENSE). Feel free to discuss and cite, but please comply with the license and give proper credit.
