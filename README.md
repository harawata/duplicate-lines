#duplicate-lines

<p>A modified version of the duplicate_line command for Sublime Text 2<p>

<p>I wasn't happy with the way the duplicate_line command was workign in Sublime Text 2, so I made a modified version. This modified command will still duplicate a single line the same way. The behavior is slightly different, however, when duplicating *multiple* lines.</p>

<p>Rather than having to fully select the area to duplicate, you can now simply run your cursor selection over multiple lines, and this command will duplicate any lines selected, from the beginning of the first line in the selection to the end of the last line selected, and duplicate to a new line. (The original command literally duplicates from where your selection begins, to where it ends.) This also means you no longer have to select the previous line in order to duplicate to a new line. It's a small change, but if you prefer Eclipse-like behavior with this command, you'll like this.</p>

##How to use

<ol>
	<li>Download the repo and place duplicate_line.py in your *~/Library/Application Support/Sublime Text 2/Packages/User* directory</li>
	<li>Add the key binding below to your Key Bindings - User file (and bind whatever command to it that you want)</li>
</ol>

<pre><code>
{ "keys": ["super+shift+d"], "command": "duplicate_lines" }
</code></pre>

<p>Enjoy.</p>