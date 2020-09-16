# Working With Files
The File class from the System.IO namespace, allows us to work with files:
```python
Example
using System.IO;  // include the System.IO namespace

File.SomeFileMethod();  // use the file class with methods
```
The File class has many useful methods for creating and getting information about files. For example:
<div class="w3-responsive" style="margin:-16px 0;">
<table class="w3-table-all notranslate">
<tbody>
<tr>
<th style="width:25%">Method</th>
<th style="width:60%">Description</th>
</tr>
<tr>
<td><code class="w3-codespan">AppendText()</code></td>
<td>Appends text at the end of an existing file</td>
</tr>
<tr>
<td><code class="w3-codespan">Copy()</code></td>
<td>Copies a file</td>
</tr>
<tr>
<td><code class="w3-codespan">Create()</code></td>
<td>Creates or overwrites a file</td>
</tr>
<tr>
<td><code class="w3-codespan">Delete()</code></td>
<td>Deletes a file</td>
</tr>
<tr>
<td><code class="w3-codespan">Exists()</code></td>
<td>Tests whether the file exists</td>
</tr>
<tr>
<td><code class="w3-codespan">ReadAllText()</code></td>
<td>Reads the contents of a file</td>
</tr>
<tr>
<td><code class="w3-codespan">Replace()</code></td>
<td>Replaces the contents of a file with the contents of another file</td>
</tr>
<tr>
<td><code class="w3-codespan">WriteAllText()</code></td>
<td>Creates a new file and writes the contents to it. If the file already exists, it will be overwritten.</td>
</tr>
</tbody>
</table>
</div>
