# xi-gtk

[![Join the chat at https://gitter.im/eyelash/xi-gtk](https://badges.gitter.im/eyelash/xi-gtk.svg)](https://gitter.im/eyelash/xi-gtk)
[![vector.im | #xi-gtk](https://img.shields.io/badge/vector.im-%23xi--gtk-76cfa6.svg)](https://vector.im/beta/#/room/#xi-gtk:matrix.org)

![screenshot](https://raw.githubusercontent.com/eyelash/xi-gtk/master/screenshot.png)

## Instructions

```sh
git clone https://github.com/google/xi-editor.git
cd xi-editor/rust
cargo install
export PATH=~/.cargo/bin:$PATH
cd ../..
git clone https://github.com/eyelash/xi-gtk.git
cd xi-gtk
mkdir build
cd build
meson ..
ninja
./xi-gtk
```

## Shortcuts

Shortcut                                         | Command
-------------------------------------------------|---------
<kbd>Control</kbd>+<kbd>N</kbd>                  | New File
<kbd>Control</kbd>+<kbd>O</kbd>                  | Open File
<kbd>Control</kbd>+<kbd>S</kbd>                  | Save
<kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>S</kbd> | Save As

## To Do

- [x] mouse input and selections
- [x] saving
- [ ] follow the cursor (respect the `scrollto` parameter)
- [ ] undo / redo
- [ ] copy / paste
- [ ] i18n
- [ ] preferences (font family, font size, etc.)
