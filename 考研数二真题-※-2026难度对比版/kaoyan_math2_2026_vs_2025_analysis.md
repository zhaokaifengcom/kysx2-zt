# 2026 考研数学二真题与 2025 考研数学二真题难度对比分析

在本文中，「荒原之梦考研数学」将对2026考研数二真题和2025考研数二真题的难度做一个全面的对比分析，希望有助于同学们把我最近几年的考研数学命题趋势和难度分布。难度评级采用五档，对应的含义如下：

- **★☆☆☆☆：** 直接套公式或单一基础知识点，计算量很小。
- **★★☆☆☆：** 基础题，但需要一到两个常规步骤。
- **★★★☆☆：** 中等题，涉及多步骤计算或两个以上知识点组合。
- **★★★★☆：** 较难题，综合性、抽象性或易错点明显。
- **★★★★★：** 全卷最难层级，通常需要较强证明能力、结构识别能力或高度综合的计算策略。

---

## 一、2025 年考研数学二真题、解析、知识点与难度

### 一、选择题

第 1～10 小题，每小题 5 分，共 50 分。下列每小题给出的四个选项中，只有一项符合题目要求。

#### 1

设函数 $z = z\left( x, y \right)$ 由 $z + \ln z - \int_{y}^{x} e^{-t^{2}} \mathrm{~d} t = 0$ 确定，则 $\frac{\partial z}{\partial x} + \frac{\partial z}{\partial y} =$

- A. $\frac{z}{z + 1}\left( e^{-x^{2}} - e^{-y^{2}} \right)$

- B. $\frac{z}{z + 1}\left( e^{-x^{2}} + e^{-y^{2}} \right)$

- C. $-\frac{z}{z + 1}\left( e^{-x^{2}} - e^{-y^{2}} \right)$

- D. $-\frac{z}{z + 1}\left( e^{-x^{2}} + e^{-y^{2}} \right)$

**答案：** A

**解析：** 原式两边分别对 $x$，$y$ 求导，得
$\frac{\partial z}{\partial x} + \frac{1}{z}\frac{\partial z}{\partial x} - e^{-x^{2}} = 0$，
$\frac{\partial z}{\partial y} + \frac{1}{z}\frac{\partial z}{\partial y} + e^{-y^{2}} = 0$.

两式相加得
$\frac{\partial z}{\partial x} + \frac{\partial z}{\partial y} = \frac{z}{z + 1}\left( e^{-x^{2}} - e^{-y^{2}} \right)$.


##### 考察知识点与难度

- **所用知识点：** 多元隐函数求导、变上限积分求导、偏导数线性组合。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 套路清晰，关键在于分别对 $x,y$ 求偏导后相加，计算量小。

#### 2

已知函数 $f\left( x \right) = \int_{0}^{x} e^{t^{2}} \sin t \mathrm{~d} t$，$g\left( x \right) = \int_{0}^{x} e^{t^{2}} \sin t \mathrm{~d} t \cdot \sin^{2} x$，则

- A. $x = 0$ 是 $f\left( x \right)$ 的极值点，也是 $g\left( x \right)$ 的极值点.

- B. $x = 0$ 是 $f\left( x \right)$ 的极值点，$\left( 0, 0 \right)$ 是曲线 $y = g\left( x \right)$ 的拐点.

- C. $x = 0$ 是 $f\left( x \right)$ 的极值点，$\left( 0, 0 \right)$ 是曲线 $y = f\left( x \right)$ 的拐点.

- D. $\left( 0, 0 \right)$ 是曲线 $y = f\left( x \right)$ 的极值点，也是曲线 $y = g\left( x \right)$ 的拐点.

**答案：** B

**解析：** $f^{\prime}\left( x \right) = e^{x^{2}} \sin x$，
$f^{\prime\prime}\left( x \right) = 2x e^{x^{2}} \sin x + e^{x^{2}} \cos x$.

故
$f^{\prime}\left( 0 \right) = 0$，$f^{\prime\prime}\left( 0 \right) = 1 > 0$，
所以 $x = 0$ 为 $f\left( x \right)$ 的极值点，但不是拐点.

又
$g^{\prime}\left( x \right) = e^{x^{2}} \sin x \cdot \sin^{2} x + \int_{0}^{x} e^{t^{2}} \sin t \mathrm{~d} t \cdot 2 \sin x \cos x$.

可得
$g^{\prime}\left( 0 \right) = 0$，$g^{\prime\prime}\left( 0 \right) = 0$，且继续求导得 $g^{\prime\prime\prime}\left( 0 \right) = 6 > 0$.

所以 $\left( 0, 0 \right)$ 是曲线 $y = g\left( x \right)$ 的拐点.


##### 考察知识点与难度

- **所用知识点：** 积分上限函数求导、极值二阶判别、拐点与高阶导数判断。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 需要同时判断极值与拐点，涉及到二阶、三阶导数，易在 $g(x)$ 的阶数上出错。

#### 3

如果对微分方程 $y^{\prime\prime} - 2a y^{\prime} + \left( a + 2 \right) y = 0$ 的任一解 $y\left( x \right)$，反常积分 $\int_{0}^{+\infty} y\left( x \right) \mathrm{~d} x$ 均收敛，那么 $a$ 的取值范围是

- A. $\left( -2, -1 \right]$

- B. $\left( -\infty, -1 \right]$

- C. $\left( -2, 0 \right)$

- D. $\left( -\infty, 0 \right)$

**答案：** C

**解析：** 特征方程为
$r^{2} - 2a r + \left( a + 2 \right) = 0$.

要使任一解对应的反常积分都收敛，需两个特征根都小于 $0$.于是
$r_{1} r_{2} = a + 2 > 0$，$r_{1} + r_{2} = 2a < 0$.

故 $-2 < a < 0$.


##### 考察知识点与难度

- **所用知识点：** 常系数二阶齐次线性微分方程、特征根符号、反常积分敛散性。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 先把问题转化为特征根均为负，再由根与系数关系确定范围，思路中等。

#### 4

设函数 $f\left( x \right)$，$g\left( x \right)$ 在 $x = 0$ 的某去心邻域内有定义且恒不为零.若当 $x \to 0$ 时，$f\left( x \right)$ 是 $g\left( x \right)$ 的高阶无穷小，则当 $x \to 0$ 时，

- A. $f\left( x \right) + g\left( x \right) = O\left( g\left( x \right) \right)$.

- B. $f\left( x \right) g\left( x \right) = o\left( f^{2}\left( x \right) \right)$.

- C. $f\left( x \right) = o\left( e^{g\left( x \right)} - 1 \right)$.

- D. $f\left( x \right) = o\left( g^{2}\left( x \right) \right)$.

**答案：** C

**解析：** 由题意，$f\left( x \right) = o\left( g\left( x \right) \right)$.

对 A，
$\lim_{x \to 0} \frac{f\left( x \right) + g\left( x \right)}{g\left( x \right)} = \lim_{x \to 0} \frac{f\left( x \right)}{g\left( x \right)} + 1 = 1$，
故 A 不正确.

