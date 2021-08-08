# Python_Course

  <br>
<h6>Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. ... Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance.</h6>

<h6>Guido van Rossum began working on Python in the late 1980s, as a successor to the ABC programming language, and first released it in 1991 as Python 0.9.0.</h6>

<h6>Python consistently ranks as one of the most popular programming languages.</h6>


  <br>

<table class="wikitable">
  <caption display=table-caption text-align=-webkit-center><b>Summary of Python 3's built-in types</b>
</caption>
<tbody><tr>
<th>Type
</th>
<th><a href="/wiki/Immutable_object" title="Immutable object">Mutability</a>
</th>
<th>Description
</th>
<th style="width: 23em;">Syntax examples
</th></tr>
<tr>
<td><code>bool</code>
</td>
<td>immutable
</td>
<td><a href="/wiki/Boolean_value" class="mw-redirect" title="Boolean value">Boolean value</a>
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="kc">True</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="kc">False</span></code>
</td></tr>
<tr>
<td><code>bytearray</code>
</td>
<td>mutable
</td>
<td>Sequence of <a href="/wiki/Byte" title="Byte">bytes</a>
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">bytearray</span><span class="p">(</span><span class="sa">b</span><span class="s1">'Some ASCII'</span><span class="p">)</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">bytearray</span><span class="p">(</span><span class="sa">b</span><span class="s2">"Some ASCII"</span><span class="p">)</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">bytearray</span><span class="p">([</span><span class="mi">119</span><span class="p">,</span> <span class="mi">105</span><span class="p">,</span> <span class="mi">107</span><span class="p">,</span> <span class="mi">105</span><span class="p">])</span></code>
</td></tr>
<tr>
<td><code>bytes</code>
</td>
<td>immutable
</td>
<td>Sequence of bytes
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="sa">b</span><span class="s1">'Some ASCII'</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="sa">b</span><span class="s2">"Some ASCII"</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">bytes</span><span class="p">([</span><span class="mi">119</span><span class="p">,</span> <span class="mi">105</span><span class="p">,</span> <span class="mi">107</span><span class="p">,</span> <span class="mi">105</span><span class="p">])</span></code>
</td></tr>
<tr>
<td><code>complex</code>
</td>
<td>immutable
</td>
<td><a href="/wiki/Complex_number" title="Complex number">Complex number</a> with real and imaginary parts
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="mi">3</span><span class="o">+</span><span class="mf">2.7</span><span class="n">j</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="mi">3</span> <span class="o">+</span> <span class="mf">2.7</span><span class="n">j</span></code>
</td></tr>
<tr>
<td><code>dict</code>
</td>
<td>mutable
</td>
<td><a href="/wiki/Associative_array" title="Associative array">Associative array</a> (or dictionary) of key and value pairs; can contain mixed types (keys and values), keys must be a hashable type
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">{</span><span class="s1">'key1'</span><span class="p">:</span> <span class="mf">1.0</span><span class="p">,</span> <span class="mi">3</span><span class="p">:</span> <span class="kc">False</span><span class="p">}</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">{}</span></code>
</td></tr>
<tr>
<td><code>ellipsis</code><sup class="reference plainlinks nourlexpansion" id="ref_inaccessible-type"><a href="#endnote_inaccessible-type">a</a></sup>
</td>
<td>immutable
</td>
<td>An <a href="/wiki/Ellipsis_(programming_operator)" class="mw-redirect" title="Ellipsis (programming operator)">ellipsis</a> placeholder to be used as an index in <a href="/wiki/NumPy" title="NumPy">NumPy</a> arrays
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="o">...</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="bp">Ellipsis</span></code>
</td></tr>
<tr>
<td><code>float</code>
</td>
<td>immutable
</td>
<td><a href="/wiki/Double-precision_floating-point_format" title="Double-precision floating-point format">Double-precision</a> <a href="/wiki/Floating-point_arithmetic" title="Floating-point arithmetic">floating-point number</a>. The precision is machine-dependent but in practice is generally implemented as a 64-bit <a href="/wiki/IEEE_754" title="IEEE 754">IEEE 754</a> number with 53 bits of precision.<sup id="cite_ref-100" class="reference"><a href="#cite_note-100">[100]</a></sup>
</td>
<td>
<p><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="mf">1.414</span></code>
</p>
</td></tr>
<tr>
<td><code>frozenset</code>
</td>
<td>immutable
</td>
<td>Unordered <a href="/wiki/Set_(computer_science)" class="mw-redirect" title="Set (computer science)">set</a>, contains no duplicates; can contain mixed types, if hashable
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">frozenset</span><span class="p">([</span><span class="mf">4.0</span><span class="p">,</span> <span class="s1">'string'</span><span class="p">,</span> <span class="kc">True</span><span class="p">])</span></code>
</td></tr>
<tr>
<td><code>int</code>
</td>
<td>immutable
</td>
<td><a href="/wiki/Integer_(computer_science)" title="Integer (computer science)">Integer</a> of unlimited magnitude<sup id="cite_ref-pep0237_101-0" class="reference"><a href="#cite_note-pep0237-101">[101]</a></sup>
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="mi">42</span></code>
</td></tr>
<tr>
<td><code>list</code>
</td>
<td>mutable
</td>
<td><a href="/wiki/List_(computer_science)" class="mw-redirect" title="List (computer science)">List</a>, can contain mixed types
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">[</span><span class="mf">4.0</span><span class="p">,</span> <span class="s1">'string'</span><span class="p">,</span> <span class="kc">True</span><span class="p">]</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">[]</span></code>
</td></tr>
<tr>
<td><code>NoneType</code><sup class="reference plainlinks nourlexpansion" id="ref_inaccessible-type"><a href="#endnote_inaccessible-type">a</a></sup>
</td>
<td>immutable
</td>
<td>An object representing the absence of a value, often called <a href="/wiki/Null_pointer" title="Null pointer">null</a> in other languages
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="kc">None</span></code>
</td></tr>
<tr>
<td><code>NotImplementedType</code><sup class="reference plainlinks nourlexpansion" id="ref_inaccessible-type"><a href="#endnote_inaccessible-type">a</a></sup>
</td>
<td>immutable
</td>
<td>A placeholder that can be returned from <a href="/wiki/Operator_overloading" title="Operator overloading">overloaded operators</a> to indicate unsupported operand types.
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="bp">NotImplemented</span></code>
</td></tr>
<tr>
<td><code>range</code>
</td>
<td>immutable
</td>
<td>A Sequence of numbers commonly used for looping specific number of times in <code>for</code> loops<sup id="cite_ref-102" class="reference"><a href="#cite_note-102">[102]</a></sup>
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">range</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="mi">10</span><span class="p">)</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">range</span><span class="p">(</span><span class="mi">10</span><span class="p">,</span> <span class="o">-</span><span class="mi">5</span><span class="p">,</span> <span class="o">-</span><span class="mi">2</span><span class="p">)</span></code>
</td></tr>
<tr>
<td><code>set</code>
</td>
<td>mutable
</td>
<td>Unordered <a href="/wiki/Set_(computer_science)" class="mw-redirect" title="Set (computer science)">set</a>, contains no duplicates; can contain mixed types, if hashable
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">{</span><span class="mf">4.0</span><span class="p">,</span> <span class="s1">'string'</span><span class="p">,</span> <span class="kc">True</span><span class="p">}</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="nb">set</span><span class="p">()</span></code>
</td></tr>
<tr>
<td><code>str</code>
</td>
<td>immutable
</td>
<td>A <a href="/wiki/String_(computer_science)" title="String (computer science)">character string</a>: sequence of Unicode codepoints
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="s1">'Wikipedia'</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="s2">"Wikipedia"</span></code><br><div class="mw-highlight mw-highlight-lang-python mw-content-ltr" dir="ltr"><pre><span></span><span class="sd">"""Spanning</span>
<span class="sd">multiple</span>
<span class="sd">lines"""</span>
</pre></div>
</td></tr>
<tr>
<td><code>tuple</code>
</td>
<td>immutable
</td>
<td>Can contain mixed types
</td>
<td><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">(</span><span class="mf">4.0</span><span class="p">,</span> <span class="s1">'string'</span><span class="p">,</span> <span class="kc">True</span><span class="p">)</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">(</span><span class="s1">'single element'</span><span class="p">,)</span></code><br><code class="mw-highlight mw-highlight-lang-python mw-content-ltr" id="" style="" dir="ltr"><span class="p">()</span></code>
</td></tr></tbody></table>
  
  <br>

  <h6>^a Not directly accessible by name</h6>
