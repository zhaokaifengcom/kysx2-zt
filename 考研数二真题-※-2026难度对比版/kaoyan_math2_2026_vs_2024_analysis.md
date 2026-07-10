# 2026 考研数学二真题与 2024 考研数学二真题难度对比分析

## 难度标注说明

评价依据主要包括：知识点综合程度、计算量、思维转换要求、易错点数量、是否需要证明或反例构造、是否具有压轴题特征。

# 第一部分：2024 年考研数学二真题、解析、知识点与难度

## 2024 年全国硕士研究生入学统一考试（数学二）试题与解析

### 一、选择题

#### 1

函数
$$
f(x)=|x|^{\frac{1}{(1-x)(x-2)}}
$$
的第一类间断点的个数为（ ）

- A. $3$
- B. $2$
- C. $1$
- D. $0$

**答案：** C

**解析：**  
间断点只可能在 $x=0,1,2$ 处。又
$$
\lim_{x\to 1}f(x)
=\lim_{x\to 1}\exp\!\left(\frac{\ln x}{(1-x)(x-2)}\right)
=e,
$$
故 $x=1$ 为可去间断点；而
$$
\lim_{x\to 2^-}f(x)=+\infty,\qquad \lim_{x\to 0^+}f(x)=+\infty,
$$
所以第一类间断点只有 $1$ 个，即 $x=1$。


> **知识点：** 间断点分类；指数型函数极限；可去间断点、无穷间断点判定
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 考查点集中在基本极限与间断点分类，计算量不大，但要注意定义域端点与 $x=1,2$ 的不同性质。

#### 2

