Importing the repository locally
========================
1.create directory with prefered name
-----------------------
```
    mkdir <DIR NAME>
```
2.initialize repository
----------------
```
    git init
```

3.add remote Github remote repository
--------------------------
```
    git remote add origin git@github.com:ShafeAhmed/LaTex.git
```
4.verify remote repository
-------------------------
```
    git remote -v
```
it should display:
-------------------
```
    origin	git@github.com:ShafeAhmed/LaTex.git (fetch)
    origin	git@github.com:ShafeAhmed/LaTex.git (push)
```
Trouble Shooting resources
=================================
Github documentation:
>>[https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github "Title").




***LaTex documentation***
===============================

##Lists and nested lists
lists
-------

```LaTex
{
    \begin{enumerate}

    \end{enumerate}
}
```

nested lists
----------

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
 \end{enumerate}
}
```

comments
---------

```LaTex
{
    \begin{comments}
    This is comments
    \end{comments}
}
```
