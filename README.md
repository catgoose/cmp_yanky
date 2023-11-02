<!-- LTeX: enabled=false -->
# cmp_yanky
<!-- LTeX: enabled=true -->
<!-- TODO uncomment shields when available in dotfyle.com 
<a href="https://dotfyle.com/plugins/chrisgrieser/cmp_yanky">
<img src="https://dotfyle.com/plugins/chrisgrieser/cmp_yanky/shield" /></a>
-->

[cmp-source](https://github.com/hrsh7th/nvim-cmp) for yank history (clipboard
history) from [yanky.nvim](https://github.com/gbprod/yanky.nvim).

<img src="https://github.com/chrisgrieser/cmp_yanky/assets/73286100/9bc6ae22-6483-4972-838a-8bc1ccc4c138" alt="demo image showcasing suggestions" width=50%>

## Usage

```lua
require("cmp").setup {
  sources = {
    { name = "cmp_yanky" }
  }
}
```

## Options

The `onlyCurrentFiletype` option filters the yank history based on the current
filetype. (`yanky` remembers in which filetype you have yanked something.)

```lua
{
	name = "cmp_yanky",
	option = {
		onlyCurrentFiletype = true, -- default: false
	},
}
```

The number of possible items to be suggested also depends on the size of the
history. You can change the history size with `yanky`'s [ring.history_length
option](https://github.com/gbprod/yanky.nvim#ringhistory_length).

## Credits
<!-- vale Google.FirstPerson = NO -->
__About Me__  
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

__Blog__  
I also occasionally blog about vim: [Nano Tips for Vim](https://nanotipsforvim.prose.sh)

__Profiles__  
- [reddit](https://www.reddit.com/user/pseudometapseudo)
- [Discord](https://discordapp.com/users/462774483044794368/)
- [Academic Website](https://chris-grieser.de/)
- [Twitter](https://twitter.com/pseudo_meta)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)
