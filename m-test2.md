---
currentMenu: m-test2
layout: markdeep
---

<markdeep>

$$ \Lo(X, \wo) = \Le(X, \wo) + \int_\Omega \Li(X, \wi) ~ f_X(\wi, \wo) ~ | \n \cdot \wi | ~ d\wi $$

</markdeep>
<br></br>


You can also use LaTeX equation syntax directly to obtain numbered
equations:

<markdeep>

|Alice|Bob|
|:----------------------:|:----------------------:|
|\c||
|\begin{equation}AG1 := H_{1}(IdA)\end{equation}||
|\begin{equation}PaG_{1} := x\cdot AG_{1}\end{equation}||
|\begin{equation}IdA, PaG_{1} \longrightarrow\end{equation}||
| |\begin{equation}y,w \in \mathbb{Z}_{q}^{*}\end{equation}|

</markdeep>
<br></br>

<markdeep>

|Alice|Bob|
|:----------------------:|:----------------------:|
|AG1 := H_{1}(IdA)||
|$U=x{A}$||
|$ID_a$, $U~~ \rightarrow  $||
| |$\leftarrow y$|
|$V=-(x+y){((s-\alpha)A+\alpha A)} \rightarrow$||
| |$A=H(ID_a)$|
| |$g=e(V,Q).e(U+yA,sQ)$|
| |if $g \ne 1$, reject the connection|

</markdeep>
<br></br>

<markdeep>
\begin{equation}
\mbox{ALICE} & \mbox{BOB} \\
x \in \mathbb{Z}_{q}^{*} & \\
AG1 := H_{1}(IdA) & \\
PaG_{1} := x\cdot AG_{1} & \\
IdA, PaG_{1} \longrightarrow & \\
&  y,w \in \mathbb{Z}_{q}^{*}\\
&  AG_{1} := H_{1}(IdA)\\
&  BG_{2} := H_{2}(IdB)\\
& PbG_{2} := y\cdot BG_{2}\\
& PgG_{1} := w\cdot AG_{1}\\
& pia := H_{q}(PaG_{1}\| PbG_{2} \| PgG_{1}\|IdB)\\
& pib := H_{q}(PbG_{2}\|PaG_{1} \|PgG_{1}\| IdA)\\
& k:=e(pia\cdot AG_{1}+PaG_{1},(y+pib)\cdot s \cdot BG_{2})\\
& K:=H(k,w\cdot PaG_{1})\\
& \longleftarrow IdB, PgG_{1}, PbG_{2}\\
BG_{2} := H_{2}(IdB) & \\
pia := H_{q}(PaG_{1}\| PbG_{2} \| PgG_{1}\|IdB) & \\
pib := H_{q}(PbG_{2}\|PaG_{1} \|PgG_{1}\| IdA) & \\
k := e((x+pia)\cdot s \cdot AG_{1}, pib\cdot BG_{2} + PbG_{2}) & \\
K := H(k,x\cdot PgG_{1}) & \\
\end{equation}

</markdeep>
<br></br>

<markdeep>

      Code                    |   Symbol
------------------------------|------------
begin{equation}x \in \mathbb{Z}_{q}^{*}\end{equation}|begin{equation}x \in \mathbb{Z}_{q}^{*}\end{equation}  






<script>window.markdeepOptions = {mode: 'html'};</script>
<script src="markdeep.min.js"></script>
<script src="https://casual-effects.com/markdeep/latest/markdeep.min.js"></script>