# Structured-Text-Programming

<br>
Begin the program
<br>
<code>
    PROGRAM
</code>
<br>

<br>
End the program
<br>
<code>
    END_PROGRAM
</code>
<br>

<br>
Program extructure
<br>
<code>
    PROGRAM<br>
      // PLC Program<br>
    END_PROGRAM
</code>
<br>

<br>
1 line comment
<br>
<code>
    // comment
</code>
<br>

<br>
1 line comment
<br>
<code>
    <statement>; /* comment */
</code>
<br>

<br>
1 line comment
<br>
<code>
    <statement>; (* comment *)
</code>
<br>

<br>
Multi-line comment
<br>
<code>
    /* multi-line
    comment */
</code>
<br>

<br>
Multi-line comment
<br>
<code>
    (* multi-line
    comment *)
</code>
<br>

<br>
Variables declaration scope
<br>
<code>
    VAR
        myVar : INT;
        myVar2 : REAL;
        myVar3 : STRING[255];
        myVar4 : BOOL;
    END_VAR
</code>
<br>

<br>
Constants declaration scope
<br>
<code><pre>
    CONSTANT
        myConstant : INT := 10;
        myConstant2 : REAL := 10.2;
    END_VAR
</pre></code>
<br>

## IF  
<pre><code>
    IF condition THEN  
        action;    
    END_IF;  
</code></pre>  
  
## IF/ELSE  
<pre><code>
    IF condition THEN  
        action1;    
    ELSE  
        action2;
    END_IF;  
</code></pre>  
  
## IF/ELSE IF/ELSE  
<pre><code>
    IF condition1 THEN  
        action1;    
    ELSIF condition2 THEN  
        action2;    
    ELSE
        action3;
    END_IF;  
</code></pre> 

## WHILE  
<pre><code>
    WHILE condition DO  
        action;    
    END_WHILE;  
</code></pre>  
  
## REPEAT  
<pre><code>
    REPEAT  
        action;    
    UNTIL condition END_REPEAT;  
</code></pre>  
  
## EXIT  
<pre><code>
    EXIT;  
</code></pre>  
  
## RETURN  
<pre><code>
    RETURN;  
</code></pre>  
  
