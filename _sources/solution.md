# Solution

---

**1.** The accumulation of policy reserve in the 1st year is
$$[0+G(.6)](1.1)-1000q_{x}=p_{x}\cdot(16.84)$$

If we knew the value of $q_{x}$, we could find G. Using the recursive relationship for net reserve for the 1st year, we have
$$[0+80](1.1)-1000q_{x}=p_{x}(40)$$

, and solving for $q_{x}$ results in $q_{x}=.05$. Then
$$.6G(1.1)-1000(.05)=(.95)\cdot(16.84)\rightarrow G=100$$

Answer: A

---

**2.** We use the recursive reserve relationship
$$({}_{k-1}V+\pi)(1+i)-(b_{k}-{}_{k}V)\cdot q_{x+k-1}={}_{k}V.$$

At time 0, ${}_{0}V=0$, and at time 2 when the policy ends, ${}_{2}V=0$ since this is a term insurance. For the first year $(k=1)$, since $b_{1}=1000+{}_{1}V$, we have
$$\pi(1.08)-1000(.1)={}_{1}V \text{, so that } {}_{1}V=1.08\pi-100$$

Then, for the second year, $b_{2}=2000+{}_{2}V$, so that
$$(1.08\pi-100+\pi)(1.08)-2000(.1)=0.$$

Solving for $\pi$ results in $\pi=137.1$.

Answer: A

---

**3.** Let S denote the aggregate present value random variable of the N annuities.
$$S=\sum_{j=1}^{N}W_{j}$$
where each $W_{j}=500Y$ and Y is the PVRV for a life annuity-due of 1 per year. Then
$$E[Y]=\ddot{a}_{x}=\frac{1-A_{x}}{d}=\frac{1-.369131}{.06/1.06}=11.1454$$
, and
$$Var[Y]=\frac{1}{d^{2}}\cdot[^{2}A_{x}-(A_{x})^{2}]=12.8445.$$

Then, $E[W]=500E[Y]=5572.7$ and $Var[W]=500^{2}\cdot Var[Y]=3,211,125$.
$$E[S]=N\cdot E[W]=5572.7N$$
, and from the independence of the lives,
$$Var[S]=N\cdot Var[W]=3,211,125N.$$

We want the initial fund amount F so that $P[S\le F]=.90$. Applying the normal approximation, we get
$$P\left[\frac{S-5572.7N}{\sqrt{3,211,125N}}\le\frac{1,429,440-5572.7N}{\sqrt{3,211,125N}}\right]=\Phi\left(\frac{1,429,440-5572.7N}{\sqrt{3,211,125N}}\right)=.9$$

From the normal table, we get
$$\frac{1,429,440-5572.7N}{\sqrt{3,211,125N}}=1.28$$

We can solve a quadratic equation for N, or try each possible answer to find $N=250$.

Answer: C

---

**4.** $L=$ PVRV benefit - PVRV premium. The later that the death occurs, the smaller the PV of benefit and the larger the PV of premium received. The median value of L, say $L_{m}$ would satisfy $P[L\le L_{m}]=.5$. If we find the point $t_{m}$ for which ${}_{t_{m}}p_{70}=.5$, and then find the issue-date loss $L_{t_{m}}$ based on death at exact time t, then $L\le L_{t_{m}}$ is equivalent to $t\ge t_{m}$, which has probability .5.

From the table, $l_{70}=91,082.4$. In order to have ${}_{t}p_{70}=.5$, we must have $\frac{l_{70+t}}{91,082.4}=.5$ so that $l_{70+t_{m}}=45,541.2$. From the table we see that $l_{89}=45,995.6$ and $l_{90}=41,841.1$. Using linear interpolation, we see that under UDD we have $t_{m} \approx 89.109$.

The issue date loss if death occurs at age 89.109 (19.109 years after issue) is \$100,000v^{19.109}-1600\ddot{a}_{\overline{10}|.05}=26,391$. This is the median of L.

Answer: D

---

**9.** $_{2|}A_{[60]:\overline{2}|}=v^{3}\cdot{}_{2|}q_{[60]}+v^{4}\cdot({}_{3|}q_{[60]}+{}_{4}p_{[60]})$.
$${}_{2|}q_{[60]}={}_{2}p_{[60]}\cdot q_{[60]+2}=p_{[60]}\cdot p_{[60]+1}\cdot q_{[60]+2}=(1-.09)(1-.11)(.13)=.1053$$
$${}_{3|}q_{[60]}={}_{3}p_{[60]}\cdot q_{63}=p_{[60]}\cdot p_{[60]+1}\cdot p_{[60]+2}\cdot q_{63}=(1-.09)(1-.11)(1-.13)(.15)=.1057$$
$${}_{4}p_{[60]}=p_{[60]}\cdot p_{[60]+1}\cdot p_{[60]+2}\cdot p_{63}=(1-.09)(1-.11)(1-.13)(.85)=.5989$$
$$_{2|}A_{[60]:\overline{2}|}=.7224$$

