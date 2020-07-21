---
layout: post
title:  "Measurements, Uncertainty, and Significant Figures"
date:   2020-01-17 22:49:53 +0800
category: phys81
---

**Fundamental Quantities** are quantities/units independent of other physical quantities.

The 7 Fundamental quantities are

1. time (second/s)
2. length (meter/m)
3. mass (kilogram/kg)
4. electric current (ampere/A)
5. thermodynamic temperature (kelvin/K)
6. amount of substance (mole/mol)
7. luminous intensity (candela/cd)



**Derived Quantities** are those that may be expressed in terms of fundamental or other derived quantities.



### Example Problems

#### 1.20

Four astronauts are in a spherical space station. **(a)** If, as is typical, each of them breathes about $500cm^{3}$ of air with each breath, approximately what volume of air (in cubic meters) do these astronauts breathe in a year? **(b)** What would the diameter (in meters) of the space station have to be to contain all this air?



**(a)** Convert $cm^{3}$ to $m^{3}$
$$
\begin{align*} 
&= 500cm^{3} \times \left(\frac{1\times 10^{-2}m }{1cm}\right)^{3}\\
&= 500 \times 10^{-6}m^{3}\\
&= 5 \times 10^{-4}m^{3}
\end{align*}
$$
Assuming $4s/breath$
$$
\begin{align*} 
&= \frac{\text{volume of breath}}{time}\\
&= 5\times 10^{-4}\frac{m^{3}}{s}\times \frac{breath}{4s}\\
&= 1.25\times 10^{-4}\frac{m^{3}}{s}
\end{align*}
$$
Now calculate **volume in 1 year per astronaut**
$$
\begin{align*} 
&= 1.25\times 10^{-4}\frac{m^{3}}{s}\times 1yr \times \frac{365days}{1yr}\times \frac{24hours}{1day}\times \frac{60min}{1hr}\times \frac{60s}{1min}\\
&= 3944.7 \frac{m^{3}}{astronaut}
\end{align*}
$$
The **total volume** is 
$$
3994.7\frac{m^{3}}{astronaut}\times 4 \quad astronauts = 15778.8m^{3}\approx 16000m^{3}
$$


**(b)** Lastly calculate the **diameter**
$$
\begin{align*} 
V_{sphere}&= \frac{4}{x}\pi \frac{d}{2}^{3}
\\16000m^{3}&= \frac{1}{6}\pi d^{3} 
\end{align*}
$$
Solve in terms of **d** gives you 
$$
\begin{align*} 
d &= 31.26m\\ 
&\approx 30m
\end{align*}
$$


#### 1.12

**(a)** The recommended daily allowance (RDA) of the trace metal magnesium is $410mg/day$ for males. Express this quantity in $\mu/day$ .
$$
\begin{align*} 
&= 410\frac{mg}{day}\cdot \frac{1\mu g}{1\times 10^{-6}g}\cdot \frac{1\times 10^{-3}g}{1mg}\\
&= \frac{410000\mu g}{day}\\
&= \frac{4.1\times 10^{5}\mu g}{day}
\end{align*}
$$


 **(b)** For adults, the RDA of the amino acid lysine is 12 mg per kg of body weight. How many grams per day should a 75-kg adult receive? 
$$
\begin{align*} 
&= 12 \frac{mg}{kg}\cdot \frac{1\times 10^{-3}g}{1mg}\cdot 75kg\\
&= 9.0\times 10^{-1}g
\end{align*}
$$

**(c)** A typical multivitamin tablet can contain 2.0 mg of vitamin $B_{2}$ (riboflavin), and the RDA is $0.0030g/day$. How many such tablets should a person take each day to get the proper amount of this vitamin, assuming that he gets none from any other sources?
$$
\begin{align*} 
&= 2mg \cdot  \frac{1\times 10^{-3}g}{1mg} \cdot \frac{1tab}{0.0030\frac{g}{day}}\\
&= 1.5 \quad tablet / day
\end{align*}
$$


 **(d)** The RDA for the trace element selenium is $0.000070g/day$. Express this dose in $mg/day$.
$$
\begin{align*} 
&= 7.0\times 10^{-5} \frac{g}{day}\cdot \frac{1mg}{1\times 10^{-3}g}\\
&\approx 0.07 \frac{mg}{day}
\end{align*}
$$

#### 8

A certain compact disc contains 783.216 megabytes of digital information. Each byte consits of exactly 8 bits. When played, a CD player reads the CD's information at a constant rate of 1.4 megabits per second. How many minutes does it take the player to read the entire CD?
$$
\begin{align*} 
&= 783.216megabytes \times \frac{byte}{8bits} \times \frac{s}{1.4megabits} \times \frac{1min}{60s}\\
&\approx 75 mins 
\end{align*}
$$

### [Quiz 1 answers](quiz1.md)
