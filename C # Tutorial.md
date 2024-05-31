---


---

<h2 id="section-2-tutorial-on-c-loops">Section 2: Tutorial on C# Loops</h2>
<h3 id="introduction-to-c-loops">Introduction to C# Loops</h3>
<p>In this tutorial, we will cover the basics of loops in C#. Loops are a fundamental concept in programming that allows you to execute a block of code multiple times.</p>
<h4 id="types-of-loops-in-c">Types of Loops in C#</h4>
<ol>
<li><strong><code>for</code> Loop</strong></li>
</ol>
<p>The <code>for</code> loop is used when you know in advance how many times you want to execute a statement or a block of statements.</p>
<pre class=" language-csharp"><code class="prism  language-csharp"><span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">int</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> i <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token punctuation">;</span> i<span class="token operator">++</span><span class="token punctuation">)</span>
<span class="token punctuation">{</span>
    Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Value of i: "</span> <span class="token operator">+</span> i<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> 
</code></pre>
<h3 id="while-loop">2. <strong><code>while</code> Loop</strong></h3>
<p>The <code>while</code> loop is used when you want to execute a statement or a block of statements as long as a condition is true.</p>
<pre class=" language-csharp"><code class="prism  language-csharp"><span class="token keyword">int</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token keyword">while</span> <span class="token punctuation">(</span>i <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token punctuation">)</span>
<span class="token punctuation">{</span>
    Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Value of i: "</span> <span class="token operator">+</span> i<span class="token punctuation">)</span><span class="token punctuation">;</span>
    i<span class="token operator">++</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</code></pre>
<h3 id="do-while-loop">3. <strong><code>do-while</code> Loop</strong></h3>
<p>The <code>do-while</code> loop is similar to the <code>while</code> loop, except that the condition is evaluated after the execution of the loop body.</p>
<pre class=" language-csharp"><code class="prism  language-csharp">
`<span class="token keyword">int</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span>
<span class="token keyword">do</span>
<span class="token punctuation">{</span>
    Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Value of i: "</span> <span class="token operator">+</span> i<span class="token punctuation">)</span><span class="token punctuation">;</span>
    i<span class="token operator">++</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span> <span class="token keyword">while</span> <span class="token punctuation">(</span>i <span class="token operator">&lt;</span> <span class="token number">10</span><span class="token punctuation">)</span><span class="token punctuation">;</span>`
</code></pre>
<h3 id="conclusion">Conclusion</h3>
<p>Loops are an essential part of C# programming that help in executing code repeatedly based on a condition. Understanding the different types of loops and when to use them is crucial for writing efficient and concise code. Practice using loops in various scenarios to solidify your understanding and improve your programming skills.</p>

