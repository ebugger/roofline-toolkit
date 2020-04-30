# CS Roofline Toolkit #

Welcome to the CS Roofline Toolkit Bitbucket site.  The Empirical Roofline Tool and Roofline Visualizer are currently available here.
In the future additional tools will be hosted here.  

For an overview of the Roofline Performance Model and this software's place in that context see
[https://crd.lbl.gov/departments/computer-science/performance-and-algorithms-research/research/roofline/](https://crd.lbl.gov/departments/computer-science/performance-and-algorithms-research/research/roofline/).

## Empirical Roofline Tool ##

The Empirical Roofline Tool, ERT, automatically generates a roofline data
for a given computer.  This includes the maximum bandwidth for the various
levels of the memory hierarchy and the maximum gflop rate.  This data is
obtained using a variety of "micro-kernels".

The ERT comes with a set of configuration files for a number of
computers/architectures.  These configuration file can be adapted to your
local environment and needs to better measure the roofline parameters of
your computer(s).

This is version 1.1.0 of the ERT -- the second public release.

For details about the ERT, please refer to the User's Manual in the
repository under the "Empirical_Roofline_Tool-1.1.0" directory.
### Use python2 and GCC7.3 with ### 
```
apt install -y gunplot 
pip install enum34

```
## Roofline Visualizer ##

The Roofline Visualizer can visualize the roofline performance data
generated locally by the ERT or stored on a remote Roofline repository.

This is version 1.1.0 of the Roofline Visualizer -- the second public release.

For details about the Roofline Visualizer, please refer to the "README.md"
file in the repository under the "Roofline_Visualizer-1.1.0" directory.

## Contact Information ##

Please contact [Charlene Yang](mailto:CJYang@lbl.gov) with any questions, problems, corrections, suggestions, etc.

## 同余式：

若正整数a和b分别对p取模的余数相同**(a%p == b%p）**，则可以记作**a≡b(modp)**，也就是a和b模p同余

## 裴蜀等式或裴蜀定理：
一个关于最大公约数（或最大公因式）的定理。说明了对任何整数a、b和m，关于未知数x和y的方程：
 
                ax+by=m
有整数解时当且仅当m是a和b的最大公约数GCD(a,b)的倍数，也就是要求GCD(a,b)|m.

裴蜀等式有解时必然有无穷多个整数解，每组解x、y都称为裴蜀数

## 模逆元：

如果a,b同余：**a≡b(modp)**, 满足 **ax≡1(modb)** 的x成为a对模数b的一个模逆元。

模逆元存在充分必要条件是a和b互素，也即GCD(a,b)=1，所以有ax+by=1。解法同上。 只是要求出x的最小正整数比较方便。



