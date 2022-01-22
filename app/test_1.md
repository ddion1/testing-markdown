# header 1

test 1

## header 2

test 2

### header 3

test 3

url test : [google](www.google.ca)

- un
- deux
- trois

This sentence introduces my wiki page.

- `command`

Sometimes you want to :monkey: around a bit and add some :star2: to your :speech_balloon:. Well we have a gift for you:

:zap: You can use emoji anywhere GitLab Flavored Markdown is supported. :v:

You can use it to point out a :bug: or warn about :speak_no_evil: patches. And if someone improves your really :snail: code, send them some :birthday:. People :heart: you for that.

If you're new to this, don't be :fearful:. You can join the emoji :family:. Just look up one of the supported codes.

Consult the [Emoji Cheat Sheet](https://www.emojicopy.com) for a list of all supported emoji codes. :thumbsup:

- [+ addition 1 +]
- [+ addition 2 +]
- {- deletion 3 -}
- {- deletion 4 -}

[Link to Documentation](documentation.md)

> Blockquotes help you emulate reply text.
> This line is part of the same quote.

Quote break.

> This very long line is still quoted properly when it wraps. Keep writing to make sure this line is long enough to actually wrap for everyone. You can also *add* **Markdown** into a blockquote.

>>>
...If you paste a message from somewhere else

...that spans multiple lines,

...you can quote that without having to manually prepend `>` to every line!
>>>

# Testing Header Anchor

```python
def function():
    #indenting works just fine in the fenced code block
    s = "Python code"
    print s
```

~~~python
def function():
    #indenting works just fine in the fenced code block
    s = "Python code"
    print s
~~~

# Testing Header Anchor1

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with double **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
    
    
    
A footnote reference tag looks like this: [^1]

This reference tag is a mix of letters and numbers. [^footnote-42]

[^1]: This text is inside a footnote.

[^footnote-42]: This text is another footnote.


Three or more hyphens,

---

asterisks,

***

or underscores

___


Inline-style (hover to see title text):

![alt text](../img/markdown_logo.png "Title Text")

Reference-style (hover to see title text):

# ![alt text1][logo]

[logo]: ../img/markdown_logo.png "Title Text"


<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. HTML <em>tags</em> do <b>work</b>, in most cases.</dd>
</dl>

<p>
<details>
<summary>Click this to collapse/fold.</summary>

These details <em>remain</em> <strong>hidden</strong> until expanded.

<pre><code>

1 un
2 deux
3 trois
4 quatre

</code></pre>

</details>
</p>


<details>
<summary>Click this to collapse/fold.</summary>

These details _remain_ **hidden** until expanded.

```
PASTE LOGS HERE
```

</details>


Here's a line for us to start with.

This longer line is separated from the one above by two newlines, so it is a *separate paragraph*.

This line is also a separate paragraph, but...
These lines are only separated by single newlines,
so they *do not break* and just follow the previous lines
in the *same paragraph*.

- This line links to [a section on a different Markdown page, using a "#" and the header ID](documentation.md#overview)

- This line links to [a different section on the same page, using a "#" and the header ID](#testing-header-anchor1)
- - This line links to [a different section on the same page, using a "#" and the header ID](#header-ids-and-links)
- 


- This line shows an [inline-style link](https://www.google.com)
- This line shows a [link to a repository file in the same directory](index.md)
- This line shows a [relative link to a readme one directory higher](../index.md)
- This line shows a [link that also has title text](https://www.google.com "This link takes you to Google!")

Using header ID anchors:

- This line links to [a section on a different Markdown page, using a "#" and the header ID](index.md#overview)
- This line links to [a different section on the same page, using a "#" and the header ID](#header-ids-and-links)

Using references:

- This line shows a [reference-style link, see below][Arbitrary case-insensitive reference text]
- You can [use numbers for reference-style link definitions, see below][1]
- Or leave it empty and use the [link text itself][], see below.

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org/en-US/
[1]: https://slashdot.org
[link text itself]: https://www.reddit.com



- https://www.google.com
- https://www.google.com
- ftp://ftp.us.debian.org/debian/
- smb://foo/bar/baz
- irc://irc.freenode.net/
- http://localhost:3000


1. First ordered list item
2. Another item
   - Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
   1. Next ordered sub-list item
4. And another item.



| header 1 | header 2 | header 3 |
| ---      | ---      | ---      |
| cell 1   | cell 2   | cell 3   |
| cell 4 | cell 5 is longer | cell 6 is much longer than the others, but that's ok. It eventually wraps the text when the cell is too large for the display size. |
| cell 7   |          | cell 9   |


| Left Aligned | Centered | Right Aligned |
| :---         | :---:    | ---:          |
| Cell 1       | Cell 2   | Cell 3        |
| Cell 4       | Cell 5   | Cell 6        |

| header 1 | header 2 |
| ---      | ---      |
| cell 1   | cell 2   |
| cell 3   | <ul><li> - [ ] Task one </li><li> - [ ] Task two </li></ul> |



Title
ID
Severity
Status
Reproducible
Description
Steps to reproduce
Created by
Reproduced by/
Also seen by
Reported to Nord by
OS Version
Link to more info
Date submitted
Unpitched Samples can pitch in legato mode
70
Major
Fixed in 2.54??
Open
Yes
Unpitched samples will be transposed when played legato.
Load an unpitched sample in synth section (play mode set to 'unpitched' in the editor).
Set synth as 'Legato'.
Compare the pitch while playing different notes in legato-style (pressing the next key before letting go the previous one) and normal style (press a key, let go, press the next key).

=> The sample will not pitch in normal style and pitch in legato-style.
Dan84


2.12


two different samples readen together changes attaq / release response
71
major
Fixed in 2.54??
always
Some more details about line 60 :
when used together two panels with two samples it changes attaq / release response 
really visible on pads with sustain pedal
even if panel B sample has no volume
read one slow attaq pad sample and another one in panel B with volume at 0
Nanawel


all (Edit: PLEASE STATE WHICH VERSION YOU TESTED FOR REFERENCE! "ALL" literally includes every single future release. -analogika)
same midi part played with one panel or with two panels (without sound in panel B) 
LINK

split zone with arp+hold key
72
major
open
yes
when synth in one zone uing arp+holdkey, pressing keys on diffrent zones will retrigger the arppegiator
set synth to low split zone, press arp, press hold key, press notes on the lower split, then press unassigned notes on the upper split
itaishitrit


2.22


Chorus/Vibrato scanner NOT working properly on VOX and FARF organ models
75
Major
open
yes
V/C scanner switch on VOX and FARF organs have some issues. See the forum post for the description. Link in the rightmost cell.
Turn on the VOX or the FARF engines on both panels and try switching V/C scanner ON and OFF for each panel and each preset of each panel and see what happens (again, refer to the forum post).
Hlaalu
Y-LNordist
Hlaalu on 24/05/2020
At least from 2.54
https://www.norduserforum.com/nord-stage-forum-f3/list-of-nord-stage-3-known-issues-bugs-t14203-220.html#p131055

MIDI Program Changes messages are received by the Stage 3 even if the setting is OFF
77
Major
open
yes
On the Global Channel, the NS3 receives Program Changes messages even if the settings (MIDI menu, page 3) says OFF or Send only
Set PC messages OFF or Send only in the menu and then try sending a PC message to the board. Sure enough, it will change Program. NB: This only refers to the Global channel. PC messages aren't handled at all in the Panels MIDI channel.
Hlaalu

Hlaalu on 29/10/2020
2.54
https://www.norduserforum.com/nord-stage-forum-f3/list-of-nord-stage-3-known-issues-bugs-t14203-250.html#p133544
23.8.2020
Arpeggiator does not take MOD or AMP envelope velocity settings into account.
8
Medium
Seems to be have been fixed. Cannot reproduce the problem on 2.x (baekgaard).
Yes
This causes a sharp timbre and volume discontinuity when turning the ARP RUN on and off while playing.
Turn MOD envelope velocity on, AMP env velocity on (any curve), turn Modulation knob all the way to VEL (left) and dial in a fat S-wave sawtooth with filter freq down low until it's a nice mellow horn sound that you can play quietly with a nice velocity response. Play an arpeggiator pattern manually (e.g. 3-notes up) with ARP RUN turned off. Then turn ARP RUN on and press & hold those notes with the same velocity. Notes will be much louder and brighter (basically as if mod/amp env velocities were turned off).
Chris Roehrig

Chris Roehrig
1.4


Flange and phase always active even at 0 amount
17
Medium
Open
Yes
just test...

ADSRLFO
Ecaroh, analogika

1.32


Samples are not released if the same key is pressed twice after Sustain
45
Medium
Open
Yes
By holding the sustain pedal you can make the same sample sound several times. However when you let go the sustain pedal, all previously triggered notes should be released which seems not to be the case for custom looped samples.
Load a custom sample with a loop. Press a key, then hold down the Sustain pedal and let go of the key (the sample keeps playing). Then press the same key again, now both samples are playing. Let go of the sustain pedal, the initial loop does not stop, both keep playing.
Dan84
Nanawel

1.36


Up / Down pedal works different on PROG and SONG mode
59
Medium
Open
Yes
In Prog mode, we can UP the programs allways to next, changing the Program and bank, but in song mode, we just can use the 5 Song parts ... I think could be important move to the next song .... iqual Prog mode
Change PROG in song mode - More information on video
Rsfelicio
This doesn't sound to me as a bug but rather as the way the thing is programmed to work. (Hlaalu).
Video link doesn't exist anymore (cookie)

1.32
https://www.youtube.com/watch?v=ZNgbH9WQ7G8

"Page/bank" buttons not working as expected in Numeric Pad navigation mode
73
Minor
open
yes
When Numeric Pad navigation mode is active, the "page" buttons should work as "bank" buttons (as per manual). They keep working as usual, though. This happens in the NS3 88 RevB 5,1 which has "page" and "bank" as the same physical button, with "bank" below it (Shift-activated).
Turn on Numeric Pad mode. Now press "page" to navigate between banks. It won't happen. Instead, you'll still be navigating between pages. You'll still have to press Shift + page to trigger bank navigation.
Hlaalu


At least from 2.22


Organ section is always on with whatever sound I choose
76
Minor
open
yes (but only on a particular instrument, not generally an issue it appears PB/20200804).
The organ section is always on. for example when I use just the piano, the organ section is on without the sound, although the drawbars are there and sometimes they switch off and on by their own. it doesn't affect the playing although it is quite frustrating and annoying
NOTE: This is not likely to be a SW issue, but could be symptomatic of a dial or button that alternates between states (PB/20200804)

Stelios
This doesn't seem to be a bug but rather some hardware malfunction. It shouldn't be in this sheet in my opinion (Hlaalu)

2.54

4.8.2020
The "E" symbol of the synth section is not shown under certain circumstances
78
Minor
open
yes
If a synth preset has been modified for a specific Program that contains it, an "E" should appear next to the third line in the main display -- as well in the synth display. This only happens, though, when jumping to such a Program from a Program that had another synth preset in it. If, conversely, I go to this Program from another one which had, instead of a synth preset, just any synth setting, then the "E" doesn't appear, neither in the main display nor in the synth's.
Read the "description" column
Hlaalu

Hlaalu on 16.11.2020
2.54
https://www.norduserforum.com/nord-stage-forum-f3/list-of-nord-stage-3-known-issues-bugs-t14203-250.html#p136006
16.11.2020
Write error message when trying to copypaste a Program and saving it without renaming to a different location
74
Minor... though a warning message like that could make one think something serious is broken in their board.
open
yes
If you copy a Program and then paste it to a different location, then try to save it without renaming, a "write error" message will pop up. This is because the system's suggested name for that newly pasted program is <empty>, which contains the forbidden characters < and >. Rename it differently, and the error message doesnt' show up.
Copy a program, paste it to an empty location and try saving it without renamiing it (double pressing the Store button.
Hlaalu
paul42

At least from 2.22
https://www.norduserforum.com/nord-stage-forum-f3/ns3c-copy-paste-program-write-error-t18389.html

swell pedal and Ctrl pedal problem
57

open

By holding the sustain pedal you can make the same sample sound several times. However when you let go the sustain pedal, all previously triggered notes should be released which seems not to be the case for custom looped samples.

Satomy
This seems to be the same description as the previous bug. Possible to delete? (Hlaalu)
open
1.32


Feature request. Pre delay for LFO in synth section
79



Please add a pre delay to the LFO at the synth section. Since the control shift/rate is already occupied with MasterClock (wich could also, and maybe better be found in the "sound" panel), this function could be added for each sound/program in the sound panel. It´s is very annoying when modulations are already there (filter, whatever) while they should start after the ENV has done its cycle.

Kaffimusic


2.54

29.12.2020
organ reverb runs always before leslie simulation




Reverb aplied to the organ sound run through the rotary horn and bass drum, "spinning" the decay of the reverb. It will be nice if the reverb position would be at the end of the path signal, after leslie simulation.

erlon79


2.54

08.06.2021
organ section volume affects the overdrive of the leslie simulation




if you turn the overdrive of the leslie simulation to maximum to have a crunch sound, but need to quiet the organ section in the mix with a piano for example, the overdrive will be decreased. It will be nice if the gain of the overdrive could not be affected by the organ section global volume.

erlon79


2.54

08.06.2021

