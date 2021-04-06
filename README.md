# Structured-Text-Programming

  
Begin the program
<pre><code>
    PROGRAM
</code></pre> 
  
End the program  
<pre><code>
    END_PROGRAM
</code></pre> 
  
Program extructure
<pre><code>
    PROGRAM<br>
      // PLC Program<br>
    END_PROGRAM
</code></pre> 
  
1 line comment  
<pre><code>
    // comment
</code></pre> 
  
1 line comment
<pre><code>
    <statement>; /* comment */
</code></pre> 
    
1 line comment
<pre><code>
    <statement>; (* comment *)
</code></pre> 
  
Multi-line comment
<pre><code>
    /* multi-line
    comment */
</code></pre> 
  
Multi-line comment
<pre><code>
    (* multi-line
    comment *)
</code></pre> 
  
Variables declaration scope
<pre><code>
    VAR
        myVar : INT;
        myVar2 : REAL;
        myVar3 : STRING[255];
        myVar4 : BOOL;
    END_VAR
</code></pre> 
  
Constants declaration scope
<pre><code>
    CONSTANT
        myConstant : INT := 10;
        myConstant2 : REAL := 10.2;
    END_VAR
</code></pre> 
  
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

## CASE  
<pre><code>
    CASE status OF  
        1:
            action1;
        2:
            action2;    
    END_CASE;  
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
  