对 B，
$\lim_{x \to 0} \frac{f\left( x \right) g\left( x \right)}{f^{2}\left( x \right)} = \lim_{x \to 0} \frac{g\left( x \right)}{f\left( x \right)} = +\infty$，
故 B 不正确.

对 C，
$\lim_{x \to 0} \frac{f\left( x \right)}{e^{g\left( x \right)} - 1} = \lim_{x \to 0} \frac{f\left( x \right)}{g\left( x \right)} \cdot \frac{g\left( x \right)}{e^{g\left( x \right)} - 1} = 0$，
故 C 正确.

对 D，
$\frac{f\left( x \right)}{g^{2}\left( x \right)} = \frac{f\left( x \right)}{g\left( x \right)} \cdot \frac{1}{g\left( x \right)}$，为未定式，故 D 不正确.


##### 考察知识点与难度

- **所用知识点：** 高阶无穷小、$o(\cdot)$ 与 $O(\cdot)$ 判断、等价无穷小。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 考查 $o$ 与 $O$ 的逻辑关系，选项辨析性较强，容易被常见结论误导。

#### 5

设函数 $f\left( x, y \right)$ 连续，则 $\int_{-2}^{2} \mathrm{~d} x \int_{4 - x^{2}}^{2} f\left( x, y \right) \mathrm{~d} y =$

- A. $\int_{0}^{4} \left[ \int_{-2}^{-\sqrt{4 - y}} f\left( x, y \right) \mathrm{~d} x + \int_{\sqrt{4 - y}}^{2} f\left( x, y \right) \mathrm{~d} x \right] \mathrm{~d} y$

- B. $\int_{0}^{4} \left[ \int_{-2}^{\sqrt{4 - y}} f\left( x, y \right) \mathrm{~d} x + \int_{\sqrt{4 - y}}^{2} f\left( x, y \right) \mathrm{~d} x \right] \mathrm{~d} y$

- C. $\int_{0}^{4} \left[ \int_{-2}^{-\sqrt{4 - y}} f\left( x, y \right) \mathrm{~d} x + \int_{2}^{\sqrt{4 - y}} f\left( x, y \right) \mathrm{~d} x \right] \mathrm{~d} y$

- D. $2 \int_{0}^{4} \mathrm{~d} y \int_{\sqrt{4 - y}}^{2} f\left( x, y \right) \mathrm{~d} x$

**答案：** A

**解析：** 积分区域由 $y = 4 - x^{2}$ 与 $y = 2$ 确定.改变积分次序后，对每个 $y \in \left[ 0, 4 \right]$，对应的 $x$ 分别落在
$\left[ -2, -\sqrt{4 - y} \right]$ 与 $\left[ \sqrt{4 - y}, 2 \right]$.

故原式等于
$\int_{0}^{4} \left[ \int_{-2}^{-\sqrt{4 - y}} f\left( x, y \right) \mathrm{~d} x + \int_{\sqrt{4 - y}}^{2} f\left( x, y \right) \mathrm{~d} x \right] \mathrm{~d} y$.


##### 考察知识点与难度

- **所用知识点：** 二重积分区域识别、交换积分次序、抛物线与直线围成区域。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 主要是画出积分区域并换序，属于常规二重积分选择题。

#### 6

设单位质点 $P$，$Q$ 分别位于点 $\left( 0, 0 \right)$ 和 $\left( 0, 1 \right)$ 处，$P$ 从点 $\left( 0, 0 \right)$ 出发沿 $x$ 轴正向移动，记 $G$ 为引力常量，则当质点 $P$ 移动到点 $\left( 1, 0 \right)$ 时，克服质点 $Q$ 的引力所做的功为

- A. $\int_{0}^{1} \frac{G}{x^{2} + 1} \mathrm{~d} x$

- B. $\int_{0}^{1} \frac{Gx}{\left( x^{2} + 1 \right)^{\frac{3}{2}}} \mathrm{~d} x$

- C. $\int_{0}^{1} \frac{G}{\left( x^{2} + 1 \right)^{\frac{3}{2}}} \mathrm{~d} x$

- D. $\int_{0}^{1} \frac{G\left( x + 1 \right)}{\left( x^{2} + 1 \right)^{\frac{3}{2}}} \mathrm{~d} x$

**答案：** B

**解析：** 当 $P$ 位于 $\left( x, 0 \right)$ 时，$Q P$ 的距离为 $\sqrt{x^{2} + 1}$，引力大小为 $\frac{G}{x^{2} + 1}$.

沿运动方向的分力为
$\frac{G}{x^{2} + 1} \cdot \frac{x}{\sqrt{x^{2} + 1}}$.

故所做的功为
$\int_{0}^{1} \frac{Gx}{\left( x^{2} + 1 \right)^{\frac{3}{2}}} \mathrm{~d} x$.


##### 考察知识点与难度

- **所用知识点：** 万有引力微元法、力的分解、变力做功定积分模型。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 物理背景明显，但数学上只需建立沿运动方向的分力积分，难度不高。

#### 7

设函数 $f\left( x \right)$ 连续，给出下列四个条件：

① $\lim_{x \to 0} \frac{\left| f\left( x \right) \right| - f\left( 0 \right)}{x}$ 存在；

② $\lim_{x \to 0} \frac{f\left( x \right) - \left| f\left( 0 \right) \right|}{x}$ 存在；

③ $\lim_{x \to 0} \frac{\left| f\left( x \right) \right|}{x}$ 存在；

④ $\lim_{x \to 0} \frac{\left| f\left( x \right) \right| - \left| f\left( 0 \right) \right|}{x}$ 存在.

其中能得到 “$f\left( x \right)$ 在 $x = 0$ 处可导” 的条件的个数是

- A. 1

- B. 2

- C. 3

- D. 4

**答案：** D

**解析：** 对于①：若极限存在，由连续性知 $\left| f\left( 0 \right) \right| = f\left( 0 \right)$，故 $f\left( 0 \right) \ge 0$.

* 若 $f\left( 0 \right) > 0$，则 $x = 0$ 的某邻域内有 $f\left( x \right) > 0$，于是 $\left| f\left( x \right) \right| = f\left( x \right)$，从而 $f$ 在 $0$ 处可导.
* 若 $f\left( 0 \right) = 0$，则①化为 $\lim_{x \to 0} \frac{\left| f\left( x \right) \right|}{x}$ 存在，与③同理可推出 $f$ 在 $0$ 处可导.

对于②：由连续性知 $f\left( 0 \right) = \left| f\left( 0 \right) \right|$，故
$\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x}$ 存在，
所以 $f$ 在 $0$ 处可导.

