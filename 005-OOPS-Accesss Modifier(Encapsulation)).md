## Types

<div class="w3-responsive" style="margin:-16px 0;">
<table class="w3-table-all notranslate">
<tbody>
<tr>
<th style="width:22%">Modifier</th>
<th style="width:78%">Description</th>
</tr>
<tr>
<td><code class="w3-codespan">public</code></td>
<td>The code is accessible for all classes</td>
</tr>
<tr>
<td><code class="w3-codespan">private</code></td>
<td>The code is only accessible within the same class</td>
</tr>
<tr>
<td><code class="w3-codespan">protected</code></td>
<td>The code is accessible within the same class, or in a class that is 
inherited from that class. You will learn more about <a href="cs_inheritance.asp">inheritance</a> in a later chapter</td>
</tr>
<tr>
<td><code class="w3-codespan">internal</code></td>
<td>The code is only accessible within its own assembly, but not from another assembly. 
You will learn more about this in a later chapter</td>
</tr>
</tbody>
</table>
</div>

Why Access Modifiers?
To control the visibility of class members (the security level of each individual class and class member).

To achieve 
```python
Encapsulation```
 - which is the process of making sure that "sensitive" data is hidden from users. This is done by declaring fields as private. You will learn more about this in the next chapter.

Note: By default, all members of a class are private if you don't specify an access modifier:
