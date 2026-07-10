# 2026 年全国硕士研究生入学统一考试（数学二）试题与解析

## 一、选择题

`1~10` 小题，每小题 `5` 分，共 `50` 分.下列每题给出的四个选项中，只有一个选项符合题目要求.

### 1

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

::: info :bulb:深度讲解
本题更深入的讲解请[点击这里](https://zhaokaifeng.com/)获取。
:::

### 2

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

### 3

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

### 4

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

### 5

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

### 6

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

### 7

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

### 8

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

### 9

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

### 10

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

---

## 二、填空题

`11~16` 小题，每小题 `5` 分，共 `30` 分.

### 11

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

### 12

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

### 13

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

### 14

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

### 15

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

### 16

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

---

## 三、解答题

`17~22` 小题，共 `70` 分.解答应写出必要的文字说明、证明过程或演算步骤.

### 17

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

### 18

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

### 19

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

### 20

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

### 21

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

### 22

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