对于③：若 $\lim_{x \to 0} \frac{\left| f\left( x \right) \right|}{x} = A$ 存在，则连续性推出 $f\left( 0 \right) = 0$.
于是
$\lim_{x \to 0^{+}} \frac{f\left( x \right)}{x} = A$，
$\lim_{x \to 0^{-}} \frac{f\left( x \right)}{x} = -A$.
又因两侧极限必须相等，得 $A = -A$，故 $A = 0$.
所以
$\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} = \lim_{x \to 0} \frac{f\left( x \right)}{x} = 0$，
即 $f$ 在 $0$ 处可导.

对于④：

* 若 $f\left( 0 \right) > 0$，则邻域内 $\left| f\left( x \right) \right| = f\left( x \right)$，于是可导；
* 若 $f\left( 0 \right) = 0$，则化为③；
* 若 $f\left( 0 \right) < 0$，则邻域内 $\left| f\left( x \right) \right| = -f\left( x \right)$，于是
  $\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x}$ 也存在.

故四个条件都能推出 $f\left( x \right)$ 在 $x = 0$ 处可导.


##### 考察知识点与难度

- **所用知识点：** 连续性、绝对值函数、导数定义、左右极限与可导性判定。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 四个条件都要逐一讨论，尤其 $f(0)=0$ 时的左右极限处理较绕。

#### 8

设矩阵 $\boldsymbol{A} = \begin{pmatrix} 1 & 2 & 0 \\ 2 & a & 0 \\ 0 & 0 & b \end{pmatrix}$ 有一个正特征值和两个负特征值，则

- A. $a > 4$，$b > 0$

- B. $a < 4$，$b > 0$

- C. $a > 4$，$b < 0$

- D. $a < 4$，$b < 0$

**答案：** D

**解析：** $\left| \lambda \boldsymbol{E} - \boldsymbol{A} \right| = \left( b - \lambda \right)\left[ \lambda^{2} - \left( a + 1 \right)\lambda + a - 4 \right]$.

二次因式对应的两个根一正一负，故其常数项满足
$a - 4 < 0$，即 $a < 4$.

此时二次因式已经给出一个正根、一个负根.又矩阵总共有一个正特征值和两个负特征值，所以第三个特征值 $b$ 必须小于 $0$.


##### 考察知识点与难度

- **所用知识点：** 对称矩阵特征值符号、二次型惯性、二阶块矩阵特征根。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 利用块矩阵与特征值符号即可判断，计算压力较小。

#### 9

下列矩阵中，可以经过若干初等变换得到矩阵 $\begin{pmatrix} 1 & 1 & 0 & 1 \\ 0 & 0 & 1 & 2 \\ 0 & 0 & 0 & 0 \end{pmatrix}$ 的是

- A. $\begin{pmatrix} 1 & 1 & 0 & 1 \\ 1 & 2 & 1 & 3 \\ 2 & 3 & 1 & 4 \end{pmatrix}$

- B. $\begin{pmatrix} 1 & 1 & 0 & 1 \\ 1 & 1 & 2 & 5 \\ 1 & 1 & 1 & 3 \end{pmatrix}$

- C. $\begin{pmatrix} 1 & 0 & 0 & 1 \\ 0 & 1 & 0 & 3 \\ 0 & 1 & 0 & 0 \end{pmatrix}$

- D. $\begin{pmatrix} 1 & 1 & 2 & 3 \\ 1 & 2 & 2 & 3 \\ 2 & 3 & 4 & 6 \end{pmatrix}$

**答案：** B

**解析：** 对 B 作初等行变换：
$\begin{pmatrix} 1 & 1 & 0 & 1 \\ 1 & 1 & 2 & 5 \\ 1 & 1 & 1 & 3 \end{pmatrix} \to \begin{pmatrix} 1 & 1 & 0 & 1 \\ 0 & 0 & 1 & 2 \\ 0 & 0 & 0 & 0 \end{pmatrix}$.


##### 考察知识点与难度

- **所用知识点：** 初等行变换、行等价矩阵、矩阵秩与阶梯形。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 只需做有限次行变换或比较行最简形，属于基础线代题。

#### 10

设 3 阶矩阵 $\boldsymbol{A}$，$\boldsymbol{B}$ 满足 $r\left( \boldsymbol{A}\boldsymbol{B} \right) = r\left( \boldsymbol{B}\boldsymbol{A} \right) + 1$，则

- A. 方程组 $\left( \boldsymbol{A} + \boldsymbol{B} \right)\boldsymbol{x} = 0$ 只有零解.

- B. 方程组 $\boldsymbol{A}\boldsymbol{x} = 0$ 与方程组 $\boldsymbol{B}\boldsymbol{x} = 0$ 均只有零解.

- C. 方程组 $\boldsymbol{A}\boldsymbol{x} = 0$ 与方程组 $\boldsymbol{B}\boldsymbol{x} = 0$ 没有公共非零解.

- D. 方程组 $\boldsymbol{A}\boldsymbol{B}\boldsymbol{A}\boldsymbol{x} = 0$ 与方程组 $\boldsymbol{B}\boldsymbol{A}\boldsymbol{B}\boldsymbol{x} = 0$ 有公共非零解.

**答案：** D

**解析：** 取
$\boldsymbol{A} = \begin{pmatrix} 1 & 1 & 1 \\ -1 & -1 & -1 \\ 0 & 0 & 0 \end{pmatrix}$，
$\boldsymbol{B} = \begin{pmatrix} 1 & 1 & 1 \\ 1 & 1 & 1 \\ 1 & 1 & 1 \end{pmatrix}$.

则
$\boldsymbol{A}\boldsymbol{B} = \begin{pmatrix} 3 & 3 & 3 \\ -3 & -3 & -3 \\ 0 & 0 & 0 \end{pmatrix}$，
$\boldsymbol{B}\boldsymbol{A} = \begin{pmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}$.

故 $r\left( \boldsymbol{A}\boldsymbol{B} \right) = 1$，$r\left( \boldsymbol{B}\boldsymbol{A} \right) = 0$，满足题设.

而
$\left( \boldsymbol{A} + \boldsymbol{B} \right)\boldsymbol{x} = 0$ 有非零解，故 A 错；
$\boldsymbol{A}\boldsymbol{x} = 0$ 与 $\boldsymbol{B}\boldsymbol{x} = 0$ 都有非零解，故 B 错；
且这两个方程组有公共非零解，故 C 错.

因此选 D.


---

### 二、填空题

第 11～16 小题，每小题 5 分，共 30 分。


##### 考察知识点与难度

- **所用知识点：** 矩阵秩、零空间、公共非零解、反例判断。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 选项需要用秩条件和反例排除，抽象性较强，不能只凭直觉判断。

#### 11

设 $\int_{1}^{+\infty} \frac{a}{x\left( 2x + a \right)} \mathrm{~d} x = \ln 2$，则 $a =$ ________.

**答案：** $2$

**解析：** $\frac{a}{x\left( 2x + a \right)} = \frac{1}{x} - \frac{2}{2x + a}$.

故
$\int_{1}^{+\infty} \frac{a}{x\left( 2x + a \right)} \mathrm{~d} x = \left. \ln \frac{2x}{2x + a} \right|_{1}^{+\infty} = \ln \left| \frac{2 + a}{2} \right|$.

