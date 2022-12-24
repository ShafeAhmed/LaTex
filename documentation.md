#**LaTex documentation**

##Lists and nested lists
###lists

```LaTex
{
    \begin{enumerate}

    \end{enumerate}
}
```

#nested lists

```LaTex
{
    \begin{enumerate}
   \item Functions and Graphs
        \begin{enumerate}
            \items Basic classes of functions
                \begin{enumerate}
                    \item Linear
                    \item polynomials
                    \item Algebraic
                    \item piece-wise defined
                    \item Transcendentals
                    \item power
                \end{enumerate}
            \item function transformations
            \item Inverse functions
            \item Trigonometric functions
            \item Exponential functions
            \item Logarithm functions
            \items
        \end{enumerate}
   \item Limits and derivatives
    \begin{enumerate}
        \item Second level item
        \item Second level item
            \begin{enumerate}
            \item Third level item
            \item Third level item
                \begin{enumerate}
                    \item Fourth level item
                    \item Fourth level item
                \end{enumerate}
            \end{enumerate}
    \end{enumerate}
 \end{enumerate}
}
```

#comments

```LaTex
{
    \begin{comments}
    This is comments
    \end{comments}
}
```
