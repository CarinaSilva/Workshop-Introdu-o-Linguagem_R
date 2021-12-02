
# Exercises 


**Exercise 1**
<br/>

**i)** Open a new folder where you are going to store your scripts and set up your working directory.


**ii)** Open a new R script file and use # to comment and organize your script.

<br/>
<br/>

**Exercise 2** Install the package _ggplot2_.
<br/>

<details><summary>Click Here to see the answer</summary><p>

```{r}
install.packages("ggplot2")
library(ggplot2)
```

</p></details>

<br/>
<br/>



**Exercise 3** Use R operators to calculate: i)  (1198/2) - $\sqrt(63)$ + 27?
<br/>

<details><summary>Click Here to see the answer</summary><p>

```{r}
1198/2-sqrt(63)+27


```

</p></details>

<br/>
<br/>

**Exercise 4**: Set _a_ equal to 7 and _b_ equal to 17 and _c_ equal to their product.
<br/>

<details><summary>Click Here to see the answer</summary><p>

```{r}
a<-7
b<-17
c<-a*b
c

```

</p></details>

<br/>
<br/>


**Exercise 5**: Type the following vector into R:
<br/>


```{r}
xx <- c(29,3,6,11,0,41,101)

```
<br/>



**a)**: Print out the 4th element of xx.
<br/>


<details><summary>Click Here to see the answer</summary><p>

```{r}
xx[4]

```

</p></details>

<br>


**b)**: What is the length of xx?

<br/>
<details><summary>Click Here to see the answer</summary><p>

```{r}
length(xx)

```

</p></details>

<br/>


**c)**: Print out the 4th and 7th elements of xx.
<br/>

<details><summary>Click Here to see the answer</summary><p>

```{r}
xx[4]

```

</p></details>

<br/>


**Exercise 6**: Look up in help the following functions: _sd()_, _min()_, _max()_ and then use these functions on the vector xx.

<br/>
<details><summary>Click Here to see the answer</summary><p>

```{r}
?sd
?min()
?max()

sd(xx)

min(xx)

max(xx)

```

</p></details>

<br/>
<br/>




**Exercise 7**: Create a function that will return the sum of 2 integers.
<br/>

<details><summary>Click Here to see the answer</summary><p>

```{r}
f.sum <- function (x, y) {
  r <- x + y
  r
}

f.sum(5, 10)

```

</p></details>

<br/>
<br/>