由 $\ln \left| \frac{2 + a}{2} \right| = \ln 2$ 得
$\left| \frac{2 + a}{2} \right| = 2$.

解得 $a = 2$ 或 $a = -6$.当 $a = -6$ 时，被积函数在区间 $\left[ 1, +\infty \right)$ 内有奇点，积分发散.

故 $a = 2$.


##### 考察知识点与难度

- **所用知识点：** 反常积分、有理式分解、参数取值与奇点排除。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 分式分解后求反常积分，并注意排除区间内奇点，整体较常规。

#### 12

曲线 $y = \sqrt[3]{x^{3} - 3x^{2} + 1}$ 的渐近线方程为 ________.

**答案：** $y = x - 1$

**解析：** 显然无水平渐近线与垂直渐近线.

又
$\lim_{x \to +\infty} \frac{y}{x} = \lim_{x \to +\infty} \frac{\sqrt[3]{x^{3} - 3x^{2} + 1}}{x} = 1$，

且
$\lim_{x \to +\infty} \left( y - x \right) = \lim_{x \to +\infty} \left( \sqrt[3]{x^{3} - 3x^{2} + 1} - x \right) = -1$.

所以有斜渐近线 $y = x - 1$.


##### 考察知识点与难度

- **所用知识点：** 曲线斜渐近线、无穷远处极限、立方根式渐近展开。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 斜渐近线的 $k,b$ 两个极限直接计算，属于基础题。

#### 13

$\lim_{n \to \infty} \frac{1}{n^{2}} \left[ \ln \frac{1}{n} + 2 \ln \frac{2}{n} + \cdots + \left( n - 1 \right) \ln \frac{n - 1}{n} \right] =$ ________.

**答案：** $-\frac{1}{4}$

**解析：** 原式可写为
$\lim_{n \to \infty} \sum_{k = 1}^{n - 1} \frac{k}{n} \ln \frac{k}{n} \cdot \frac{1}{n}$.

它是函数 $x \ln x$ 在区间 $\left[ 0, 1 \right]$ 上的黎曼和，因此
$\lim_{n \to \infty} \sum_{k = 1}^{n - 1} \frac{k}{n} \ln \frac{k}{n} \cdot \frac{1}{n} = \int_{0}^{1} x \ln x \mathrm{~d} x = -\frac{1}{4}$.


##### 考察知识点与难度

- **所用知识点：** 黎曼和极限、定积分定义、$x\ln x$ 的积分。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 把数列极限识别为黎曼和是关键，识别后计算简单。

#### 14

