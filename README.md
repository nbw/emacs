# Emacs

Document what libraries I use, what I know, and what I want to learn about Emacs.

# Basic things

- [ ] How do you create a file?
- [ ] How do you access console?
- [ ] How do you cancel?
      Answer: `C-g`
- [ ] Multiple working panes?
- [ ] How to comment out multiple lines?
- [ ] Equivalent of Tim Pope's surround
- [x] How to open previous file?
    Answer: One way is using the buffer `C-x b` (hit tab for a list of autocompletes)  

    Answer: `C-x left` or `C-x right`
- [ ] How to show the line number?
- [ ] Change the color of my cursor? 
- [x] Search locally in a file?
    Answer: 'C-s' to search forward, then `C-s` for next and `C-r` for previous. There's also functionality to search backwards `C-r` but it might be overridden by EVIL
- [x] Find and replace?
    Answer: `M-%`, `space` for yes, `n` for no, `!` for all 
- [x] Wrap text
    Answer: `M-q`


# Emacs stuff
- [ ] How do I write and use a macro?
- [ ] Help?
    Answer: there's `C-h C-h` for a list, but `C-h k` is more usefull for looking up a command or character

# Basic Commands
- a good list, [here](http://www.jesshamrick.com/2012/09/10/absolute-beginners-guide-to-emacs/)

# Want
- [ ] Setup C-tags, more [here](https://www.emacswiki.org/emacs/BuildTags#toc3)
- [ ] Have autocomplete
- [ ] How to run something Async
- [ ] Elixir Auto format on save
- [ ] Git integration (magit?)
- [x] Markdown formatter
	Answer: markdown mode
- [x] Disable toolbar on startup
	Answer: 
	```
	;; Remove the toolbar
	(tool-bar-mode -1)

	;; Remove Scroll bars
	(scroll-bar-mode -1)
	```

# Libraries worth mentioning

- [x] Not a lib, but _Evil Mode_ is a must
- [ ] Something for file search
- [ ]
