#NekoMathLibs

##Outline of this Repository

This is a Java library for Mathematics.
I made this library to study programming.

##Usage
* Import this package. 

```java
import NekoMathLibs.*;
```

* Solve the quadratic equation.

```java
QuadSolver [NAME_OF_INSTANCE] = new QuadSolver([DOUBLE_A], [DOUBLE_B], [DOUBLE_C]);
```

###Variables of Instances

```java
public double a, b, c; // Coefficients of the equation
public double discriminant; // Value of the discriminant
public int ansType; // The type of the answer
public double pAns1; // One of the solutions of the real number
public double pAns2; // Another solution of the real number
public double nAnsRe; // Real part of the imaginary number
public double nAnsIm; // The imaginery part
```

###The Type of the Answer

* D > 0 (D := the Discriminant)

```java
ansType == 0;
```

* D = 0

```java
ansType == 1;
```

* D < 0

```java
ansType == 2;
```

* a = 0 (Solutions not Found)

```java
ansType == -1;
```

##License
Undefined.