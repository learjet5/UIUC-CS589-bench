# UIUC-CS589-bench
Collect and construct AI-powered open-source projects and their vulns/bugs for CS598 course project.



主要关注同时符合以下条件的漏洞挖掘/分析对象：

- 以C/C++代码为主。
- 受memory bugs/vulnerabilities影响（此要地，我们也研究其他漏洞类型）。
- AI生态上下游的软件，包括但不限于AI training/inference frameworks、AI libraries、AI compilers、domain-specific AI-powered software（embodied AI frameworks）。
- 具有一定的影响力（比如大厂主推的或学术界认可度较高的project），不能太小众。



整体的流程大致是：

1. 收集符合条件的open-source projects对象。
2. 针对每一个对象，收集CVE、bug issue等漏洞对象（优先有CVE编号的内存类漏洞）。
3. 针对每个漏洞对象进行标准化的format和validation。



预期：仓库里最好收集5～8个projects的相关的30～50个vulnerabilities/bugs。
