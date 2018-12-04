## coDE
A mac-keyboard-layout for german speaking hackers that does not suck.

Works on ANSI and ISO keyboards. Easy to learn because most of the stuff is there where you expect it to be (not like complete new layouts like DVORAK or NEO). 

Essentially its a [us-keyboard-layout](http://en.wikipedia.org/wiki/File:KB_United_States-NoAltGr.svg) with some alterations:

* `Z` and `Y` are where german speaking people like it. (`Z` is between `T` and `U`, `Y` left of `X`)
* your umlauts, `€` and `ß` work with `option-key` / `alt` + base-key:
    * `option` + `A` = `ä`
    * `option` + `shift` + `A` = `Ä`
    * `option` + `O` = `ö`
    * `option` + `shift` + `O` = `Ö`
    * `option` + `U` = `ü`
    * `option` + `shift` + `U` = `Ü`
    * `option` + `S` = `ß`
    * `option` + `E` = `€`
* `~` (tilde / unix-home) is on two places:
    * `shift` + `` ` `` (us-standard)
    * on the extra key on ISO-keyboards, between `left-shift` and `Y` (extra key: yay!)
* `°` (degree) is on `shift` + the extra ISO-key (between `left-shift` and `Y`)
* all dead-keys are disabled, so if you hit `` ` ``, `~` or `^` you get `` ` ``, `~` or `^`
* 'period' on the numblock produces `,` not `.`


### Installation

Copy `coDE.keylayout` into `~/Library/Keyboard Layouts` and pick `coDE` as layout in the preference pane.

In the Terminal:

```
cd ~/Library/Keyboard\ Layouts
wget https://raw.githubusercontent.com/bmaeser/coDE/master/coDE.keylayout
```

### Layout Images (ISO)

### default
![default](https://raw.githubusercontent.com/bmaeser/coDE/master/default.png)

### shift
![shift](https://raw.githubusercontent.com/bmaeser/coDE/master/shift.png)

### alt
![alt](https://raw.githubusercontent.com/bmaeser/coDE/master/alt.png)

### alt + shift
![alt + shift](https://raw.githubusercontent.com/bmaeser/coDE/master/altshift.png)