已知函数 $y = y\left( x \right)$ 由 $\left\{ \begin{aligned} x &= \ln \left( 1 + 2t \right), \\ 2t - \int_{1}^{y + t^{2}} e^{-u^{2}} \mathrm{~d} u &= 0 \end{aligned} \right.$
确定，则 $\left. \frac{\mathrm{d} y}{\mathrm{d} x} \right|_{x = 0} =$ ________.

**答案：** $e$

**解析：** 令 $t = 0$，代入方程得 $y = 1$.

对方程
$2t - \int_{1}^{y + t^{2}} e^{-u^{2}} \mathrm{~d} u = 0$
关于 $t$ 求导，得
$2 - e^{-\left( y + t^{2} \right)^{2}}\left( \frac{\mathrm{d} y}{\mathrm{d} t} + 2t \right) = 0$.

代入 $t = 0$，$y = 1$，得
$\left. \frac{\mathrm{d} y}{\mathrm{d} t} \right|_{t = 0} = 2e$.

又
$\frac{\mathrm{d} x}{\mathrm{d} t} = \frac{2}{1 + 2t}$，故 $\left. \frac{\mathrm{d} x}{\mathrm{d} t} \right|_{t = 0} = 2$.

所以
$\left. \frac{\mathrm{d} y}{\mathrm{d} x} \right|_{x = 0} = \frac{\left. \frac{\mathrm{d} y}{\mathrm{d} t} \right|_{t = 0}}{\left. \frac{\mathrm{d} x}{\mathrm{d} t} \right|_{t = 0}} = e$.


##### 考察知识点与难度

- **所用知识点：** 参数方程求导、变上限积分求导、隐函数求导。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 参数与隐函数求导组合，但代入点明确，计算量适中偏小。

#### 15

微分方程 $\left( 2y - 3x \right) \mathrm{d} x + \left( 2x - 5y \right) \mathrm{d} y = 0$ 满足条件 $y\left( 1 \right) = 1$ 的解为 ________.

**答案：** $5y^{2} - 4xy + 3x^{2} = 4$

**解析：** $\frac{\mathrm{d} y}{\mathrm{d} x} = \frac{2y - 3x}{5y - 2x} = \frac{2 \frac{y}{x} - 3}{5 \frac{y}{x} - 2}$.

令 $\frac{y}{x} = u$，则 $y = ux$，从而
$u + x \frac{\mathrm{d} u}{\mathrm{d} x} = \frac{2u - 3}{5u - 2}$.

化简得
$\frac{5u - 2}{5u^{2} - 4u + 3} \mathrm{d} u = -\frac{1}{x} \mathrm{d} x$.

两边积分可得
$5u^{2} - 4u + 3 = \frac{C}{x^{2}}$.

即
$5y^{2} - 4xy + 3x^{2} = C$.

由 $y\left( 1 \right) = 1$ 得 $C = 4$.

故所求解为
$5y^{2} - 4xy + 3x^{2} = 4$.


##### 考察知识点与难度

- **所用知识点：** 齐次微分方程、变量代换 $u=y/x$、初值问题。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 标准齐次微分方程，代换和积分步骤需要完整。

#### 16

设矩阵 $\boldsymbol{A} = \left( \boldsymbol{\alpha}_{1}, \boldsymbol{\alpha}_{2}, \boldsymbol{\alpha}_{3}, \boldsymbol{\alpha}_{4} \right)$.若 $\boldsymbol{\alpha}_{1}$，$\boldsymbol{\alpha}_{2}$，$\boldsymbol{\alpha}_{3}$ 线性无关，且 $\boldsymbol{\alpha}_{1} + \boldsymbol{\alpha}_{2} = \boldsymbol{\alpha}_{3} + \boldsymbol{\alpha}_{4}$，则方程组 $\boldsymbol{A}\boldsymbol{x} = \boldsymbol{\alpha}_{1} + 4\boldsymbol{\alpha}_{4}$ 的通解为 ________.

**答案：** $\boldsymbol{x} = k \begin{pmatrix} 1 \\ 1 \\ -1 \\ -1 \end{pmatrix} + \begin{pmatrix} 1 \\ 0 \\ 0 \\ 4 \end{pmatrix}$

**解析：** 由 $\boldsymbol{\alpha}_{1} + \boldsymbol{\alpha}_{2} = \boldsymbol{\alpha}_{3} + \boldsymbol{\alpha}_{4}$ 得
$\boldsymbol{\alpha}_{4} = \boldsymbol{\alpha}_{1} + \boldsymbol{\alpha}_{2} - \boldsymbol{\alpha}_{3}$.

故
$r\left( \boldsymbol{A} \right) = r\left( \boldsymbol{\alpha}_{1}, \boldsymbol{\alpha}_{2}, \boldsymbol{\alpha}_{3} \right) = 3$.

于是齐次方程组 $\boldsymbol{A}\boldsymbol{x} = \boldsymbol{0}$ 的基础解系只有一个线性无关向量，且
$\left( 1, 1, -1, -1 \right)^{\mathrm{T}}$ 是其一个解.

又
$\left( 1, 0, 0, 4 \right)^{\mathrm{T}}$ 是方程组 $\boldsymbol{A}\boldsymbol{x} = \boldsymbol{\alpha}_{1} + 4\boldsymbol{\alpha}_{4}$ 的一个特解.

故通解为
$\boldsymbol{x} = k \begin{pmatrix} 1 \\ 1 \\ -1 \\ -1 \end{pmatrix} + \begin{pmatrix} 1 \\ 0 \\ 0 \\ 4 \end{pmatrix}$.

---

### 三、解答题

第 17～22 小题，共 70 分。解答应写出必要的文字说明、证明过程或演算步骤。


##### 考察知识点与难度

- **所用知识点：** 向量组线性相关、极大线性无关组、线性方程组通解。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 从向量关系写出齐次解与特解，线代基础但有一定抽象性。

#### 17

（本题满分 10 分）

计算 $\int_{0}^{1} \frac{1}{\left( x + 1 \right)\left( x^{2} - 2x + 2 \right)} \mathrm{~d} x$.

**解：**
设
$\frac{1}{\left( 1 + x \right)\left( x^{2} - 2x + 2 \right)} = \frac{a}{1 + x} + \frac{bx + c}{x^{2} - 2x + 2}$.

比较系数得
$\left\{ \begin{aligned} a + b &= 0, \\ -2a + b + c &= 0, \\ 2a + c &= 1 \end{aligned} \right.$

解得
$a = \frac{1}{5}$，$b = -\frac{1}{5}$，$c = \frac{3}{5}$.

故原式
$= \int_{0}^{1} \left[ \frac{1}{5\left( 1 + x \right)} + \frac{-\frac{1}{5}x + \frac{3}{5}}{x^{2} - 2x + 2} \right] \mathrm{~d} x$

$= \frac{1}{5}\ln \left( 1 + x \right)\Big|_{0}^{1} - \frac{1}{5} \int_{0}^{1} \frac{x - 3}{x^{2} - 2x + 2} \mathrm{~d} x$

$= \frac{1}{5}\ln 2 - \frac{1}{5} \left[ \frac{1}{2} \int_{0}^{1} \frac{1}{x^{2} - 2x + 2} \mathrm{d} \left( x^{2} - 2x + 2 \right) - \int_{0}^{1} \frac{2}{x^{2} - 2x + 2} \mathrm{~d} x \right]$

$= \frac{1}{5}\ln 2 - \frac{1}{10}\ln \left( x^{2} - 2x + 2 \right)\Big|_{0}^{1} + \frac{2}{5} \int_{0}^{1} \frac{1}{\left( x - 1 \right)^{2} + 1} \mathrm{~d} x$

$= \frac{1}{5}\ln 2 - \frac{1}{10}\left( 0 - \ln 2 \right) + \frac{2}{5}\arctan \left( x - 1 \right)\Big|_{0}^{1}$

$= \frac{1}{5}\ln 2 + \frac{1}{10}\ln 2 + \frac{2}{5}\left( 0 + \frac{\pi}{4} \right)$

$= \frac{3}{10}\ln 2 + \frac{\pi}{10}$.


##### 考察知识点与难度

- **所用知识点：** 有理函数部分分式分解、定积分计算、反三角函数积分。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 部分分式分解较机械，后续积分也较常规。

#### 18

（本题满分 12 分）

设函数 $f\left( x \right)$ 在 $x = 0$ 处连续，且 $\lim_{x \to 0} \frac{x f\left( x \right) - e^{2 \sin x} + 1}{\ln \left( 1 + x \right) + \ln \left( 1 - x \right)} = -3$，证明 $f\left( x \right)$ 在 $x = 0$ 处可导，并求 $f^{\prime}\left( 0 \right)$.

**解：**
由
$\ln \left( 1 + x \right) + \ln \left( 1 - x \right) = \ln \left( 1 - x^{2} \right)$，
可将已知极限写为
$-3 = \lim_{x \to 0} \frac{x f\left( x \right) - e^{2 \sin x} + 1}{-x^{2}}$.

进一步化为
$-3 = \lim_{x \to 0} \frac{f\left( x \right) + \frac{1 - e^{2 \sin x}}{x}}{-x}$.

由于
$\lim_{x \to 0} \frac{1 - e^{2 \sin x}}{x} = -2$，
又由 $f\left( x \right)$ 在 $x = 0$ 处连续，可知 $f\left( 0 \right) = 2$.

于是
$-3 = \lim_{x \to 0} \frac{x\left[ f\left( x \right) - f\left( 0 \right) \right] + 2x - e^{2 \sin x} + 1}{-x^{2}}$

$= -\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} + \lim_{x \to 0} \frac{2x - e^{2 \sin x} + 1}{-x^{2}}$

$= -\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} + \lim_{x \to 0} \frac{2 - 2 \cos x \cdot e^{2 \sin x}}{-2x}$

$= -\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} + \lim_{x \to 0} \frac{1 - \cos x + \cos x \left( 1 - e^{2 \sin x} \right)}{-x}$

$= -\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} + 2$.

故
$\lim_{x \to 0} \frac{f\left( x \right) - f\left( 0 \right)}{x} = 5$.

所以 $f\left( x \right)$ 在 $x = 0$ 处可导，且
$f^{\prime}\left( 0 \right) = 5$.


##### 考察知识点与难度

- **所用知识点：** 极限展开、连续性推出函数值、导数定义、洛必达法或等价替换。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 需要从给定极限反推 $f(0)$ 与导数，展开和极限整理都不能漏项。

#### 19

（本题满分 12 分）

设函数 $f\left( x, y \right)$ 可微且满足 $\mathrm{d} f\left( x, y \right) = -2x e^{-y} \mathrm{d} x + e^{-y}\left( x^{2} - y - 1 \right) \mathrm{d} y$，$f\left( 0, 0 \right) = 2$，求 $f\left( x, y \right)$，并求 $f\left( x, y \right)$ 的极值.

**解：**
由题意知
$f_{x}^{\prime}\left( x, y \right) = -2x e^{-y}$，
$f_{y}^{\prime}\left( x, y \right) = e^{-y}\left( x^{2} - y - 1 \right)$.

对 $x$ 积分得
$f\left( x, y \right) = \int -2x e^{-y} \mathrm{~d} x = -x^{2} e^{-y} + C\left( y \right)$.