已知
$$
\left\{
\begin{aligned}
x &= 1+t^3,\\
y &= e^{t^2},
\end{aligned}
\right.
$$
则
$$
\lim_{x\to+\infty}x\!\left[f\!\left(2+\frac{2}{x}\right)-f(2)\right]
$$
等于（ ）

- A. $2e$
- B. $\frac{4}{3}e$
- C. $\frac{2}{3}e$
- D. $\frac{e}{3}$

**答案：** B

**解析：**  
由参数方程，
$$
f'(x)=\frac{dy/dt}{dx/dt}=\frac{2te^{t^2}}{3t^2}.
$$
当 $x=2$ 时，$t=1$，故
$$
f'(2)=\frac{2}{3}e.
$$
于是
$$
\lim_{x\to+\infty}x\!\left[f\!\left(2+\frac{2}{x}\right)-f(2)\right]
=2\lim_{x\to+\infty}\frac{f\!\left(2+\frac{2}{x}\right)-f(2)}{2/x}
=2f'(2)=\frac{4}{3}e.
$$

> **知识点：** 参数方程求导；导数定义型极限；无穷小替换
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 核心是把极限识别为 $2f'(2)$，属于常规导数应用题。

#### 3

已知
$$
f(x)=\int_0^{\sin x}\sin t^3\,dt,\qquad
g(x)=\int_0^x f(t)\,dt,
$$
则（ ）

- A. $f(x)$ 为奇函数，$g(x)$ 为奇函数
- B. $f(x)$ 为奇函数，$g(x)$ 为偶函数
- C. $f(x)$ 为偶函数，$g(x)$ 为偶函数
- D. $f(x)$ 为偶函数，$g(x)$ 为奇函数

**答案：** D

**解析：**  
设
$$
h(x)=\int_0^x \sin t^3\,dt.
$$
因 $\sin(t^3)$ 为奇函数，所以 $h(x)$ 为偶函数。于是
$$
f(x)=h(\sin x)
$$
仍为偶函数；而
$$
g(x)=\int_0^x f(t)\,dt
$$
是偶函数在 $[0,x]$ 上的积分，因此为奇函数。


> **知识点：** 奇偶函数；变上限积分奇偶性；复合函数奇偶性
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 思路明确，关键是判断奇函数积分函数的奇偶性。

#### 4

已知数列 $\{a_n\}$（$a_n\ne 0$），若 $\{a_n\}$ 发散，则（ ）

- A. $\left\{a_n+\frac{1}{a_n}\right\}$ 发散
- B. $\left\{a_n-\frac{1}{a_n}\right\}$ 发散
- C. $\left\{e^{a_n}+\frac{1}{e^{a_n}}\right\}$ 发散
- D. $\left\{e^{a_n}-\frac{1}{e^{a_n}}\right\}$ 发散

**答案：** D

**解析：**  
A、C 可取反例 $a_n=2^{(-1)^n}$；B 可取反例 $a_n=(-1)^n$。  
对 D，设
$$
b_n=e^{a_n}-e^{-a_n}.
$$
函数
$$
\varphi(x)=e^x-e^{-x}
$$
在 $\mathbb R$ 上连续且严格单调递增，故存在连续反函数。若 $\{b_n\}$ 收敛，则
$$
a_n=\varphi^{-1}(b_n)
$$
也收敛，与题设矛盾，所以 D 正确。

> **知识点：** 数列收敛与发散；连续单调函数反函数；反例构造
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 需要分别排除多个选项，并用严格单调连续函数的反函数说明正确项，逻辑性较强。

#### 5

已知函数
$$
f(x,y)=
\begin{cases}
(x^2+y^2)\sin\frac{1}{xy}, & xy\ne 0,\\
0, & xy=0,
\end{cases}
$$
则在点 $(0,0)$ 处（ ）

- A. $\dfrac{\partial f}{\partial x}$ 连续，$f$ 可微
- B. $\dfrac{\partial f}{\partial x}$ 连续，$f$ 不可微
- C. $\dfrac{\partial f}{\partial x}$ 不连续，$f$ 可微
- D. $\dfrac{\partial f}{\partial x}$ 不连续，$f$ 不可微

**答案：** C

**解析：**  
先有
$$
\frac{\partial f}{\partial x}(0,0)=0,\qquad \frac{\partial f}{\partial y}(0,0)=0.
$$
且
$$
\left|\frac{f(x,y)-f(0,0)}{\sqrt{x^2+y^2}}\right|
\le \sqrt{x^2+y^2}\to 0,
$$
故 $f$ 在 $(0,0)$ 可微。  
当 $xy\ne 0$ 时，
$$
\frac{\partial f}{\partial x}
=2x\sin\frac{1}{xy}-\frac{x^2+y^2}{x^2y}\cos\frac{1}{xy},
$$
其在 $(0,0)$ 附近极限不存在，所以偏导不连续。

> **知识点：** 二元函数可微定义；偏导数连续性；夹逼估计；振荡项
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 可微性用定义和夹逼较直接，但偏导不连续需要识别强振荡项，容易误判。

#### 6

设 $f(x,y)$ 为连续函数，则
$$
\int_{\pi/6}^{\pi/2}dx\int_{\sin x}^{1}f(x,y)\,dy
=
(\ \ )
$$

- A. $\displaystyle \int_{1/2}^{1}dy\int_{\pi/6}^{\arcsin y}f(x,y)\,dx$
- B. $\displaystyle \int_{1/2}^{1}dy\int_{\arcsin y}^{\pi/2}f(x,y)\,dx$
- C. $\displaystyle \int_0^{1/2}dy\int_{\pi/6}^{\arcsin y}f(x,y)\,dx$
- D. $\displaystyle \int_0^{1/2}dy\int_{\arcsin y}^{\pi/2}f(x,y)\,dx$

**答案：** A

**解析：**  
原区域满足
$$
\frac{\pi}{6}\le x\le \frac{\pi}{2},\qquad \sin x\le y\le 1.
$$
换序后，
$$
\frac12\le y\le 1,\qquad \frac{\pi}{6}\le x\le \arcsin y.
$$
故对应选项为 A。

> **知识点：** 二重积分换序；平面区域描述；反三角函数边界
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 属于常规换序题，画清区域后难度较低。

#### 7

设非负函数 $f(x)$ 在 $[0,+\infty)$ 上连续，给出三个命题：

1. 若 $\int_0^{+\infty}f^2(x)\,dx$ 收敛，则 $\int_0^{+\infty}f(x)\,dx$ 收敛；
2. 若存在 $p>1$，使极限 $\lim_{x\to+\infty}x^p f(x)$ 存在，则 $\int_0^{+\infty}f(x)\,dx$ 收敛；
3. 若 $\int_0^{+\infty}f(x)\,dx$ 收敛，则存在 $p>1$，使极限 $\lim_{x\to+\infty}x^p f(x)$ 存在。

其中正确命题的个数是（ ）

- A. $0$
- B. $1$
- C. $2$
- D. $3$

**答案：** B

**解析：**

- (1) 错。取 $f(x)=\dfrac{1}{1+x}$，则 $\int_0^{+\infty}f^2(x)\,dx$ 收敛，但 $\int_0^{+\infty}f(x)\,dx$ 发散。
- (2) 对。若 $\lim_{x\to+\infty}x^pf(x)$ 存在，则充分大时 $f(x)\le \dfrac{M}{x^p}$，再由比较判别法知积分收敛。
- (3) 错。取
  $$
  f(x)=\frac{1}{(x+2)\ln^2(x+2)},
  $$
  积分收敛，但不存在 $p>1$ 使 $x^pf(x)$ 极限存在。

故正确的只有 1 个。


> **知识点：** 反常积分敛散性；比较判别法；命题真假与反例
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 不仅要会判别收敛，还要构造或理解反例，综合性明显高于一般填空选择。

#### 8

设 $\boldsymbol A$ 为三阶矩阵，
$$
\boldsymbol P=
\begin{pmatrix}
1&0&0\\
0&1&0\\
1&0&1
\end{pmatrix},
$$
若
$$
\boldsymbol P^T\boldsymbol A\boldsymbol P^2=
\begin{pmatrix}
a+2c&0&c\\
0&b&0\\
2c&0&c
\end{pmatrix},
$$
则矩阵 $\boldsymbol A$ 为（ ）

- A. $\begin{pmatrix} c&0&0\\ 0&a&0\\ 0&0&b \end{pmatrix}$
- B. $\begin{pmatrix} b&0&0\\ 0&c&0\\ 0&0&a \end{pmatrix}$
- C. $\begin{pmatrix} a&0&0\\ 0&b&0\\ 0&0&c \end{pmatrix}$
- D. $\begin{pmatrix} c&0&0\\ 0&b&0\\ 0&0&a \end{pmatrix}$

**答案：** C

**解析：**  
由
$$
\boldsymbol A=(\boldsymbol P^T)^{-1}
\begin{pmatrix}
a+2c&0&c\\
0&b&0\\
2c&0&c
\end{pmatrix}
(\boldsymbol P^2)^{-1}
$$
直接计算得
$$
\boldsymbol A=
\begin{pmatrix}
a&0&0\\
0&b&0\\
0&0&c
\end{pmatrix}.
$$

> **知识点：** 矩阵乘法；可逆矩阵变换；矩阵方程求 $A$
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 按矩阵等式左、右乘逆矩阵即可，计算较机械。

#### 9

设 $\boldsymbol A$ 为 $4$ 阶矩阵，$\boldsymbol A^*$ 为 $\boldsymbol A$ 的伴随矩阵。若
$$
\boldsymbol A(\boldsymbol A-\boldsymbol A^*)=\boldsymbol O,\qquad \boldsymbol A\ne \boldsymbol A^*,
$$
则 $r(\boldsymbol A)$ 的取值为（ ）

- A. $0$ 或 $1$
- B. $1$ 或 $3$
- C. $2$ 或 $3$
- D. $1$ 或 $2$

**答案：** D

**解析：**  
若 $\boldsymbol A$ 可逆，则 $\boldsymbol A^*=|\boldsymbol A|\boldsymbol A^{-1}$，由题式可推出 $\boldsymbol A=\boldsymbol A^*$，矛盾；故 $\boldsymbol A$ 不可逆，从而
$$
\boldsymbol A\boldsymbol A^*=|\boldsymbol A|\boldsymbol E=\boldsymbol O.
$$
于是由题设得
$$
\boldsymbol A^2=\boldsymbol O.
$$
故
$$
r(\boldsymbol A)+r(\boldsymbol A)\le 4 \Rightarrow r(\boldsymbol A)\le 2.
$$
又 $\boldsymbol A\ne \boldsymbol O$，故
$$
r(\boldsymbol A)=1\ \text{或}\ 2.
$$

> **知识点：** 伴随矩阵；矩阵秩；幂零矩阵；Sylvester 秩不等式
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 需要把伴随矩阵性质、不可逆情形和 $A^2=O$ 的秩限制联系起来，抽象度较高。

#### 10

设 $\boldsymbol A,\boldsymbol B$ 均为 $2$ 阶矩阵，且 $\boldsymbol A\boldsymbol B=\boldsymbol B\boldsymbol A$，则“$\boldsymbol A$ 有两个不相等的特征值”是“$\boldsymbol B$ 可对角化”的（ ）

- A. 充要条件
- B. 充分不必要条件
- C. 必要不充分条件
- D. 既不充分也不必要条件

**答案：** B

**解析：**  
若 $\boldsymbol A$ 有两个不同特征值，则有两组线性无关特征向量。由 $\boldsymbol A\boldsymbol B=\boldsymbol B\boldsymbol A$ 可知，$\boldsymbol B$ 将 $\boldsymbol A$ 的特征子空间映到自身，因此这两组特征向量也可取为 $\boldsymbol B$ 的特征向量，故 $\boldsymbol B$ 可对角化。  
反之不成立，例如取
$$
\boldsymbol A=\boldsymbol B=\boldsymbol E,
$$
则 $\boldsymbol B$ 可对角化，但 $\boldsymbol A$ 没有两个不相等特征值。

### 二、填空题

> **知识点：** 可交换矩阵；特征子空间不变性；可对角化充分条件
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 考查线性代数理论理解，不只是计算；充分与必要的区分是难点。

#### 11

曲线 $y^2=x$ 在点 $(0,0)$ 处的曲率圆方程为 ______

**答案：**
$$
\left(x-\frac12\right)^2+y^2=\frac14
$$

**解析：**  
将曲线写成 $x=y^2$，则
$$
x'(y)=2y,\qquad x''(y)=2.
$$
故在 $y=0$ 处曲率为
$$
K=\frac{|x''(0)|}{\left(1+[x'(0)]^2\right)^{3/2}}=2,
$$
曲率半径
$$
R=\frac12.
$$
又曲线在原点处与 $y$ 轴相切，曲率中心为 $\left(\frac12,0\right)$，故曲率圆方程如上。

> **知识点：** 曲率与曲率圆；参数形式 $x=x(y)$ 的曲率；法线方向
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 公式本身不难，但曲线在原点处不能直接写成常规 $y=y(x)$，方向判断有一定陷阱。

#### 12

函数
$$
f(x,y)=2x^3-9x^2-6y^4+12x+24y
$$
的极值点为 ______

**答案：**
$$
(1,1)
$$

**解析：**  
由
$$
f_x=6x^2-18x+12,\qquad f_y=-24y^3+24,
$$
得驻点为 $(1,1)$、$(2,1)$。再由
$$
f_{xx}=12x-18,\qquad f_{xy}=0,\qquad f_{yy}=-72y^2,
$$
知在 $(1,1)$ 处，
$$
f_{xx}f_{yy}-f_{xy}^2>0,\qquad f_{xx}<0,
$$
故 $(1,1)$ 为极值点；而 $(2,1)$ 处判别式小于零，不是极值点。

> **知识点：** 多元函数驻点；二阶充分条件；Hessian 判别
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 标准的二元极值判别题，计算量较小。

#### 13

微分方程
$$
y'=\frac{1}{(x+y)^2}
$$
满足初始条件 $y(1)=0$ 的解为 ______

**答案：**
$$
y=\arctan(x+y)-\frac{\pi}{4}
$$

**解析：**  
令 $u=x+y$，则
$$
y=u-x,\qquad y'=u'-1.
$$
代入原方程得
$$
u'-1=\frac{1}{u^2}
\Rightarrow
u'=\frac{1+u^2}{u^2}.
$$
分离变量积分：
$$
x=u-\arctan u+C.
$$
代回 $u=x+y$，得
$$
y=\arctan(x+y)-C.
$$
再由 $y(1)=0$ 得 $C=\frac{\pi}{4}$。

> **知识点：** 一阶微分方程变量替换；分离变量；初值问题
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 变量替换 $u=x+y$ 是关键，识别后计算常规。

#### 14

已知函数
$$
f(x)=x^2(e^x-1),
$$
则
$$
f^{(5)}(1)=\ \underline{\qquad}
$$

**答案：**
$$
31e
$$

**解析：**  
由莱布尼茨公式可得
$$
f^{(5)}(x)=(x^2+10x+20)e^x.
$$
故
$$
f^{(5)}(1)=(1+10+20)e=31e.
$$

> **知识点：** 高阶导数；莱布尼茨公式；指数函数导数
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 用莱布尼茨公式直接计算，套路清晰。

#### 15

某物体以速度
$$
v(t)=t+k\sin\pi t
$$
做直线运动。若它从 $t=0$ 到 $t=3$ 的平均速度是 $\dfrac52$，则 $k=$ ______

**答案：**
$$
\frac{3\pi}{2}
$$

**解析：**  
由平均速度定义，
$$
\frac13\int_0^3\bigl(t+k\sin\pi t\bigr)\,dt=\frac52.
$$
计算得
$$
\frac13\left(\frac92+\frac{2k}{\pi}\right)=\frac52,
$$
故
$$
k=\frac{3\pi}{2}.
$$

> **知识点：** 定积分平均值；平均速度；三角函数积分
>
> **难度：** ★☆☆☆☆（1/5）
>
> **难度说明：** 公式直接，计算简单，是全卷较基础题。

#### 16

设向量
$$
\boldsymbol\alpha_1=
\begin{pmatrix}
a\\
1\\
-1\\
1
\end{pmatrix},\quad
\boldsymbol\alpha_2=
\begin{pmatrix}
1\\
1\\
b\\
a
\end{pmatrix},\quad
\boldsymbol\alpha_3=
\begin{pmatrix}
1\\
a\\
-1\\
1
\end{pmatrix}.
$$
若 $\boldsymbol\alpha_1,\boldsymbol\alpha_2,\boldsymbol\alpha_3$ 线性相关，且其中任意两个向量均线性无关，则 $ab=$ ______

**答案：**
$$
-4
$$

**解析：**  
对矩阵 $(\boldsymbol\alpha_1,\boldsymbol\alpha_2,\boldsymbol\alpha_3)$ 行变换，可化到
$$
\begin{pmatrix}
1&1&a\\
0&1&-1-a\\
0&0&a+b\\
0&0&a+2
\end{pmatrix}.
$$
由题设知秩为 $2$，故
$$
a+2=0,\qquad a+b=0.
$$
解得
$$
a=-2,\qquad b=2,
$$
于是
$$
ab=-4.
$$

### 三、解答题

> **知识点：** 向量组线性相关；矩阵秩；参数求解
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 需要把线性相关且任意两个无关转化为秩为 $2$，再处理参数。

#### 17

设平面有界区域 $D$ 位于第一象限，由曲线
$$
xy=\frac13,\qquad xy=3
$$
与直线
$$
y=\frac13x,\qquad y=3x
$$
围成，计算
$$
\iint_D(1+x-y)\,dx\,dy.
$$

**解析：**  
区域关于直线 $y=x$ 对称，因此
$$
\iint_D x\,dx\,dy=\iint_D y\,dx\,dy,
$$
从而原积分化为
$$
\iint_D 1\,dx\,dy,
$$
即只需求区域面积。

改用极坐标
$$
x=r\cos\theta,\qquad y=r\sin\theta.
$$
由边界条件得
$$
\arctan\frac13\le \theta\le \arctan 3,
$$
且
$$
\frac13\le r^2\sin\theta\cos\theta\le 3.
$$
故
$$
\iint_D dx\,dy
=
\int_{\arctan(1/3)}^{\arctan 3}
\int_{\sqrt{\frac{1}{3\sin\theta\cos\theta}}}^{\sqrt{\frac{3}{\sin\theta\cos\theta}}}
r\,dr\,d\theta.
$$
计算得
$$
\iint_D dx\,dy
=
\frac{8}{3}\int_{\arctan(1/3)}^{\arctan 3}\frac{1}{\sin 2\theta}\,d\theta
=
\frac{8}{3}\ln 3.
$$
因此
$$
\boxed{\iint_D(1+x-y)\,dx\,dy=\frac{8}{3}\ln 3 }.
$$

> **知识点：** 二重积分；极坐标；区域对称性；曲线边界转换
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 区域边界由双曲线和射线组成，极坐标转换与对称性是核心，区域识别要求较高。

#### 18

设 $y=y(x)$ 满足方程
$$
x^2y''+xy'-9y=0,
$$
且
$$
y\big|_{x=1}=2,\qquad y'\big|_{x=1}=6.
$$

1. 利用变换 $x=e^t$ 化简方程，并求 $y(x)$；
2. 求
   $$
   \int_1^2 y(x)\sqrt{4-x^2}\,dx.
   $$

**解析：**

##### （1）

令 $x=e^t$，则 $t=\ln x$。有
$$
\frac{dy}{dx}=\frac1x\frac{dy}{dt},\qquad
\frac{d^2y}{dx^2}=\frac{1}{x^2}\left(\frac{d^2y}{dt^2}-\frac{dy}{dt}\right).
$$
代入原方程得
$$
\frac{d^2y}{dt^2}-9y=0.
$$
故通解为
$$
y=C_1e^{3t}+C_2e^{-3t}=C_1x^3+C_2x^{-3}.
$$
再由
$$
y(1)=2,\qquad y'(1)=6
$$
解得
$$
C_1=2,\qquad C_2=0.
$$
因此
$$
\boxed{y=2x^3 }.
$$

##### （2）

于是
$$
\int_1^2 y(x)\sqrt{4-x^2}\,dx
=
\int_1^2 2x^3\sqrt{4-x^2}\,dx.
$$
令
$$
u=4-x^2,\qquad du=-2x\,dx,
$$
则
$$
2x^3dx=2x^2(x\,dx)=(4-u)(-du).
$$
故原积分化为
$$
\int_0^3 (4-u)u^{1/2}\,du
=
\left[\frac{8}{3}u^{3/2}-\frac{2}{5}u^{5/2}\right]_0^3
=
\frac{22}{5}\sqrt3.
$$
即
$$
\boxed{\int_1^2 y(x)\sqrt{4-x^2}\,dx=\frac{22}{5}\sqrt3 }.
$$

> **知识点：** 欧拉方程；变量替换 $x=e^t$；定积分计算
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 微分方程部分较典型，第二问积分计算增加了步骤量。

#### 19

设 $t>0$，曲线
$$
y=\sqrt{x}e^{-x}
$$
与直线 $x=t,\ x=2t$ 及 $x$ 轴所围平面图形绕 $x$ 轴旋转所得的旋转体体积为 $V(t)$，求 $V(t)$ 的最大值。

**解析：**  
由旋转体体积公式，
$$
V(t)=\pi\int_t^{2t}\bigl(\sqrt{x}e^{-x}\bigr)^2\,dx
=\pi\int_t^{2t}xe^{-2x}\,dx.
$$
对 $t$ 求导，
$$
V'(t)=2\pi\cdot (2t)e^{-4t}-\pi\cdot t e^{-2t}
=\pi t e^{-2t}(4e^{-2t}-1).
$$
故
$$
V'(t)
\begin{cases}
>0, & 0<t<\ln 2,\\
<0, & t>\ln 2.
\end{cases}
$$
所以 $V(t)$ 在 $t=\ln 2$ 处取得最大值。

代入得
$$
V_{\max}=V(\ln 2)
=\pi\int_{\ln 2}^{2\ln 2}xe^{-2x}\,dx
=\pi\left(\frac{\ln 2}{16}+\frac{3}{64}\right).
$$
即
$$
\boxed{V_{\max}=\pi\left(\frac{\ln 2}{16}+\frac{3}{64}\right)}.
$$

> **知识点：** 旋转体体积；变限积分求导；一元函数最值
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 模型常规，但需正确对 $V(t)$ 使用变限积分求导并判断最大值。

#### 20

设 $f(u,v)$ 具有二阶连续偏导，
$$
g(x,y)=f(2x+y,\,3x-y),
$$
且满足
$$
\frac{\partial^2g}{\partial x^2}
+\frac{\partial^2g}{\partial x\partial y}
-6\frac{\partial^2g}{\partial y^2}=1.
$$

1. 求 $\dfrac{\partial^2f}{\partial u\partial v}$；
2. 若 $\dfrac{\partial f(u,0)}{\partial u}=ue^{-u}$，且 $f(0,v)=\dfrac{1}{50}v^2-1$，求 $f(u,v)$。

**解析：**

##### （1）

由链式法则，
$$
u=2x+y,\qquad v=3x-y.
$$
于是
$$
g_x=2f_u+3f_v,\qquad g_y=f_u-f_v.
$$
继续求导得
$$
g_{xx}=4f_{uu}+12f_{uv}+9f_{vv},
$$
$$
g_{xy}=2f_{uu}+f_{uv}-3f_{vv},
$$
$$
g_{yy}=f_{uu}-2f_{uv}+f_{vv}.
$$
代入题设可得
$$
25f_{uv}=1.
$$
故
$$
\boxed{f_{uv}=\frac{1}{25}}.
$$

##### （2）

由
$$
f_{uv}=\frac{1}{25}
$$
知
$$
f_u(u,v)=\frac{1}{25}v+\phi(u).
$$
又因
$$
f_u(u,0)=ue^{-u},
$$
故
$$
\phi(u)=ue^{-u}.
$$
于是
$$
f_u(u,v)=\frac{1}{25}v+ue^{-u}.
$$
对 $u$ 积分，
$$
f(u,v)=\frac{1}{25}uv-(u+1)e^{-u}+\psi(v).
$$
再由
$$
f(0,v)=\frac{1}{50}v^2-1
$$
得
$$
\psi(v)=\frac{1}{50}v^2.
$$
因此
$$
\boxed{
f(u,v)=\frac{1}{25}uv-(u+1)e^{-u}+\frac{1}{50}v^2
}.
$$

> **知识点：** 复合函数二阶链式法则；偏微分方程；积分还原函数
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 二阶偏导展开量较大，后续还要由边界条件还原函数，综合计算要求高。

#### 21

设函数 $f(x)$ 具有二阶导数，且
$$
f'(0)=f'(1),\qquad |f''(x)|\le 1.
$$
证明：

1. 当 $x\in(0,1)$ 时，
   $$
   \left|f(x)-f(0)(1-x)-f(1)x\right|\le \frac{x(1-x)}{2};
   $$
2. 
   $$
   \left|\int_0^1 f(x)\,dx-\frac{f(0)+f(1)}{2}\right|\le \frac{1}{12}.
   $$

**解析：**

##### （1）

令
$$
g(x)=f(x)-f(0)(1-x)-f(1)x-\frac{x(1-x)}{2}.
$$
则
$$
g(0)=g(1)=0,
$$
且
$$
g''(x)=f''(x)+1\ge 0.
$$
若存在 $x_0\in(0,1)$ 使 $g(x_0)>0$，则由拉格朗日中值定理可在 $(0,x_0)$、$(x_0,1)$ 内分别取点 $\xi_1,\xi_2$，使
$$
g'(\xi_1)>0,\qquad g'(\xi_2)<0.
$$
再对 $g'$ 应用中值定理，可得某点 $\xi\in(\xi_1,\xi_2)$ 满足
$$
g''(\xi)<0,
$$
与 $g''(x)\ge 0$ 矛盾。故
$$
g(x)\le 0.
$$
同理，对
$$
\tilde g(x)=f(x)-f(0)(1-x)-f(1)x+\frac{x(1-x)}{2}
$$
可得
$$
\tilde g(x)\ge 0.
$$
于是
$$
-\frac{x(1-x)}{2}
\le
f(x)-f(0)(1-x)-f(1)x
\le
\frac{x(1-x)}{2},
$$
即
$$
\boxed{
\left|f(x)-f(0)(1-x)-f(1)x\right|
\le
\frac{x(1-x)}{2}
}.
$$

##### （2）

将上式在 $[0,1]$ 上积分，得
$$
-\int_0^1\frac{x(1-x)}{2}\,dx
\le
\int_0^1\left[f(x)-f(0)(1-x)-f(1)x\right]dx
\le
\int_0^1\frac{x(1-x)}{2}\,dx.
$$
而
$$
\int_0^1\frac{x(1-x)}{2}\,dx=\frac{1}{12},
$$
且
$$
\int_0^1\left[f(x)-f(0)(1-x)-f(1)x\right]dx
=
\int_0^1f(x)\,dx-\frac{f(0)+f(1)}{2}.
$$
因此
$$
\boxed{
\left|\int_0^1f(x)\,dx-\frac{f(0)+f(1)}{2}\right|
\le
\frac{1}{12}
}.
$$

> **知识点：** 拉格朗日中值定理；凸性/凹性；二阶导数有界的不等式证明；积分估计
>
> **难度：** ★★★★★（5/5）
>
> **难度说明：** 证明题对构造辅助函数和不等式双侧估计要求高，是 2024 卷中理论难度最高的题之一。

#### 22

设矩阵
$$
\boldsymbol A=
\begin{pmatrix}
0&1&a\\
1&0&1
\end{pmatrix},\qquad
\boldsymbol B=
\begin{pmatrix}
1&1\\
1&1\\
b&2
\end{pmatrix},
$$
二次型
$$
f(x_1,x_2,x_3)=\boldsymbol x^T\boldsymbol B\boldsymbol A\boldsymbol x.
$$

已知方程组 $\boldsymbol A\boldsymbol x=0$ 的解是 $\boldsymbol B^T\boldsymbol x=0$ 的解，但两个方程组不同解。

1. 求 $a,b$ 的值；
2. 求正交变换 $\boldsymbol x=\boldsymbol Q\boldsymbol y$，将 $f(x_1,x_2,x_3)$ 化为标准形。

**解析：**

##### （1）

由题意，
$$
\boldsymbol A\boldsymbol x=0
\quad\text{与}\quad
\begin{pmatrix}
\boldsymbol A\\
\boldsymbol B^T
\end{pmatrix}\boldsymbol x=0
$$
同解，故
$$
r\!\begin{pmatrix}
\boldsymbol A\\
\boldsymbol B^T
\end{pmatrix}
=r(\boldsymbol A)=2.
$$
而
$$
\begin{pmatrix}
\boldsymbol A\\
\boldsymbol B^T
\end{pmatrix}
=
\begin{pmatrix}
0&1&a\\
1&0&1\\
1&1&b\\
1&1&2
\end{pmatrix}
\sim
\begin{pmatrix}
1&1&2\\
0&1&1\\
0&0&a-1\\
0&0&b-2
\end{pmatrix}.
$$
故
$$
a-1=0,\qquad b-2=0.
$$
因此
$$
\boxed{a=1,\qquad b=2 }.
$$

##### （2）

代入 $a=1,\ b=2$，得
$$
\boldsymbol B\boldsymbol A
=
\begin{pmatrix}
1&1\\
1&1\\
2&2
\end{pmatrix}
\begin{pmatrix}
0&1&1\\
1&0&1
\end{pmatrix}
=
\begin{pmatrix}
1&1&2\\
1&1&2\\
2&2&4
\end{pmatrix}.
$$
于是
$$
f(x_1,x_2,x_3)=x_1^2+x_2^2+4x_3^2+2x_1x_2+4x_1x_3+4x_2x_3
=(x_1+x_2+2x_3)^2.
$$
故该矩阵只有一个非零特征值：
$$
\lambda_1=6,\qquad \lambda_2=\lambda_3=0.
$$
取对应的单位正交特征向量为
$$
\boldsymbol q_1=\frac{1}{\sqrt6}
\begin{pmatrix}
1\\
1\\
2
\end{pmatrix},\qquad
\boldsymbol q_2=\frac{1}{\sqrt2}
\begin{pmatrix}
1\\
-1\\
0
\end{pmatrix},\qquad
\boldsymbol q_3=\frac{1}{\sqrt3}
\begin{pmatrix}
1\\
1\\
-1
\end{pmatrix}.
$$
令
$$
\boldsymbol Q=(\boldsymbol q_1,\boldsymbol q_2,\boldsymbol q_3)
=
\begin{pmatrix}
\frac{1}{\sqrt6} & \frac{1}{\sqrt2} & \frac{1}{\sqrt3}\\[4pt]
\frac{1}{\sqrt6} & -\frac{1}{\sqrt2} & \frac{1}{\sqrt3}\\[4pt]
\frac{2}{\sqrt6} & 0 & -\frac{1}{\sqrt3}
\end{pmatrix}.
$$
则
$$
\boldsymbol Q^T(\boldsymbol B\boldsymbol A)\boldsymbol Q
=
\operatorname{diag}(6,0,0).
$$
因此在正交变换 $\boldsymbol x=\boldsymbol Q\boldsymbol y$ 下，
$$
\boxed{f=6y_1^2 }.
$$

> **知识点：** 矩阵秩与方程组解空间；二次型；正交对角化；特征向量构造
>
> **难度：** ★★★★★（5/5）
>
> **难度说明：** 线性代数压轴题综合了解空间、参数、二次型标准形和正交变换，步骤长且容错率低。

# 第二部分：2026 年考研数学二真题、解析、知识点与难度

## 2026 年全国硕士研究生入学统一考试（数学二）试题与解析

### 一、选择题

`1~10` 小题，每小题 `5` 分，共 `50` 分.下列每题给出的四个选项中，只有一个选项符合题目要求.

#### 1

已知当 $x \to 0$ 时，$a x^{2} + b x + \arcsin x$ 与 $\sqrt[3]{1 + x^{2}} - 1$ 是等价无穷小，则

- A. $a = \frac{1}{3},\ b = -1$
- B. $a = \frac{1}{3},\ b = 1$
- C. $a = \frac{2}{3},\ b = -1$
- D. $a = \frac{2}{3},\ b = 1$

**答案：** A

**解析：**  
当 $x \to 0$ 时，
$$
\sqrt[3]{1+x^2}-1 \sim \frac13 x^2,\qquad \arcsin x = x + o(x^2).
$$
故
$$
ax^2+bx+\arcsin x=(b+1)x+ax^2+o(x^2).
$$
与 $\frac13 x^2$ 等价，必有
$$
b+1=0,\qquad a=\frac13.
$$
故选 **A**.


> **知识点：** 等价无穷小；Taylor 展开；反三角函数与幂函数展开
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 只需展开到二阶并匹配一次项、二次项，基础但要注意一次项必须消失。

#### 2

设 $y_1(x),y_2(x)$ 是某二阶非齐次线性微分方程的两个特解.若常数 $\lambda,\mu$ 使得 $2\lambda y_1(x)+\mu y_2(x)$ 是该方程的解，$\lambda y_1(x)-2\mu y_2(x)$ 是该方程对应齐次方程的解，则

- A. $\lambda=\frac15,\ \mu=\frac25$
- B. $\lambda=\frac25,\ \mu=\frac15$
- C. $\lambda=\frac14,\ \mu=\frac12$
- D. $\lambda=\frac12,\ \mu=\frac14$

**答案：** B

**解析：**  
非齐次解线性组合仍为原方程解时，特解系数和应为 $1$；齐次解对应系数和应为 $0$.故
$$
2\lambda+\mu=1,\qquad \lambda-2\mu=0.
$$
解得
$$
\lambda=\frac25,\qquad \mu=\frac15.
$$
故选 **B**.

> **知识点：** 非齐次线性微分方程解结构；特解线性组合；齐次解判定
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 抓住非齐次特解系数和为 $1$、齐次组合系数和为 $0$ 即可。

#### 3

设函数 $z=z(x,y)$ 由方程 $x-az=e^{y+az}$（$a$ 为非零常数）确定，则

- A. $\dfrac{\partial z}{\partial x}-\dfrac{\partial z}{\partial y}=\dfrac1a$
- B. $\dfrac{\partial z}{\partial x}+\dfrac{\partial z}{\partial y}=\dfrac1a$
- C. $\dfrac{\partial z}{\partial x}-\dfrac{\partial z}{\partial y}=-\dfrac1a$
- D. $\dfrac{\partial z}{\partial x}+\dfrac{\partial z}{\partial y}=-\dfrac1a$

**答案：** A

**解析：**  
设
$$
F(x,y,z)=x-az-e^{y+az}=0.
$$
则
$$
F_x=1,\qquad F_y=-e^{y+az},\qquad F_z=-a\bigl(1+e^{y+az}\bigr).
$$
由隐函数求导公式，
$$
\frac{\partial z}{\partial x}=-\frac{F_x}{F_z}
=\frac{1}{a(1+e^{y+az})},
$$
$$
\frac{\partial z}{\partial y}=-\frac{F_y}{F_z}
=-\frac{e^{y+az}}{a(1+e^{y+az})}.
$$
两式相减得
$$
\frac{\partial z}{\partial x}-\frac{\partial z}{\partial y}=\frac1a.
$$
故选 **A**.

> **知识点：** 隐函数求导；二元偏导；代数消元
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 隐函数公式直接套用，最终相减出现常数，计算难度较低。

#### 4

设线密度为 $1$ 的细直棒两端点分别位于 $(-1,0)$ 和 $(1,0)$，质量为 $m$ 的质点位于 $(0,1)$，$G$ 为引力常量，则该细直棒对该质点的引力大小为

- A. $\displaystyle \int_0^1 \frac{2Gmx}{(x^2+1)^{1/2}}\,dx$
- B. $\displaystyle \int_0^1 \frac{2Gm}{(x^2+1)^{1/2}}\,dx$
- C. $\displaystyle \int_0^1 \frac{2Gmx}{(x^2+1)^{3/2}}\,dx$
- D. $\displaystyle \int_0^1 \frac{2Gm}{(x^2+1)^{3/2}}\,dx$

**答案：** D

**解析：**  
取棒上点 $(x,0)$ 的微元 $dx$，其到质点的距离为 $\sqrt{x^2+1}$.微元引力大小为
$$
dF=\frac{Gm\,dx}{x^2+1}.
$$
由对称性，水平方向分力抵消，只需取竖直分量：
$$
dF_y=dF\cdot \frac{1}{\sqrt{x^2+1}}
=\frac{Gm\,dx}{(x^2+1)^{3/2}}.
$$
故总引力为
$$
F=2\int_0^1 \frac{Gm}{(x^2+1)^{3/2}}\,dx.
$$
故选 **D**.

> **知识点：** 微元法；对称性；定积分建模；引力分解
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 不是单纯积分计算，还要建立物理微元模型并取竖直分量。

#### 5

设函数 $f(x)$ 在区间 $[-1,1]$ 上有定义，则

- A. 当 $f(x)$ 在 $(-1,0)$ 单调递减、在 $(0,1)$ 单调递增时，$f(0)$ 是极小值
- B. 当 $f(0)$ 是极小值时，$f(x)$ 在 $(-1,0)$ 单调递减、在 $(0,1)$ 单调递增
- C. 当 $f(x)$ 的图形在 $[-1,1]$ 上是凹的时，$\dfrac{f(x)-f(1)}{x-1}$ 在 $[-1,1)$ 上单调递增
- D. 当 $\dfrac{f(x)-f(1)}{x-1}$ 在 $[-1,1)$ 上单调递增时，$f(x)$ 的图形在 $[-1,1]$ 上是凹的

**答案：** C

**解析：**

- **A 错：** 取
  $$
  f(x)=
  \begin{cases}
  x^2, & x\ne 0,\\
  1, & x=0,
  \end{cases}
  $$
  则单调性满足，但 $f(0)$ 不是极小值.
- **B 错：** 取
  $$
  f(x)=
  \begin{cases}
  -x^2+1, & x\ne 0,\\
  0, & x=0,
  \end{cases}
  $$
  则 $f(0)$ 是极小值，但两侧单调性不满足.
- **C 对：** 若图形在 $[-1,1]$ 上是凹的，则割线斜率随点右移而增大，因此
  $$
  \frac{f(x)-f(1)}{x-1}
  $$
  在 $[-1,1)$ 上单调递增.
- **D 错：** 取 $f(x)=x^4-x^3$，上式单调递增，但 $f''(x)=6x(2x-1)$ 在 $[-1,1]$ 不恒号，不是凹函数.

故选 **C**.

> **知识点：** 极值、单调性与凹凸性；反例构造；割线斜率性质
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 多选项辨析需要反例意识和对凹函数割线斜率性质的理解，概念性较强。

#### 6

已知函数
$$
f(x)=\int_1^{x^3}\frac{e^t}{1+t^2}\,dt,
$$
$f$ 的反函数为 $g$，则

- A. $g(0)=1,\ g'(0)=\dfrac{3e}{2}$
- B. $g(0)=1,\ g'(0)=\dfrac{2}{3e}$
- C. $g(1)=0,\ g'(1)=\dfrac{3e}{2}$
- D. $g(1)=0,\ g'(1)=\dfrac{2}{3e}$

**答案：** B

**解析：**  
因 $f(1)=0$，故
$$
g(0)=1.
$$
由变上限积分求导，
$$
f'(x)=\frac{e^{x^3}}{1+x^6}\cdot 3x^2,
$$
于是
$$
f'(1)=\frac{3e}{2}.
$$
反函数求导公式给出
$$
g'(0)=\frac{1}{f'(1)}=\frac{2}{3e}.
$$
故选 **B**.

> **知识点：** 变上限积分求导；反函数求导；复合函数导数
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 属于典型反函数导数题，计算量较小。

#### 7

设函数 $f(x,y)$ 在区域
$$
D=\{(x,y)\mid 0\le x\le 1,\ 0\le y\le 1\}
$$
上连续，且 $f(x,y)=f(y,x)$，则
$$
\iint_D f(x,y)\,dx\,dy=
$$

- A. $\displaystyle 2\lim_{n\to\infty}\sum_{i=1}^n\sum_{j=n+1-i}^n f\!\left(\frac{i}{n},\frac{j}{n}\right)\frac{1}{n^2}$
- B. $\displaystyle \frac12\lim_{n\to\infty}\sum_{i=1}^n\sum_{j=i}^n f\!\left(\frac{i}{n},\frac{j}{n}\right)\frac{1}{n^2}$
- C. $\displaystyle 2\lim_{n\to\infty}\sum_{i=1}^{2n}\sum_{j=1}^{2n+1-i} f\!\left(\frac{i}{2n},\frac{j}{2n}\right)\frac{1}{n^2}$
- D. $\displaystyle \frac12\lim_{n\to\infty}\sum_{i=1}^{2n}\sum_{j=1}^i f\!\left(\frac{i}{2n},\frac{j}{2n}\right)\frac{1}{n^2}$

**答案：** D

**解析：**  
由对称性，
$$
\iint_D f(x,y)\,dx\,dy
=2\iint_{0\le y\le x\le 1} f(x,y)\,dx\,dy
=2\int_0^1 dx\int_0^x f(x,y)\,dy.
$$
选项 **D** 的求和区域正对应三角形区域 $0\le y\le x\le 1$，且网格边长为 $\frac{1}{2n}$，因此
$$
\frac12\cdot \frac{1}{n^2}
=2\cdot \frac{1}{(2n)^2},
$$
恰好对应上述二重积分.故选 **D**.

> **知识点：** 二重积分的 Riemann 和；对称区域；网格尺度换算
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 难点在于识别求和区域、网格面积和对称倍数之间的关系，容易因系数出错。

#### 8

单位矩阵经过若干次互换两行得到的矩阵称为置换矩阵.设 $\boldsymbol A$ 为 $n$ 阶置换矩阵，$\boldsymbol A^*$ 为 $\boldsymbol A$ 的伴随矩阵，则

- A. $\boldsymbol A^*$ 为置换矩阵
- B. $\boldsymbol A^{-1}$ 为置换矩阵
- C. $\boldsymbol A^{-1}=\boldsymbol A^*$
- D. $\boldsymbol A^{-1}=-\boldsymbol A^*$

**答案：** B

**解析：**  
置换矩阵的逆矩阵等于其转置，仍是置换矩阵，所以 **B** 正确.  
又
$$
\boldsymbol A^*=|\boldsymbol A|\,\boldsymbol A^{-1},\qquad |\boldsymbol A|=\pm 1.
$$
因此 $\boldsymbol A^*$ 不一定还是置换矩阵，且 **C、D** 也都不是恒成立.故选 **B**.

> **知识点：** 置换矩阵；逆矩阵与转置；伴随矩阵性质
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 核心事实是置换矩阵的逆仍为置换矩阵，伴随矩阵只需作为干扰项处理。

#### 9

设矩阵
$$
\boldsymbol A=
\begin{pmatrix}
1&0&1\\
0&0&1\\
1&1&3\\
1&1&1
\end{pmatrix},
\qquad
\boldsymbol C=
\begin{pmatrix}
2&0\\
1&1\\
1&1\\
a&b
\end{pmatrix}.
$$
若存在矩阵 $\boldsymbol B$ 满足 $\boldsymbol A\boldsymbol B=\boldsymbol C$，则

- A. $a=-1,\ b=-1$
- B. $a=2,\ b=2$
- C. $a=-1,\ b=2$
- D. $a=2,\ b=-1$

**答案：** A

**解析：**  
$\boldsymbol A\boldsymbol B=\boldsymbol C$ 意味着 $\boldsymbol C$ 的每一列都应属于 $\boldsymbol A$ 的列空间.

对第一列 $(2,1,1,a)^T$，设
$$
\boldsymbol A x=
\begin{pmatrix}
2\\1\\1\\a
\end{pmatrix}.
$$
由方程组得
$$
x_3=1,\quad x_1=1,\quad x_2=-3,
$$
再代入第四行得
$$
a=x_1+x_2+x_3=-1.
$$

同理，对第二列 $(0,1,1,b)^T$，解得
$$
x_3=1,\quad x_1=-1,\quad x_2=-1,
$$
故
$$
b=x_1+x_2+x_3=-1.
$$
故选 **A**.

> **知识点：** 矩阵方程 $AB=C$；列空间；线性方程组相容性
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 需要把存在 $B$ 转化为 $C$ 的列属于 $A$ 的列空间，线性代数建模意识较重要。

#### 10

设三阶矩阵 $\boldsymbol A,\boldsymbol B$ 满足
$$
\boldsymbol A\boldsymbol B+\boldsymbol B\boldsymbol A=\boldsymbol A^2+\boldsymbol B^2,
$$
且 $\boldsymbol A\ne \boldsymbol B$，则下列结论错误的是

- A. $(\boldsymbol A-\boldsymbol B)^3=\boldsymbol O$
- B. $\boldsymbol A-\boldsymbol B$ 只有零特征值
- C. $\boldsymbol A,\boldsymbol B$ 不能都是对角矩阵
- D. $\boldsymbol A-\boldsymbol B$ 只有一个线性无关的特征向量

**答案：** D

**解析：**  
原式化为
$$
\boldsymbol A(\boldsymbol B-\boldsymbol A)+\boldsymbol B(\boldsymbol A-\boldsymbol B)=\boldsymbol O,
$$
即
$$
(\boldsymbol A-\boldsymbol B)(\boldsymbol B-\boldsymbol A)=\boldsymbol O,
$$
从而
$$
(\boldsymbol A-\boldsymbol B)^2=\boldsymbol O.
$$
因此：

- **A 对：** 平方为零，立方当然也为零.
- **B 对：** 若 $\lambda$ 是 $\boldsymbol A-\boldsymbol B$ 的特征值，则 $\lambda^2=0$，故 $\lambda=0$.
- **C 对：** 若二者都为对角矩阵，则差仍为对角矩阵；对角矩阵平方为零只能是零矩阵，这与 $\boldsymbol A\ne\boldsymbol B$ 矛盾.
- **D 错：** 例如
  $$
  \begin{pmatrix}
  0&1&0\\
  0&0&0\\
  0&0&0
  \end{pmatrix}^2=\boldsymbol O,
  $$
  但其对应零特征值可有两个线性无关特征向量.

故选 **D**.

### 二、填空题

`11~16` 小题，每小题 `5` 分，共 `30` 分.

> **知识点：** 矩阵代数恒等变形；幂零矩阵；特征值与特征向量
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 由等式推出 $(A-B)^2=O$ 后，还要判断多个命题，理论辨析强。

#### 11

设 $p$ 为常数，若反常积分
$$
\int_0^{+\infty}\frac{\arctan x}{x^p(x+1)}\,dx
$$
收敛，则 $p$ 的取值范围是 ________.

**答案：** $0<p<2$

**解析：**  
分两端讨论：

- 当 $x\to 0^+$ 时，$\arctan x\sim x$，故被积函数
  $$
  \sim \frac{x}{x^p}=\frac{1}{x^{p-1}},
  $$
  收敛条件为 $p<2$.
- 当 $x\to +\infty$ 时，$\arctan x\to \frac\pi2$，故被积函数
  $$
  \sim \frac{\pi/2}{x^{p+1}},
  $$
  收敛条件为 $p>0$.

综上，
$$
0<p<2.
$$

> **知识点：** 反常积分；端点敛散性；等价无穷小与比较判别
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 两端分别比较是关键，条件合并较直接但容易漏掉一端。

#### 12

$$
\lim_{x\to 0}\left(\frac1x-\frac{\ln(1+x)}{x\sin x}\right)=\ \underline{\qquad\qquad}.
$$

**答案：** $\dfrac12$

**解析：**  
化为
$$
\lim_{x\to 0}\frac{\sin x-\ln(1+x)}{x\sin x}.
$$
利用展开式
$$
\sin x=x-\frac{x^3}{6}+o(x^3),\qquad \ln(1+x)=x-\frac{x^2}{2}+o(x^2),
$$
得分子为
$$
\frac12x^2+o(x^2),
$$
分母为 $x^2+o(x^2)$，故极限为
$$
\frac12.
$$

> **知识点：** 极限；Taylor 展开；对数和正弦展开
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 展开到二阶即可，属于基础极限题。

#### 13

曲线
$$
x^2+2\sqrt3xy+y^2=1
$$
在点 $(0,1)$ 处的曲率半径为 ________.

**答案：** $4$

**解析：**  
对方程求导：
$$
2x+2\sqrt3y+2\sqrt3x y'+2y y'=0.
$$
代入 $(0,1)$ 得
$$
y'(0)=-\sqrt3.
$$
再求一次导并代入 $(0,1)$，得
$$
y''(0)=2.
$$
曲率
$$
k=\frac{|y''|}{\left(1+(y')^2\right)^{3/2}}
=\frac{2}{(1+3)^{3/2}}
=\frac14.
$$
故曲率半径
$$
R=\frac1k=4.
$$

> **知识点：** 隐函数求导；曲率与曲率半径；二阶导数
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 隐式求二阶导再代入曲率公式，步骤稍多。

#### 14

已知函数 $f(x,y)$ 可微，且
$$
df(0,0)=\pi\,dx+3\,dy.
$$
记
$$
g(x)=f(\ln x,\sin \pi x),
$$
则
$$
g'(1)=\ \underline{\qquad\qquad}.
$$

**答案：** $-2\pi$

**解析：**  
由全微分知
$$
f_x(0,0)=\pi,\qquad f_y(0,0)=3.
$$
由链式法则，
$$
g'(x)=f_x(\ln x,\sin\pi x)\cdot \frac1x+f_y(\ln x,\sin\pi x)\cdot \pi\cos\pi x.
$$
代入 $x=1$ 时，$(\ln 1,\sin\pi)=(0,0)$，故
$$
g'(1)=\pi\cdot 1+3\pi\cos\pi=\pi-3\pi=-2\pi.
$$

> **知识点：** 全微分；多元复合函数链式法则；偏导数代入
>
> **难度：** ★★☆☆☆（2/5）
>
> **难度说明：** 由全微分读出偏导后代入链式法则，计算简单。

#### 15

函数
$$
f(x)=\ln(2+x)
$$
在区间 $[0,2]$ 上的平均值为 ________.

**答案：** $3\ln 2-1$

**解析：**  
平均值为
$$
\frac12\int_0^2 \ln(2+x)\,dx.
$$
令 $u=2+x$，则
$$
\frac12\int_2^4 \ln u\,du
=\frac12\bigl(u\ln u-u\bigr)\Big|_2^4
=3\ln 2-1.
$$


> **知识点：** 函数平均值；定积分换元；对数积分
>
> **难度：** ★☆☆☆☆（1/5）
>
> **难度说明：** 直接套平均值公式并换元计算，是基础送分题。

#### 16

设矩阵
$$
\boldsymbol A=
\begin{pmatrix}
1&b&-1\\
a+2&3&-3a
\end{pmatrix}.
$$
若二次型
$$
\boldsymbol x^T(\boldsymbol A\boldsymbol A^T)\boldsymbol x
$$
的规范形为 $y_1^2$，则 $a+b=$ ________.

**答案：** $2$

**解析：**  
规范形只有一项，说明
$$
r(\boldsymbol A\boldsymbol A^T)=1.
$$
故
$$
r(\boldsymbol A)=1,
$$
即两行成比例.于是
$$
\frac{1}{a+2}=\frac{b}{3}=\frac{1}{3a}.
$$
由
$$
a+2=3a,\qquad 3=(a+2)b
$$
得
$$
a=1,\qquad b=1.
$$
故
$$
a+b=2.
$$

### 三、解答题

`17~22` 小题，共 `70` 分.解答应写出必要的文字说明、证明过程或演算步骤.

> **知识点：** 二次型规范形；矩阵秩；$AA^T$ 的秩性质
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 关键是由规范形只有一项推出秩为 $1$，再转化为两行成比例。

#### 17

（本题满分 `10` 分）

计算
$$
I=\int_{-1}^1 dx\int_{|x|}^{\sqrt{2-x^2}} y\sin\sqrt{x^2+y^2}\,dy.
$$

**解：**  
改用极坐标
$$
x=r\cos\theta,\qquad y=r\sin\theta.
$$
区域对应为
$$
0\le r\le \sqrt2,\qquad \frac{\pi}{4}\le \theta\le \frac{3\pi}{4}.
$$
故
$$
I=\int_{\pi/4}^{3\pi/4}\int_0^{\sqrt2} r^2\sin\theta\sin r\,dr\,d\theta
=\left(\int_{\pi/4}^{3\pi/4}\sin\theta\,d\theta\right)\left(\int_0^{\sqrt2}r^2\sin r\,dr\right).
$$
其中
$$
\int_{\pi/4}^{3\pi/4}\sin\theta\,d\theta=\sqrt2,
$$
且
$$
\int_0^{\sqrt2}r^2\sin r\,dr
=2\sqrt2\sin\sqrt2-2.
$$
因此
$$
I=\sqrt2\,(2\sqrt2\sin\sqrt2-2)=4\sin\sqrt2-2\sqrt2.
$$

> **知识点：** 二重积分；极坐标；区域识别；分部积分
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 极坐标区域较清楚，主要难点在径向积分的计算。

#### 18

（本题满分 `12` 分）

已知函数 $g(x)$ 连续.设
$$
f(x)=\int_0^{x^2} g(xt)\,dt,
$$
求 $f'(x)$ 的表达式，并判断 $f'(x)$ 在 $x=0$ 处的连续性.

**解：**  
当 $x\ne 0$ 时，令 $u=xt$，则
$$
f(x)=\int_0^{x^2} g(xt)\,dt
=\frac1x\int_0^{x^3} g(u)\,du.
$$
故
$$
f'(x)=-\frac{1}{x^2}\int_0^{x^3}g(u)\,du+3x\,g(x^3),\qquad x\ne 0.
$$

再看 $x=0$.因 $f(0)=0$，
$$
f'(0)=\lim_{x\to 0}\frac{f(x)-f(0)}{x}
=\lim_{x\to 0}\frac1{x^2}\int_0^{x^3}g(u)\,du.
$$
由积分中值定理，
$$
\int_0^{x^3}g(u)\,du=x^3 g(\xi_x),
$$
其中 $\xi_x$ 介于 $0$ 与 $x^3$ 之间.于是
$$
f'(0)=\lim_{x\to 0} x\,g(\xi_x)=0.
$$

因此
$$
f'(x)=
\begin{cases}
3x\,g(x^3)-\dfrac{1}{x^2}\displaystyle\int_0^{x^3}g(u)\,du, & x\ne 0,\\[1.1em]
0, & x=0.
\end{cases}
$$

再由同样的中值定理，
$$
\frac{1}{x^2}\int_0^{x^3}g(u)\,du=x\,g(\xi_x)\to 0,\qquad 3x\,g(x^3)\to 0,
$$
故
$$
\lim_{x\to 0} f'(x)=0=f'(0).
$$
所以 $f'(x)$ 在 $x=0$ 处连续.

> **知识点：** 含参变上限积分；换元；导数在特殊点的连续性；积分中值定理
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 除求导外，还要单独处理 $x=0$ 并证明连续性，对严谨性要求较高。

#### 19

（本题满分 `10` 分）

求函数
$$
f(x,y)=(2x^2-y^2)e^x
$$
的极值.

**解：**  
先求偏导：
$$
f_x=e^x(2x^2+4x-y^2),\qquad f_y=-2ye^x.
$$
令
$$
f_x=0,\qquad f_y=0,
$$
得驻点
$$
(0,0),\qquad (-2,0).
$$

再求二阶偏导：
$$
A=f_{xx}=e^x(2x^2+8x+4-y^2),\qquad
B=f_{xy}=-2ye^x,\qquad
C=f_{yy}=-2e^x.
$$

- 在 $(0,0)$ 处，
  $$
  AC-B^2=-8<0,
  $$
  不是极值点.
- 在 $(-2,0)$ 处，
  $$
  AC-B^2=8e^{-4}>0,\qquad A=-4e^{-2}<0,
  $$
  故为极大值点.

极大值为
$$
f(-2,0)=2\cdot 4\cdot e^{-2}=\frac{8}{e^2}.
$$

**结论：** 只有一个极大值
$$
\frac{8}{e^2},
$$
在点 $(-2,0)$ 处取得；无极小值.

> **知识点：** 多元函数极值；驻点；Hessian 判别
>
> **难度：** ★★★☆☆（3/5）
>
> **难度说明：** 标准极值题，但偏导和二阶判别需要完整计算。

#### 20

（本题满分 `12` 分）

已知 $M(x_0,y_0)$ 是曲线
$$
y=\frac{1}{1+x^2}\qquad (x\ge 0)
$$
的拐点，$O$ 为原点.记 $D$ 是第一象限中以曲线
$$
y=\frac{1}{1+x^2}\qquad (x\ge x_0),
$$
线段 $OM$ 及 $x$ 正半轴为边界的无界区域，求 $D$ 绕 $x$ 轴旋转所成旋转体的体积.

**解：**  
先求拐点.由
$$
y'=-\frac{2x}{(1+x^2)^2},\qquad
y''=\frac{6x^2-2}{(1+x^2)^3},
$$
令 $y''=0$，得
$$
x_0=\frac1{\sqrt3},\qquad y_0=\frac{3}{4}.
$$

于是直线 $OM$ 的方程为
$$
y=\frac{y_0}{x_0}x=\frac{3\sqrt3}{4}x,\qquad 0\le x\le \frac1{\sqrt3}.
$$

旋转体体积为
$$
V=\pi\int_0^{1/\sqrt3}\left(\frac{3\sqrt3}{4}x\right)^2dx
+\pi\int_{1/\sqrt3}^{+\infty}\frac{1}{(1+x^2)^2}\,dx.
$$

第一部分：
$$
\pi\int_0^{1/\sqrt3}\left(\frac{3\sqrt3}{4}x\right)^2dx
=\frac{\sqrt3}{16}\pi.
$$

第二部分用公式
$$
\int \frac{dx}{(1+x^2)^2}
=\frac{x}{2(1+x^2)}+\frac12\arctan x,
$$
故
$$
\pi\int_{1/\sqrt3}^{+\infty}\frac{1}{(1+x^2)^2}\,dx
=\frac{\pi^2}{6}-\frac{\sqrt3}{8}\pi.
$$

综上，
$$
V=\frac{\sqrt3}{16}\pi+\left(\frac{\pi^2}{6}-\frac{\sqrt3}{8}\pi\right)
=\frac{\pi^2}{6}-\frac{\sqrt3}{16}\pi.
$$

> **知识点：** 拐点；旋转体体积；无界区域积分；反常积分计算
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 区域由线段与无界曲线拼接，体积积分分段且含反常积分，步骤较长。

#### 21

（本题满分 `12` 分）

求微分方程
$$
x^2y''-2xy'-(y')^2=0\qquad (x>2)
$$
满足条件
$$
y\big|_{x=3}=\frac12,\qquad y'\big|_{x=3}=-9
$$
的解.

**解：**  
方程不显含 $y$，令
$$
p=y',
$$
则
$$
x^2p'-2xp-p^2=0.
$$
化为
$$
p'-\frac{2}{x}p=\frac{p^2}{x^2}.
$$
再令
$$
z=\frac1p,
$$
则
$$
z'=-\frac{p'}{p^2},
$$
代入得一阶线性方程
$$
z'+\frac{2}{x}z=-\frac1{x^2}.
$$
解得
$$
z=-\frac1x+\frac{C}{x^2}.
$$
由
$$
z(3)=\frac1{y'(3)}=-\frac19
$$
得
$$
-\frac13+\frac{C}{9}=-\frac19 \quad\Rightarrow\quad C=2.
$$
所以
$$
\frac1{y'}=-\frac1x+\frac{2}{x^2}
=\frac{2-x}{x^2},
$$
即
$$
y'=\frac{x^2}{2-x}=-x-2-\frac{4}{x-2}.
$$
积分得
$$
y=-\frac12x^2-2x-4\ln(x-2)+C_1.
$$
再由
$$
y(3)=\frac12
$$
得
$$
C_1=11.
$$
故所求解为
$$
\boxed{\,y=-\frac12x^2-2x-4\ln(x-2)+11\, }.
$$

> **知识点：** 不显含 $y$ 的二阶微分方程降阶；Riccati 型转线性；初值问题
>
> **难度：** ★★★★☆（4/5）
>
> **难度说明：** 降阶后还要用倒数替换化为线性方程，方法性强。

#### 22

（本题满分 `12` 分）

已知向量组
$$
\boldsymbol{\alpha}_1=
\begin{pmatrix}
1\\
0\\
-1\\
-1
\end{pmatrix},
\qquad
\boldsymbol{\alpha}_2=
\begin{pmatrix}
1\\
-1\\
0\\
-2
\end{pmatrix},
\qquad
\boldsymbol{\alpha}_3=
\begin{pmatrix}
0\\
-1\\
1\\
-1
\end{pmatrix},
\qquad
\boldsymbol{\alpha}_4=
\begin{pmatrix}
0\\
1\\
-1\\
1
\end{pmatrix}.
$$

记
$$
\boldsymbol A=(\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2,\boldsymbol{\alpha}_3,\boldsymbol{\alpha}_4),\qquad
\boldsymbol G=(\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2).
$$

1. 证明：$\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2$ 是 $\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2,\boldsymbol{\alpha}_3,\boldsymbol{\alpha}_4$ 的极大线性无关组；
2. 求矩阵 $\boldsymbol H$ 使得 $\boldsymbol A=\boldsymbol G\boldsymbol H$，并求 $\boldsymbol A^{10}$.

**（1）证明：**  
将 $\boldsymbol A$ 行化简：
$$
\boldsymbol A=
\begin{pmatrix}
1&1&0&0\\
0&-1&-1&1\\
-1&0&1&-1\\
-1&-2&-1&1
\end{pmatrix}
\sim
\begin{pmatrix}
1&0&-1&1\\
0&1&1&-1\\
0&0&0&0\\
0&0&0&0
\end{pmatrix}.
$$
故
$$
r(\boldsymbol A)=2.
$$
而 $\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2$ 显然线性无关，所以它们构成一个极大线性无关组.

另外由化简结果可直接读出
$$
\boldsymbol{\alpha}_3=-\boldsymbol{\alpha}_1+\boldsymbol{\alpha}_2,\qquad
\boldsymbol{\alpha}_4=\boldsymbol{\alpha}_1-\boldsymbol{\alpha}_2.
$$

**（2）解：**  
由上式，
$$
\boldsymbol A
=
\bigl(\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2,-\boldsymbol{\alpha}_1+\boldsymbol{\alpha}_2,\boldsymbol{\alpha}_1-\boldsymbol{\alpha}_2\bigr)
=
(\boldsymbol{\alpha}_1,\boldsymbol{\alpha}_2)
\begin{pmatrix}
1&0&-1&1\\
0&1&1&-1
\end{pmatrix}.
$$
故
$$
\boldsymbol H=
\begin{pmatrix}
1&0&-1&1\\
0&1&1&-1
\end{pmatrix}.
$$

设
$$
\boldsymbol D=\boldsymbol H\boldsymbol G,
$$
则
$$
\boldsymbol D=
\begin{pmatrix}
1&0&-1&1\\
0&1&1&-1
\end{pmatrix}
\begin{pmatrix}
1&1\\
0&-1\\
-1&0\\
-1&-2
\end{pmatrix}
=
\begin{pmatrix}
1&-1\\
0&1
\end{pmatrix}.
$$
于是
$$
\boldsymbol A^{10}
=(\boldsymbol G\boldsymbol H)^{10}
=\boldsymbol G(\boldsymbol H\boldsymbol G)^9\boldsymbol H
=\boldsymbol G\boldsymbol D^9\boldsymbol H.
$$
又因为
$$
\boldsymbol D=
\begin{pmatrix}
1&-1\\
0&1
\end{pmatrix},
$$
故
$$
\boldsymbol D^9=
\begin{pmatrix}
1&-9\\
0&1
\end{pmatrix}.
$$
从而
$$
\boldsymbol A^{10}
=\boldsymbol G\boldsymbol D^9\boldsymbol H
=
\begin{pmatrix}
1&-8&-9&9\\
0&-1&-1&1\\
-1&9&10&-10\\
-1&7&8&-8
\end{pmatrix}.
$$

> **知识点：** 向量组极大线性无关组；矩阵分解；低秩矩阵幂；Jordan 型幂结构
>
> **难度：** ★★★★★（5/5）
>
> **难度说明：** 压轴线代题把极大无关组、分解 $A=GH$ 与高次幂计算结合，综合性最强。

## 三、整体难度对比与结论

### 1. 星级统计结果

| 年份 | 逐题平均难度 | 按分值加权平均难度 | ★ | ★★ | ★★★ | ★★★★ | ★★★★★ |
||:|:|:|:|:|:|:|
| 2024 数学二 | 3.00/5 | 3.29/5 | 1 | 7 | 7 | 5 | 2 |
| 2026 数学二 | 2.95/5 | 3.23/5 | 1 | 7 | 7 | 6 | 1 |

> 加权平均难度按常见数二分值结构估算：选择题与填空题每题 $5$ 分，解答题总分 $70$ 分，并按第 $17$ 至 $22$ 题约 $10,12,10,12,12,14$ 分计入。该统计不是官方难度系数，而是基于本文逐题知识点、步骤量、综合性和易错程度给出的分析量化结果。

### 2. 分题型对比

**选择题部分：** 2024 年选择题理论辨析更强，典型题如第 7 题反常积分命题判断、第 9 题伴随矩阵与秩、第 10 题可交换矩阵与可对角化，均要求考生具备较强的概念理解和反例意识。2026 年选择题也有难题，例如第 5 题函数性质辨析、第 7 题二重积分 Riemann 和、第 10 题幂零矩阵命题判断，但整体上计算入口更直接，基础题比例略高。

**填空题部分：** 两年填空题都以常规计算为主。2024 年第 11 题曲率圆和第 16 题向量组参数有一定陷阱；2026 年第 11 题反常积分、第 13 题隐式曲率、第 16 题秩与二次型规范形也具有区分度。总体看，两年填空难度接近，2026 年更偏常规基础链条，2024 年个别题更考察形式转换。

**解答题部分：** 2024 年解答题难度更集中在后半卷：第 20 题二阶链式法则展开量大，第 21 题证明题对辅助函数构造和中值定理运用要求高，第 22 题线性代数综合度高。2026 年解答题同样有综合题，第 18 题考查导数在 $x=0$ 处连续性，第 20 题涉及无界区域旋转体体积，第 21 题是降阶微分方程，第 22 题为矩阵分解与高次幂，但整体更偏“方法识别 + 规范计算”，证明型抽象压力弱于 2024 年。

### 3. 最终结论

综合逐题星级、知识点覆盖和解题负担来看，**2024 年考研数学二整体难度略高于 2026 年**。主要依据有三点：第一，2024 年五星题有第 21 题和第 22 题两道，其中第 21 题为证明型不等式，抽象性和构造性较强；第二，2024 年线性代数选择题和压轴题对理论理解要求更高，不能只靠代入计算；第三，按本文加权估算，2024 年约为 **3.29/5**，2026 年约为 **3.23/5**，二者差距不大但 2024 年略占上风。

不过，2026 年并不简单。2026 年的难点主要体现在多处中档偏难题的连续分布，例如第 5、7、10、18、20、21、22 题，容易在概念辨析、区域识别、特殊点连续性和矩阵高次幂处失分。因此更准确的判断是：**2024 年属于“理论证明和线代综合更难”的试卷，2026 年属于“基础题较稳、中档题密集、压轴题综合”的试卷。若以应试体感衡量，2024 年对高分考生更有压迫感，2026 年对中等考生的稳定计算和规范表达要求更高。**