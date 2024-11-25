# Mission Statement?

The goal of this vault is for me to do some learning in public.  I want to post this to Github and either use git submodules to pull some files out of the vault posted to github.

# Minimum Viable Product

`/InterstitialJournal` should be a separate git submodule.
`/Codenames` should be a seperate git submodule.

the `nix-config` repo should configure these repos. so that

```
willworks:
	will:
		ij: true
		codenames: false
willsm1:
	will:
		ij:true
		codenames: true
	games:
		ij:true
		codenames: true
	eagles:
		ij: false
		codenames: false
```

Eagles needs a seperate "IJ" repo that I can keep off screen when streaming.

# Future Ideas

- [ ] stop using obsidian, start using neovim.
- [ ] Better navigation:
      stop using calendar-nav.
      Link to previous note.
      Link to yesterday unless previous note is yesterday
      Tomorrow
      Next note unless next note is tomorrow
- [ ] Dataview tag to redact lines.
- [ ] Dataview tag to enable redact begin and end
- [ ] Dataview tag when wrapped in parentheses redacts contents