于是
$f_{y}^{\prime}\left( x, y \right) = x^{2} e^{-y} + C^{\prime}\left( y \right) = e^{-y}\left( x^{2} - y - 1 \right)$.

故
$C^{\prime}\left( y \right) = -\left( y + 1 \right)e^{-y}$，
从而
$C\left( y \right) = \left( y + 2 \right)e^{-y} + C$.

所以
$f\left( x, y \right) = -x^{2} e^{-y} + \left( y + 2 \right)e^{-y} + C$.

由 $f\left( 0, 0 \right) = 2$ 得 $C = 0$.

故
$f\left( x, y \right) = -x^{2} e^{-y} + \left( y + 2 \right)e^{-y}$.

令
$\left\{ \begin{aligned} f_{x}^{\prime}\left( x, y \right) &= -2x e^{-y} = 0, \\ f_{y}^{\prime}\left( x, y \right) &= e^{-y}\left( x^{2} - y - 1 \right) = 0 \end{aligned} \right.$
得驻点 $\left( 0, -1 \right)$.

再求二阶偏导：
$f_{xx}^{\prime\prime}\left( x, y \right) = -2e^{-y}$，
$f_{xy}^{\prime\prime}\left( x, y \right) = 2x e^{-y}$，
$f_{yy}^{\prime\prime}\left( x, y \right) = -e^{-y}\left( x^{2} - y - 1 \right) - e^{-y}$.

在点 $\left( 0, -1 \right)$ 处，
$A = -2e$，$B = 0$，$C = -e$，
故
$AC - B^{2} > 0$，且 $A < 0$.

所以 $\left( 0, -1 \right)$ 为极大值点，极大值为
$f\left( 0, -1 \right) = e$.


##### 考察知识点与难度

- **所用知识点：** 全微分还原原函数、二元函数驻点与二阶判别法。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 先由全微分积分还原函数，再做二元极值判别，综合度中等。

#### 20

（本题满分 12 分）

已知平面有界区域 $D = \left\{ \left( x, y \right) \mid x^{2} + y^{2} \le 4x,\ x^{2} + y^{2} \le 4y \right\}$，计算 $\iint_{D} \left( x - y \right)^{2} \mathrm{d} x \mathrm{d} y$.

**解：**
由区域关于直线 $y = x$ 对称，记第一部分区域为 $D_{1}$，则
$\iint_{D} \left( x - y \right)^{2} \mathrm{d} x \mathrm{d} y = 2 \iint_{D_{1}} \left( x^{2} + y^{2} - 2xy \right) \mathrm{d} x \mathrm{d} y$.

作极坐标变换
$x = r \cos \theta$，$y = r \sin \theta$.

在区域 $D_{1}$ 上有
$0 \le \theta \le \frac{\pi}{4}$，$0 \le r \le 4 \sin \theta$.

于是
$\iint_{D} \left( x - y \right)^{2} \mathrm{d} x \mathrm{d} y = 2 \int_{0}^{\frac{\pi}{4}} \mathrm{~d} \theta \int_{0}^{4 \sin \theta} \left( r^{2} - 2r^{2} \cos \theta \sin \theta \right) r \mathrm{~d} r$

$= 128 \int_{0}^{\frac{\pi}{4}} \left( \sin^{4} \theta - 2 \cos \theta \sin^{5} \theta \right) \mathrm{~d} \theta$

$= 128 \left[ \int_{0}^{\frac{\pi}{4}} \left( \frac{1 - \cos 2\theta}{2} \right)^{2} \mathrm{~d} \theta - \frac{1}{3}\sin^{6} \theta \Big|_{0}^{\frac{\pi}{4}} \right]$

$= 128 \left[ \frac{1}{4} \int_{0}^{\frac{\pi}{4}} \left( 1 - 2 \cos 2\theta + \cos^{2} 2\theta \right) \mathrm{~d} \theta - \frac{1}{24} \right]$

$= 128 \left[ \frac{1}{4} \left( \frac{\pi}{4} - \sin 2\theta \Big|_{0}^{\frac{\pi}{4}} \right) + \frac{1}{2} \int_{0}^{\frac{\pi}{2}} \cos^{2} t \mathrm{~d} t - \frac{1}{24} \right]$

$= 128 \left( \frac{3\pi}{32} - \frac{7}{24} \right)$

$= 12\pi - \frac{112}{3}$.


##### 考察知识点与难度

- **所用知识点：** 极坐标、积分区域对称性、二重积分计算、三角积分。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 区域对称和极坐标都要用到，三角积分计算较长，易出现系数错误。

#### 21

（本题满分 12 分）

设函数 $f\left( x \right)$ 在区间 $\left( a, b \right)$ 内可导，证明：导函数 $f^{\prime}\left( x \right)$ 在 $\left( a, b \right)$ 内严格单调递增的充分必要条件是：对 $\left( a, b \right)$ 内任意的 $x_{1}$，$x_{2}$，$x_{3}$，当 $x_{1} < x_{2} < x_{3}$ 时，有
$\frac{f\left( x_{2} \right) - f\left( x_{1} \right)}{x_{2} - x_{1}} < \frac{f\left( x_{3} \right) - f\left( x_{2} \right)}{x_{3} - x_{2}}$.

**解：**
必要性：由拉格朗日中值定理，存在
$\xi_{1} \in \left( x_{1}, x_{2} \right)$，$\xi_{2} \in \left( x_{2}, x_{3} \right)$，使得

$\frac{f\left( x_{2} \right) - f\left( x_{1} \right)}{x_{2} - x_{1}} = f^{\prime}\left( \xi_{1} \right)$，
$\frac{f\left( x_{3} \right) - f\left( x_{2} \right)}{x_{3} - x_{2}} = f^{\prime}\left( \xi_{2} \right)$.

由于 $f^{\prime}\left( x \right)$ 在 $\left( a, b \right)$ 内严格单调递增，且 $\xi_{1} < \xi_{2}$，故
$f^{\prime}\left( \xi_{1} \right) < f^{\prime}\left( \xi_{2} \right)$.

于是
$\frac{f\left( x_{2} \right) - f\left( x_{1} \right)}{x_{2} - x_{1}} < \frac{f\left( x_{3} \right) - f\left( x_{2} \right)}{x_{3} - x_{2}}$.

充分性：任取 $c_{1} < c_{2}$，其中 $c_{1}, c_{2} \in \left( a, b \right)$.对任意满足 $c_{1} < x < c_{2}$ 的 $x$，由题设有
$\frac{f\left( c_{1} \right) - f\left( a \right)}{c_{1} - a} < \frac{f\left( x \right) - f\left( c_{1} \right)}{x - c_{1}} < \frac{f\left( c_{2} \right) - f\left( x \right)}{c_{2} - x} < \frac{f\left( b \right) - f\left( c_{2} \right)}{b - c_{2}}$.

特别地，只需利用
$\frac{f\left( c_{1} \right) - f\left( a \right)}{c_{1} - a} < \frac{f\left( x \right) - f\left( c_{1} \right)}{x - c_{1}} < \frac{f\left( c_{2} \right) - f\left( x \right)}{c_{2} - x}$
并分别令 $x \to c_{1}^{+}$ 与 $x \to c_{2}^{-}$，得

$f^{\prime}\left( c_{1} \right) \le \frac{f\left( c_{2} \right) - f\left( c_{1} \right)}{c_{2} - c_{1}} \le f^{\prime}\left( c_{2} \right)$.

故 $f^{\prime}\left( x \right)$ 在 $\left( a, b \right)$ 上单调递增.再结合题设中的严格不等号，可排除在某子区间上恒等的情形，因此 $f^{\prime}\left( x \right)$ 在 $\left( a, b \right)$ 上严格单调递增.


##### 考察知识点与难度

- **所用知识点：** 拉格朗日中值定理、割线斜率、导函数严格单调、充要性证明。
- **难度：** ★★★★★（5/5）
- **难度说明：** 证明题的充分性最难，需要把割线斜率不等式与导函数单调性严密连接。

#### 22

（本题满分 12 分）

已知矩阵
$\boldsymbol{A} = \begin{pmatrix} 4 & 1 & -2 \\ 1 & 1 & 1 \\ -2 & 1 & a \end{pmatrix}$，
$\boldsymbol{B} = \begin{pmatrix} k & 0 & 0 \\ 0 & 6 & 0 \\ 0 & 0 & 0 \end{pmatrix}$
合同.

1. 求 $a$ 的值及 $k$ 的取值范围；
2. 若存在正交矩阵 $\boldsymbol{Q}$，使得 $\boldsymbol{Q}^{\mathrm{T}} \boldsymbol{A} \boldsymbol{Q} = \boldsymbol{B}$，求 $k$ 及 $\boldsymbol{Q}$.

**解：**
（1）因为 $\boldsymbol{A}$ 与 $\boldsymbol{B}$ 合同，所以它们有相同的惯性指标.又由 $\boldsymbol{B}$ 可知存在零特征值，因此 $\boldsymbol{A}$ 也有零特征值，从而
$\left| \boldsymbol{A} \right| = 0$.

计算得 $a = 4$.此时 $\boldsymbol{A}$ 的特征值为 $3$，$6$，$0$，故 $\boldsymbol{A}$ 有两个正特征值和一个零特征值.由合同保持惯性知 $k > 0$.

（2）若存在正交矩阵 $\boldsymbol{Q}$，使得 $\boldsymbol{Q}^{\mathrm{T}} \boldsymbol{A} \boldsymbol{Q} = \boldsymbol{B}$，则 $\boldsymbol{B}$ 是 $\boldsymbol{A}$ 的正交相似对角化结果.由于 $\boldsymbol{B}$ 的对角元已固定为 $k$，$6$，$0$，故必有 $k = 3$.

当 $a = 4$ 时，分别求特征值对应的特征向量：

当 $\lambda_{1} = 3$ 时，由 $\left( 3\boldsymbol{E} - \boldsymbol{A} \right)\boldsymbol{x} = \boldsymbol{0}$，可取
$\boldsymbol{\xi}_{1} = \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix}$.