Answer: D

---

**10.** Under the UDD assumption, $\ddot{a}_{x}^{(m)}=\alpha(m)\cdot\ddot{a}_{x}-\beta(m)$.
$$i^{(2)}/d^{(2)}=1+\frac{i^{(2)}}{2}=1.035374\rightarrow i^{(2)}=.070748 \text{ and } d^{(2)}=.068331$$

Then $i=(1+\frac{i^{(2)}}{2})^{2}-1=.0720$ and $d=\frac{i}{1+i}=.067164$.
Then, $\alpha(2)=\frac{id}{i^{(2)}d^{(2)}}=1.000316$ and $\beta(2)=\frac{\alpha(2)-1}{d^{(2)}}=.258984$.
Then, $\ddot{a}_{x}=\frac{\ddot{a}_{x}^{(2)}+\beta(2)}{\alpha(2)}=10.2557$ and $A_{x}=1-d\ddot{a}_{x}=.3112$.
Finally, under UDD, $\overline{A}_{x}=\frac{i}{\delta}\cdot A_{x}=\frac{.0720}{ln(1.072)}\cdot.3112=.322$.

Answer: D

---

**11.** From the LTAM Table we have \$1000A_{30}=76.98$.
The APV of the premiums is \$2x\cdot\ddot{a}_{30}-x\cdot\ddot{a}_{30:\overline{5}|}$.

From the LTAM Table we have $\ddot{a}_{30}=19.3834$, and
$$\ddot{a}_{30:\overline{5}|}=\ddot{a}_{30}-v^{5}{}_{5}p_{30}\ddot{a}_{35}=\ddot{a}_{30}-{}_{5}E_{30}\ddot{a}_{35}$$
$$=19.383-(.78219)(18.7928)=4.6839.$$

The APV of premiums is \$2x(19.3834)-x\cdot(4.6839)=34.0829x$.
Then \$34.0829x=76.98$, so that $x=2.26$.

Answer: E

---

**12.** The original net premium is based on the original insurance value.
$\$1000P_{60}=\frac{1000A_{60}}{ \ddot{a}_{60} } = \frac{1000A_{60}}{(1-A_{60})/d} = \frac{1000(.36933)}{(1-.36933)/(.06/1.06)}=33.145.$$

The expected loss at issue is
$$APV\ benefit - APV\ premium=1000A_{60}'-33.145 \ddot{a}_{60}'=1000A_{60}'-33.145\left(\frac{1-A_{60}'}{d}\right)=114.3.$$

It follows that $A_{60}'=.44140$. Therefore
$$A_{60}=.36933=vq_{60}+v(1-q_{60})A_{61}$$
and
$$A_{60}'=.44140=v(10q_{60})+v(1-10q_{60})A_{61}$$

Since there is no change in mortality from age 61, we get
$$A_{61}=\frac{.36933-vq_{60}}{v(1-q_{60})}=\frac{.4414-10vq_{60}}{v(1-10q_{60})}$$

This results in a quadratic equation for $q_{60}$, which we can solve. Alternatively, we can "guess and check" to find that $q_{60}=.01376$.

Answer: D

---

**13.** $R=(1-.05)\times(1-.08)\times(1-.12)\times(1-.2)=.95\times.92\times.88\times.8=.61529$.
$q(x,C)=.05$, $q(x+1,C+1)=q(x+1,C)\times(1-\phi_{x+1})=.08\times.9=.072$.
$q(x+2,C+2)=q(x+2,C)\times(1-\phi_{x+1})^{2}=.12\times.9^{2}=.0972$.
$q(x+3,C+3)=q(x+3,C)\times(1-\phi_{x+1})^{3}=.2\times.9^{3}=.1458$.
$$S=(1-.05)(1-.072)(1-.0972)(1-.1458)=.67987$$
$$\frac{R}{S}=.905$$

Answer: E

---

