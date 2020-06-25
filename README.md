# 108trigo - Further Fiddling with Fancy Fundamental Functions

- **Binary name:** 108trigo
- **Repository name:** 108trigo_2019
- **Repository rigths:** ramassage-tek
- **Language:** everything working on "the dump"
- **Choosed language:** C
- **Compilation:** via Makefile, including re, clean and fclean rules


# Subject

As you may know (or not), the exponential function can be written as the sum of a power series.
So does many other functions, such as trigonometric and hyperbolic functions.

These power series are extremely handy when it comes to fast approximations of all those functions. But they can also be used to exponentiate (for instance) mathematical objects (as long as they can be elevated to integer powers). One could for example compute the cosine of a function, the exponentiation of a graph, the hyperbolic tangent of a rotation or the sine of a square matrix (which is what you will do here). . .

Given a matrix and the name of a function, your program must apply the latter to the former, and print the
result

> :speaking_head: Matrices are given as arguments line by line.

> :loudspeaker:	Obviously, matrix-managing libraries are not allowed. Hopefully, you already wrote efficient functions to compute matrix powers!

## Nao Marvin

| Details      | Nao Marvin :robot: (%) |
| ------------- |:-------------:|
| `rigor`: 100% \| `basic`: 100% \| `cosine`: 100% \| `exponential`: 100% \| `hyperbolic cosine`: 100% \| `hyperbolic sine`: 100% \| `sine`: 100% | 100% |

## Prerequisites

What you need

```
GlibC
gcc
make
```

## Compiling

Clone the repository and go inside. Then,

```
$ make
```

## Usage

```
~/B-MAT-200> ./108trigo fun a0 a1 a2 ...
```
- **fun:** function to be applied, among at least “EXP”, “COS”, “SIN”, “COSH” and “SINH”
- **ai:** coeficients of the matrix

## Examples

```
∼/B-MAT-200> ./108trigo COS 4 5 9 3 3 5 0 1 9
0.70 -0.43 -1.94
-0.16 0.67 -1.23
-0.06 -0.15 0.07
```

```
∼/B-MAT-200> ./108trigo EXP 1 2 3 4
51.97 74.74
112.10 164.07
```

```
∼/B-MAT-200> ./108trigo SINH 1 0 2 0
1.18 0.00
2.35 0.00
```

> :bulb: Coefficients are split by tabulations.

> :bulb: Mind the float numbers precision!