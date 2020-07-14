# LaTeX Snippets for VS Code
These are Visual Studio Code snippets to be used in conjunction with my LaTeX templates package [hrftex](https://github.com/r0uv3n/hrftex) 
and [LaTeX-Workshop for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop). 
Fork (or just download) these into "%AppData%\Code\User\snippets" (or "%AppData%\Code - Insiders\User\snippets" if you are using Visual Studio Code - Insiders).

## Further tips and tricks
At least for me, the suggestions provided by VS Code are one of the most important parts of my workflow. While working for example on my AGLA lecture notes, I can type "Vektorr" and I will automatically get the suggestions "Vektorraum" and "Vektorräume". If I am a bit more clever about this, I can type in "Vea" to get only the "Vektorraum" suggestion, and I can type in "Veä" to get only the "Vektorräume" suggestion. This works, because the editor does not have any other words containing these letters in the same order. This is also the reason why I will nearly always always fully type out all command names, avoiding abbreviations: I can just use this feature to minimize typing work, while (through the verbose names) still maximising clarity in my .tex files. 

There is one exceptions to this: Initially, I used "\parens" paired delimiters (from mathtools) for parantheses (I even debated using "\parentheses"), but later I switched to "\p", because the many "\parens" cluttered the .tex files, actually *hindering* reading comprehension. I have however not seen any reason to do this for any other commands.
