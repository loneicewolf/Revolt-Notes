# Re-Volt Basic Formatting 
Note: Revolt uses latex so!

# Colors
```
# $\color{pink}\textsf{abc}$
# $\color{green}\textsf{abc}$
# $\color{red}\textsf{abc}$
# $\color{yellow}\textsf{abc}$
# $\color{blue}\textsf{abc}$
# $\color{cyan}\textsf{abc}$

```

# Re Create that list, but in bash!

- filename: `revolt_snippets.sh` 
```sh
msg="abc"
for color in {red,green,blue,orange,cyan,purple,pink};do echo "$\\color{$color}\\textsf{$msg}$"; done
```

# Output
```
$\color{red}\textsf{abc}$
$\color{green}\textsf{abc}$
$\color{blue}\textsf{abc}$
$\color{orange}\textsf{abc}$
$\color{cyan}\textsf{abc}$
$\color{purple}\textsf{abc}$
$\color{pink}\textsf{abc}$
```

# Same with Greek Letters
`for a in {alpha,beta,gamma,lambda,pi,phi};do echo "$\\$a$" | tr '\n' ' '; done `

# Output: when copy pasted: `α β γ λ π ϕ`




