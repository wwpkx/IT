`MarkDown`中公式公式的语法与`LaTeX`类似
# 公式语法
- **行内公式**:用 `$`包裹公式
- **独立公式**:用`$$`包裹公式
- 上标表示：`^`
- 下标表示：`_`
- 加边框：`\boxed`用于给公式
- **根号**：通用表达方式为`$\sqrt[a]{b}$`→ $\sqrt[a]{b}$
- **分式**
	- `$\frac {a}{b}$` -->  $\frac {a}{b}$
	- `$a+1 \over b+1$` --> $a+1 \over b+1$
- **大括号:** $\{a+b\}$ 或者 $\lbrace a+b \rbrace$
- **向上取整**：$\lceil x \rceil$
- **向下取整：**$\lfloor x \rfloor$
- 换行
	- \newline
	- \\
- 空格
        - \,  插入一个短的空格。
        - \:  插入一个中等长度的空格。
        - \quad  插入一个较宽的空格。
        - \qquad  插入一个更宽的空格，通常是\quad的两倍宽度。
# 特殊转义字符
`# $ & ~ _ ^ \ { } %`

# 希腊字母表示
| 名称      | 大写          | TeX             | 小写               | TeX        |
|---------|-------------|-----------------|------------------|------------|
| alpha   | A AA        | $A$             | α \alphaα        | $\alpha$   |
| beta    | B BB        | $B$             | b e t a betabeta | $\beta$    |
| gamma   | Γ \GammaΓ   | $\Gamma$        | γ \gammaγ        | $\gamma$   |
| delta   | Δ \DeltaΔ   | $\Delta$        | δ \deltaδ        | $\delta$   |
| epsilon | E \EpsilonE | 4\Epsilon$或者$E$ | ϵ \epsilonϵ      | $\epsilon$ |
| zeta    | Z \ZetaZ    | $\Zeta$或者$Z$    | ζ \zetaζ         | $\zeta$    |
| eta     | H \EtaH     | $H$或者$\Eta$     | η \etaη          | $\eta$     |
| theta   | Θ \ThetaΘ   | $\Theta$        | θ \thetaθ        | $\theta$   |
| iota    | I \IotaI    | $\Iota$或者$I$    | ι \iotaι         | $\iota$    |
| kappa   | K \KappaK   | \Kappa或者$K$     | κ \kappaκ        | $\kappa$   |
| lambda  | I II        | $\Lambda$       | λ \lambdaλ       | $\lambda$  |
| mu      | M \MuM      | $\Mu$或者$M$      | μ \muμ           | $\mu$      |
| nu      | N \NuN      | $\Nu$或者$N$      | ν \nuν           | $\nu$      |
| xi      | Ξ \XiΞ      | $\Xi$           | ξ \xiξ           | $\xi$      |
| omicron | O \OmicronO | $\Omicron$或者$O$ | ο \omicronο      | $omicron$  |
| pi      | Π \PiΠ      | $\Pi$           | π \piπ           | $pi$       |
| rho     | P \RhoP     | $\Rho$或者$P$     | ρ \rhoρ          | $\rho$     |
| sigma   | Σ \SigmaΣ   | $\Sigma$        | σ \sigmaσ        | $\sigma$   |
| tau     | T \TauT     | $T$或者$\Tau$     | τ \tauτ          | $\tau$     |
| upsilon | Υ \UpsilonΥ | $\Upsilon$      | υ \upsilonυ      | $\upsilon$ |
| phi     | Φ \PhiΦ     | $\Phi$          | ϕ \phiϕ          | $\phi$     |
| chi     | X \ChiX     | $\Chi$或者$X$     | χ \chiχ          | $\chi$     |
| psi     | Ψ \PsiΨ     | $\Psi$          | ψ \psiψ          | $\psi$     |
| omega   | Ω \OmegaΩ   | $\Omega$        | ω \omegaω        | $\Omega$   |

# 大型数学运算符

|    运算符    |     TeX      |    运算符     |      TeX      |
| :-------: | :----------: | :--------: | :-----------: |
|   \sum    |   ∑ \sum∑    |    \int    |    ∫ \int∫    |
|   \prod   |   ∏ \prod∏   |   \iint    |   ∬ \iint∬    |
|  \coprod  |  ∐ \coprod∐  |   \iiint   |   ∭ \iiint∭   |
|  \bigvee  | ⋀ \bigwedge⋀ | \bigwedge  | ⋀ \bigwedge⋀  |
| \bigoplus | ⨁ \bigoplus⨁ | \bigotimes | ⨂ \bigotimes⨂ |
|  \bigcup  |  ⋃ \bigcup⋃  |    \lim    | lim ⁡ \limlim |
# 三角函数

|算式|Tex|备注|
|:-:|:-:|:-:|
|sin ⁡ \sinsin|`$\sin$`|正弦|
|cos ⁡ \coscos|`$\cos$`|余弦|
|tan ⁡ \tantan|`$\tan$`|正切|
|cot ⁡ \cotcot|`$\cot$`|余切|
|sec ⁡ \secsec|`$\sec$`|反正弦|
|csc ⁡ \csccsc|`$\csc$`|反余弦|

# 对数函数

|      算式      |     Tex      |         备注         |
| :----------: | :----------: | :----------------: |
| ln ⁡ \ln{}ln |  `$\ln{}$`   | e为底的对数，`{}`中填对数内容  |
| lg ⁡ \lg{}lg |  `$\lg{}$`   | 10为底的对数，`{}`中填对数内容 |
|  $\log_a^b$  | `$\log_a^b$` |                    |
# 例子

$A$
$\alpha$
## 独立公式
$$ \boxed{E=mc^2} $$

等号对齐
$$
\begin{align}
a&=1+2+3+4+5 \\
&=6+9
\end{align}
$$