当 $\lambda_{2} = 6$ 时，由 $\left( 6\boldsymbol{E} - \boldsymbol{A} \right)\boldsymbol{x} = \boldsymbol{0}$，可取
$\boldsymbol{\xi}_{2} = \begin{pmatrix} -1 \\ 0 \\ 1 \end{pmatrix}$.

当 $\lambda_{3} = 0$ 时，由 $\left( 0\boldsymbol{E} - \boldsymbol{A} \right)\boldsymbol{x} = \boldsymbol{0}$，可取
$\boldsymbol{\xi}_{3} = \begin{pmatrix} 1 \\ -2 \\ 1 \end{pmatrix}$.

将其单位化，得
$\boldsymbol{q}_{1} = \frac{1}{\sqrt{3}} \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix}$，
$\boldsymbol{q}_{2} = \frac{1}{\sqrt{2}} \begin{pmatrix} -1 \\ 0 \\ 1 \end{pmatrix}$，
$\boldsymbol{q}_{3} = \frac{1}{\sqrt{6}} \begin{pmatrix} 1 \\ -2 \\ 1 \end{pmatrix}$.

于是
$\boldsymbol{Q} = \left( \boldsymbol{q}_{1}, \boldsymbol{q}_{2}, \boldsymbol{q}_{3} \right) = \begin{pmatrix} \frac{1}{\sqrt{3}} & -\frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} \\ \frac{1}{\sqrt{3}} & 0 & -\frac{2}{\sqrt{6}} \\ \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} \end{pmatrix}$.


##### 考察知识点与难度

- **所用知识点：** 合同矩阵、惯性定理、正交相似对角化、特征值与标准正交特征向量。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 涉及合同与正交对角化两个层次，还要求标准正交特征向量，综合性较高。

---

## 二、2026 年考研数学二真题、解析、知识点与难度

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


##### 考察知识点与难度

- **所用知识点：** 泰勒展开、等价无穷小、待定系数。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 只需展开到二阶并比较系数，属于基础无穷小题。

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


##### 考察知识点与难度

- **所用知识点：** 非齐次线性微分方程解结构、特解线性组合、齐次解判定。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 抓住非齐次解线性组合中系数和的性质即可，计算很少。

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


##### 考察知识点与难度

- **所用知识点：** 多元隐函数求导、偏导数线性组合。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 隐函数求导直接，最后组合抵消明显，难度偏低。

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


##### 考察知识点与难度

- **所用知识点：** 万有引力微元法、对称性、定积分建模。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 物理情境下建立积分表达式，核心是竖直分量和对称性。

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


##### 考察知识点与难度

- **所用知识点：** 极值定义、单调性、凹凸性、割线斜率、反例判断。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 命题真假判断依赖定义与反例，尤其凹凸与割线斜率的方向容易混淆。

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


##### 考察知识点与难度

- **所用知识点：** 变上限积分求导、反函数求导、函数值定位。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 先定位 $g(0)$，再用反函数求导公式，步骤标准。

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


##### 考察知识点与难度

- **所用知识点：** 二重积分黎曼和、区域对称性、三角区域积分。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 既要看懂求和指标对应的区域，又要处理对称性和网格面积，辨析度高。

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


##### 考察知识点与难度

- **所用知识点：** 置换矩阵、逆矩阵、伴随矩阵、行列式符号。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 置换矩阵逆矩阵容易判断，但伴随矩阵受行列式符号影响，需细致。

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


##### 考察知识点与难度

- **所用知识点：** 矩阵方程有解条件、列空间、线性方程组。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 本质是判断 $\boldsymbol C$ 的列是否在 $\boldsymbol A$ 的列空间中，计算量中等。

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

---

### 二、填空题

`11~16` 小题，每小题 `5` 分，共 `30` 分.


##### 考察知识点与难度