**15.** Let $p=1-q$.
$$\ddot{a}_{x:\overline{10}|}=1+vp_{x}+v^{2}{}_{2}p_{x}+\cdot\cdot\cdot+v^{9}{}_{9}p_{x}=1+vp+v^{2}p^{2}+\cdot\cdot\cdot+v^{9}p^{9}=\frac{1-v^{10}p^{10}}{1-vp}$$
$$A^{1}_{x:\overline{10}|}=vq_{x}+v^{2}{}_{1|}q_{x}+\cdot\cdot\cdot+v^{10}{}_{9|}q_{x}=vq+v^{2}pq+\cdot\cdot\cdot+v^{10}p^{9}q$$
$$=vq[1+vp+v^{2}p^{2}+\cdot\cdot\cdot+v^{9}p^{9}]=vq\left[\frac{1-v^{10}p^{10}}{1-vp}\right]$$
$$P^{1}_{x:\overline{10}|}=\frac{A^{1}_{x:\overline{10}|}}{\ddot{a}_{x:\overline{10}|}}=vq$$

Using the recursive formula for reserves, $(_{k-1}V + P)(1+i) - q_{x+k-1}b_k = p_{x+k-1} {}_{k}V$.
For $k=1$: $(0+vq)(1+i)-q(1)=p\cdot {}_{1}V \implies q-q = p\cdot {}_{1}V \implies 0=p\cdot {}_{1}V \implies {}_{1}V=0$.
Same equation continues for $k=2,3,...,9$ so ${}_{k}V=0$ for all k.

Answer: A

---

**18.** $G\cdot\ddot{a}_{35:\overline{40}|}=.25G+200+.1G a_{35:\overline{39}|}+50 a_{35:\overline{39}|}+200,000 A_{35:\overline{40}|}+200A^{1}_{35:\overline{40}|}$.
$$G=\frac{150+50\ddot{a}_{35:\overline{40}|}+200,000A_{35:\overline{40}|}+200A^{1}_{35:\overline{40}|}}{.9\ddot{a}_{35:\overline{40}|}-.15}$$

But $\ddot{a}_{35:\overline{40}|}=\frac{1-A_{35:\overline{40}|}}{d}=15.4663$, and $A_{35:\overline{40}|}^{1}=A_{35:\overline{40}|}-A_{35:\overline{40}| \quad \rceil} = .047971 \rightarrow G=1876.78$.
Net premium = \$200,000 \times A_{35:\overline{40}|} / \ddot{a}_{35:\overline{40}|} = 1610.58$. Expense loading $= G - P^{net} = 266.20$. Using the recursive relationship for expense reserves, we have
$$(_{0}V^{e} + G - e_0)(1+i) - e_1 q_{35} = p_{35} {}_{1}V^{e}$$
$$(0 + 1876.78 - (0.25 \times 1876.78 + 200))(1.06) - 200(0.001223) = (1-0.001223){}_{1}V^{e} \implies {}_{1}V^{e}=-427.94$$
and
$$(_{1}V^{e} + G - e_1)(1+i) - e_2 q_{36} = p_{36} {}_{2}V^{e}$$
$$(-427.94 + 1876.78 - (0.10 \times 1876.78 + 50))(1.06) - 200(0.0012735) = (1-0.0012735){}_{2}V^{e} \implies {}_{2}V^{e}=-424.1$$

Answer: B

---

**19.** We use the following general relationship:
$${}_{m}V=\pi\cdot\ddot{s}_{\overline{m}|}-\sum_{k=0}^{m-1}q_{x+k}\cdot(1+i)^{m-k-1}\cdot(b_{k+1}-{}_{k+1}V)$$

For an endowment policy, the reserve at the time of endowment is equal to the endowment amount. In this case, we have ${}_{30}V=500,000$. The premium is payable for only 20 years, so in the right hand side of the expression, $\pi\cdot \ddot{s}_{\overline{m}|}$ is replaced by $\pi\cdot \ddot{s}_{\overline{20}|}\cdot(1+i)^{10}$ (this term is the accumulated premium to the time of endowment using interest only). The expression becomes
$\$500,000=\pi\cdot s_{\overline{20}|}\cdot(1+i)^{10}-\sum_{k=0}^{29}q_{35+k}\cdot(1+i)^{30-k-1}\cdot(b_{k+1}-{}_{k+1}V).$$

Since $b_{k+1}={}_{k+1}V$ for $k=0,1,...,28$, and $b_{30}=0$ (no death benefit in year 30) and ${}_{30}V=500,000$, the summation simplifies. All terms in the sum are zero except for the last one, at k=29.
$\$500,000=\pi\cdot \ddot{s}_{\overline{20}|}\cdot(1+i)^{10}-q_{64}\cdot(1+i)^{0}\cdot(0-500,000)$$

With $i=.04$ and $q_{64}=.02$, solving for $\pi$ results in $\pi=10,689$.

Answer: E