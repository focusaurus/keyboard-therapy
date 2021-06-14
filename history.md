# Summary History of My Keyboard Setup

# v0 (1990s)

- Improper 6-finger qwerty touch typing
- assorted early Windows and Mac desktops and laptops

# v1 (2000s)

- Learned proper 10-finger touch-typing and the dvorak layout
- Still on standard keyboard hardware
- transitioned from mostly-mac to mostly-linux
- set keyboard layout with OS utilities
- `setxkbmap dvorak` but not much beyond that

# v2 (2010s)

- Stabilized for a while on macbook pro with dvorak in software and Keyboard Maestro
- Developed first extensive snippets library. Worked throughout the GUI session.
- Developed large toolbox of macros in Keyboard Maestro
- Remapped caps lock to control via macos keyboard settings
- Enabled OSX "Sticky Keys" accessibility setting for one-shot modifiers
  - For several years was convinced all modifiers should be one-shot and chording was terrible
  - This partially hinged on how great and reliable macos GUI/HUD overlay was. Whenever a sticky modifier was activated, there was clear indication on the screen

# v3.0 (2013)

- Bought an ergodox in I think the 2nd massdrop group buy
- full-hand acrylic case
- became a true believer in
  - split keyboards
  - ortholinear layout (plus columnar stagger)
  - thumb clusters
  - steep tenting
  - multilayer layouts
- Layers evolved frequently but the core bits were
  - Base layer still qwerty and doing dvorak remapping in the OS
    - Tried also dvorak in firmware and switching between external and laptop keyboard requires changing the OS input layout and it's a hassle. Easier to just always do dvorak in the OS.
  - Navigation/formatting layer (arrows, space, tab, backspace, delete, home/end, etc)
  - Numpad layer on right hand
  - Weird but good columns for paired punctuation: `() {} []`
- Was not explicitly aware of QMK at this point. Not managing my ergodox configuration in git, etc.
  - Using keyboard-layout-editor.com and configure.ergodox-ez.com

# v3.1 (2018)

- Bought an Infinity Ergodox
- Learned about Quantum Mechanical Keyboard (QMK) project
- Discovered more subreddits like /r/mechanicalkeyboards, /r/ergomechkeyboards, /r/olkb
- adopted QMK tooling for both my ErgoDox and Infinity ErgoDox
- Learned about mod-taps via Ross Hadden and started using them via `xcape` on linux
- Added some mod-taps to my QMK layers

# v3.2 (2020)

- Bought and tried a keyboardio model 01
- The large pinkie column offset was too different from the ergodox (and standard keyboards) for me to adjust to
- I ended up typing one row too high on the pinkie column by accident
- at some point may give it another go, but at that time I gave up and switched back to my ergodoxes

# v3.3 (2020)

- Learned about kmonad and started to replace my linux X11 utilities (setxkbmap, xmodmap, xbindkeys, xcape) with kmonad for thinkpad linux laptop keyboard stuff
- Tried home row mod-taps
- Had to use macos/macbook for work
  - Researched extensively for tools for snippets, macros, hotkeys, etc
  - settled on hammerspoon, karabiner elements, and bettertouchtool as key components of my macos stack
- Nicely scripted QMK compiling/flashing
- Using ergodox on linux and infinity ergodox on mac

# v4 (2020)

Did some [research on which keyboard to build for v4](v4-research.md). Ended up building a keebio irisv4 but not liking the thumb cluster position.

# v3.5 (2020)

Late game upset! After typing on the iris for a week I was having pain in my left thumb from keeping it in flexion above the middle thumb key. I think my only option to continue on the iris would be to rework my key mappings so that my thumb hovers on the innermost key and moves outward to hit the other ones, which would be a biggish muscle memory rework. That did not seem too desirable ergonomically. I had also been thinking about tracing the outline and making a full-hand case for it with my woodworking router, and I realized I was just basically trying to modify this iris so that it was like my ergodox. But the new QMK experience I gained gave me some good tools and a fresh perspective. I wanted to fix my errant touch typing on the pinky top row. I hadn't realized, but I have been typing the top row pinkie keys with my ring finger by reaching sideways, which I think the greater column stagger on the model 01 vs the ergodox might remedy. So I decided to pull my keyboardio model 01 out of the closet and over a 4-day weekend get my keymaps updated and spent some time typing and trying to fix those touch-typing habits. Sadly most typing programs don't use apostrophes much so I may need to find some more specialized drills to do.

So back to the keyboardio model 01 again, but this time running custom QMK firmware instead of kaleidoscope/chrysalis.

# v3.6 (2020)

I grew quite frustrated with the mattias switches in the model 01. They were so flimsy and only actuated properly when struck from dead center above. I foolishly tried to lube them not knowing that they had a history of issues with liquid lube. After that I started to have issues with jitter and broken keys. I gave up and went back to my 2013 ergodox with full-hand case. I like the switches in there much better and I now had a much better toolbox in terms of QMK setup, leader keys with menuhammer, etc. I had no more need for dedicated function keys.

# v3.7 (2021)

Through many experiments with a keebio iris v4, a splitkb kyria, and 2 custom squeezebox prototypes I've overhauled my keymaps kind of a lot and reduced pinky usage a lot. Chording also reduced by a lot of one-shot modifiers. Still haven't been able to find anything that works better for me than my OG ergodox from 2013.

# v5 Tractyl (nah)

I was originally thinking of doing this but once I started prototyping the squeezebox I decided to focus on that instead.

I want to build something like this vertical dactyl manuform. The maker has extensive notes etc, but does indicate this is several months worth of weekends to tackle.

![tractyl](https://preview.redd.it/1k2lzwhqzqz51.jpg?width=1080&crop=smart&auto=webp&s=3feff33cddc8cacac8b4639859e10f0968631939)

[reddit post](https://www.reddit.com/r/ErgoMechKeyboards/comments/jvofrz/rebuild_finally_complete/?utm_source=share&utm_medium=web2x&context=3)

# v5.0 Squeezebox DIY custom

I'm currently prototyping a split vertical keyboard and the results are promising enough that I'm expecting to be able to have a working version in winter of 2021.

For more details on this build check out [squeezebox-v0](squeezebox-v0.md).

# squeeze box long term roadmap

- v0: Keep it simple and achievable. Focus on a working prototype I can type on without spending months on the trickier ergonomic CAD challenges.
- v1: Add thumb cluster
- later: add some pointing device
  - thumb joystick a la the sherbert keyboard
  - thinkpad style touchpoint
  - thumb trackball
- later: Do the trickier ergonomics of the build: column X and Y axis offsets
- fully ambidextrous layer mappings
- QMK support for 2 truly independent layer stack activation states across the hands
