<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

## Vim Quick Reference Guide

**Modes**

- **Normal**: Navigation and commands (default mode)
- **Insert**: Text entry (`i`, `a`, `I`, `A`, `o`, `O`)
- **Visual**: Selection (`v` for character, `V` for line, `&lt;C-v&gt;` for block)
- **Command-Line**: Commands like save, quit, search (`:`)

---

**Navigation**

- `h`/`j`/`k`/`l`: Left/Down/Up/Right
- `gg` / `G`: First/Last line
- `nG` or `:n`: Go to line n
- `0` / `$`: Start/End of line
- `^`: First non-blank character of line
- `w` / `b`: Next/Previous word
- `e` / `ge`: End of next/previous word
- `%`: Matching parenthesis/bracket/brace
- `H`/`M`/`L`: Top/Middle/Bottom of screen[^2][^4][^5]

---

**Basic Editing**

- `i` / `a`: Insert before/after cursor
- `I` / `A`: Insert at start/end of line
- `o` / `O`: New line below/above
- `r`: Replace one character
- `x`: Delete character under cursor
- `dd`: Delete (cut) line
- `dw`: Delete word
- `D`: Delete to end of line
- `yy`: Yank (copy) line
- `p` / `P`: Paste after/before cursor
- `u`: Undo
- `&lt;C-r&gt;`: Redo
- `J`: Join with next line[^2][^4][^5]

---

**Visual Mode**

- `v`: Start visual (character) mode
- `V`: Visual line mode
- `&lt;C-v&gt;`: Visual block mode
- `ggVG`: Select all
- `&gt;` / `&lt;`: Indent right/left[^5]

---

**Search and Replace**

- `/pattern`: Search forward
- `?pattern`: Search backward
- `n` / `N`: Next/Previous match
- `:%s/old/new/g`: Replace all
- `:%s/old/new/gc`: Replace all with confirmation
- `:noh`: Remove search highlight[^4]

---

**File Operations**

- `:w`: Save
- `:q`: Quit
- `:wq` or `ZZ`: Save and quit
- `:q!`: Quit without saving
- `:e filename`: Open file
- `:bn` / `:bp`: Next/Previous buffer[^2][^4]

---

**Macros and Repeats**

- `.`: Repeat last change
- `q{a-z}`: Start recording macro into register
- `q`: Stop recording macro
- `@{a-z}`: Execute macro[^5]

---

**Tabs and Windows**

- `:tabnew filename`: Open file in new tab
- `gt` / `gT`: Next/Previous tab
- `:split filename` / `:vsplit filename`: Horizontal/Vertical split
- `&lt;C-w&gt;h/j/k/l`: Move between splits[^4]

---

**Advanced**

- `:set nu`: Show line numbers
- `:syntax on`: Enable syntax highlighting
- `:map` / `:unmap`: Key mappings
- `:ab`: Abbreviations[^1]

---

**Tips**

- Use `Esc` to return to Normal mode.
- Prefix commands with a number to repeat (e.g., `5dd` deletes 5 lines).
- Combine navigation and editing for efficiency (e.g., `d2w` deletes two words).

---

This guide covers the essential Vim commands for efficient navigation, editing, and automation, ideal for quick reference by engineers and power users[^2][^4][^5].

<div style="text-align: center">⁂</div>

[^1]: https://users.ece.utexas.edu/~adnan/vimqrc.html

[^2]: https://www.cs.cmu.edu/~15131/f17/topics/vim/vim-cheatsheet.pdf

[^3]: https://opensource.com/article/19/3/getting-started-vim

[^4]: https://vim.rtorr.com

[^5]: https://quickref.me/vim.html

[^6]: https://monovm.com/blog/vim-shortcuts/

[^7]: https://michaelgoerz.net/refcards/vimqrc.pdf

[^8]: https://devhints.io/vim

[^9]: https://www.interviewbit.com/vim-cheat-sheet/

[^10]: https://www.linuxfoundation.org/blog/blog/classic-sysadmin-vim-101-a-beginners-guide-to-vim

[^11]: https://www.tutorialspoint.com/vim/vim_quick_guide.htm

[^12]: https://www.phcomp.co.uk/Tutorials/Unix-And-Linux/Vi-and-vim-reference-sheet.html

[^13]: https://phoenixnap.com/kb/vim-commands-cheat-sheet

[^14]: https://www.youtube.com/watch?v=ggSyF1SVFr4

[^15]: https://www.reddit.com/r/vim/comments/ozdyeu/ultimate_vim_keyboard_shortcuts_new_comprehensive/

[^16]: https://w3.cs.jmu.edu/bernstdh/web/common/help/vim.php

[^17]: https://www.pluralsight.com/resources/blog/cloud/a-vim-cheat-sheet-reference-guide

[^18]: https://vimdoc.sourceforge.net/htmldoc/quickref.html

[^19]: https://learnbyexample.github.io/vim_reference/Introduction.html

[^20]: https://gist.github.com/azadkuh/5d223d46a8c269dadfe4

