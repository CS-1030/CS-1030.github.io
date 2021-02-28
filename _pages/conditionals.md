---
layout: default
title: Conditionals
---

# Conditionals
{: .no_toc }
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Description
Conditionals allow our programs to make choices based on the result of analyzing certain information. In more technical terms, conditionals execute alternate sets of code (branches) based on the evaluation of a boolean expression.
- Conditionals are a control structure. It directs the order of execution of program statements.
- Python Docs: [if Statments](https://docs.python.org/3/tutorial/controlflow.html#if-statements), [The if statement](https://docs.python.org/3/reference/compound_stmts.html#if), [Truth Value Testing](https://docs.python.org/3/library/stdtypes.html#truth-value-testing)
{% highlight Python %}
if (boolean-expression):
    execute_this_code_block
elif (boolean-expression):
    execute_this_other_code
else:
    execute_this
{% endhighlight %}

## if/else Statements
The `if` keyword, followed by a boolean expression, is used to start a conditional statement. If the boolean expression is `True`, the code indented under the `if` statement will execute. 
Optionally, an `else` statement can be included. The code indented under the `else` will only execute when the `if`'s boolean expression evaluates to `False`.
<iframe height="400px" width="100%" src="https://repl.it/@bianca_ruiz/simpleIfTaco?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
## elif Statements
<iframe height="400px" width="100%" src="https://repl.it/@bianca_ruiz/elifTaco?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
#### Compound if Statement
<iframe height="400px" width="100%" src="https://repl.it/@bianca_ruiz/compoundIfTaco?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>


## Section