- **所用知识点：** 矩阵恒等式化简、幂零矩阵、特征值与特征向量。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 先化出 $(\boldsymbol A-\boldsymbol B)^2=\boldsymbol O$，再判断特征向量结论，抽象性较强。

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


##### 考察知识点与难度

- **所用知识点：** 反常积分敛散性、无穷小比较、参数范围。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 要同时考察 $0^+$ 与 $+\infty$ 两端敛散条件，属于中等题。

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


##### 考察知识点与难度

- **所用知识点：** 泰勒展开、极限计算、等价无穷小。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 展开到二阶即可，但式子形式容易误判主导项。

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


##### 考察知识点与难度

- **所用知识点：** 隐函数求导、曲率公式、曲率半径。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 隐式求一、二阶导并代入曲率公式，计算环节较多。

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


##### 考察知识点与难度

- **所用知识点：** 全微分、偏导数、链式法则。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 全微分给出偏导数，再链式求导，整体基础。

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


##### 考察知识点与难度

- **所用知识点：** 函数平均值、定积分基本计算。
- **难度：** ★★☆☆☆（2/5）
- **难度说明：** 平均值公式直接应用，计算简单。

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

---

### 三、解答题

`17~22` 小题，共 `70` 分.解答应写出必要的文字说明、证明过程或演算步骤.


##### 考察知识点与难度

- **所用知识点：** 二次型规范形、矩阵秩、行向量成比例。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 规范形只有一项转化为秩为 $1$，再由行成比例求参，难度中等。

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


##### 考察知识点与难度

- **所用知识点：** 极坐标变换、积分区域转化、分部积分。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 极坐标区域识别不难，但径向积分需分部积分，计算量中等。

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


##### 考察知识点与难度

- **所用知识点：** 变上限积分、换元、导数定义、连续性证明。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 要先换元化简，再讨论 $x=0$ 处导数与连续性，证明过程较细。

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


##### 考察知识点与难度

- **所用知识点：** 二元函数极值、驻点、Hessian 判别法。
- **难度：** ★★★☆☆（3/5）
- **难度说明：** 常规二元极值题，偏导与二阶判别步骤明确。

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


##### 考察知识点与难度

- **所用知识点：** 拐点、旋转体体积、反常积分、定积分公式。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 集合了拐点、旋转体体积和反常积分，步骤较多且积分结果易错。

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


##### 考察知识点与难度

- **所用知识点：** 不显含 $y$ 的微分方程降阶、倒数代换、一阶线性方程、初值问题。
- **难度：** ★★★★☆（4/5）
- **难度说明：** 降阶后还要做倒数代换并结合初值，属于综合型微分方程题。

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


##### 考察知识点与难度

- **所用知识点：** 向量组极大无关组、矩阵分解 $\boldsymbol A=\boldsymbol G\boldsymbol H$、低秩矩阵幂计算。
- **难度：** ★★★★★（5/5）
- **难度说明：** 线性相关结构、低秩分解和矩阵高次幂结合，是整套题中最综合的线代题。

---

## 三、2026 年与 2025 年考研数学二难度整体对比分析

### 1. 逐题评分统计

| 年份 | 选择题平均难度 | 填空题平均难度 | 解答题平均难度 | 全卷平均难度 | 4星及以上题数 | 5星题数 |
|---|---:|---:|---:|---:|---:|---:|
| 2025 | 2.7 | 2.33 | 3.67 | 2.86 | 6 | 1 |
| 2026 | 2.8 | 2.5 | 3.83 | 3.0 | 7 | 1 |

从逐题星级看，2025 年全卷平均难度约为 **2.86 星**，2026 年全卷平均难度约为 **3.00 星**。两年都不是“极端偏难”的试卷，但 2026 年的平均难度略高，主要体现在选择题的辨析性、填空题的综合小计算，以及解答题后半部分的结构化思维要求上。

### 2. 选择题对比

2025 年选择题平均难度约为 **2.70 星**。其中基础题较多，如第 5 题换积分次序、第 6 题引力做功、第 8 题特征值符号、第 9 题初等行变换，整体比较常规。但第 7 题绝对值条件推出可导、第 10 题矩阵秩与公共解判断具有较强辨析性，是选择题中的难点。

2026 年选择题平均难度约为 **2.80 星**，略高于 2025 年。2026 年第 5 题考查极值、单调、凹凸和割线斜率之间的逻辑关系，需要用反例排除；第 7 题把二重积分、区域对称性和黎曼和结合起来；第 10 题由矩阵恒等式推出幂零矩阵性质，再判断特征值与特征向量命题。这些题目的共同特点是“会算”还不够，还要准确理解概念和命题逻辑。

### 3. 填空题对比

2025 年填空题平均难度约为 **2.33 星**，整体偏基础。第 11 题反常积分参数、第 12 题斜渐近线、第 13 题黎曼和、第 14 题参数求导都属于常规题；第 15 题齐次微分方程和第 16 题向量组通解略有综合性，但仍在常规训练范围内。

2026 年填空题平均难度约为 **2.50 星**，比 2025 年略高。第 13 题需要隐函数二阶求导并代入曲率公式，第 16 题要把二次型规范形只有一项转化为矩阵秩为 $1$，再通过行成比例求参数。这说明 2026 年填空题虽然没有出现特别复杂的大题型，但小题中对概念转换和计算稳定性的要求更高。

### 4. 解答题对比

2025 年解答题平均难度约为 **3.67 星**。其中第 17 题有理函数积分偏基础，第 19 题全微分与二元极值是常规综合题；难点主要集中在第 18 题极限反推可导、第 20 题极坐标二重积分、第 21 题证明题和第 22 题合同与正交对角化。尤其第 21 题是全卷最难题，需要严格证明导函数严格单调与割线斜率不等式之间的充要关系。

2026 年解答题平均难度约为 **3.83 星**，略高于 2025 年。第 17 题二重积分极坐标、第 19 题二元极值仍较常规；第 18 题变上限积分与导数连续性证明、第 20 题旋转体体积、第 21 题微分方程降阶、第 22 题向量组极大无关组与矩阵幂明显提高了综合性。尤其第 22 题不仅要求判断极大线性无关组，还要构造 $\boldsymbol A=\boldsymbol G\boldsymbol H$，并利用低秩分解计算 $\boldsymbol A^10$，属于结构识别和线代计算相结合的高难题。

### 5. 总结

综合逐题知识点、计算量、证明要求和易错程度来看，**2026 年考研数学二整体难度略高于 2025 年**：

- **2025 年** 的难点更集中，最突出的是第 21 题证明题和第 22 题线代综合题；基础题数量相对更多，填空题整体较温和。
- **2026 年** 的难点分布更均匀，选择题中已有较强辨析题，填空题中也有一定综合转换，解答题后四题连续考查证明、建模、微分方程和线代结构。
- 从备考角度看，2025 年更强调“常规题型熟练度 + 个别证明压轴”，2026 年更强调“概念辨析 + 多步骤计算 + 线性代数结构识别”。
