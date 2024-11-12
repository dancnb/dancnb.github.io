+++
title = 'Sonic Radio'
description = "A stylish TUI radio player making use of Radio Browser API and Bubbletea library."
# date = 2024-06-02T13:54:50+03:00
toc = true
draft = false
+++

A stylish TUI radio player making use of [Radio Browser API](https://www.radio-browser.info/) and [Bubbletea](https://github.com/charmbracelet/bubbletea).

## [Github](https://github.com/dancnb/sonicradio)

## Prerequisites

* Go : https://go.dev/doc/install
* MPV  : https://mpv.io/

## Installation

    go install github.com/dancnb/sonicradio@latest

## Usage

After the installation, the command to run the application:

    sonicradio

## Demo

![ Demo](/sonicradio.png)
![ Demo](/demo.gif)

## Keybindings

| Key(s)          |                          Action |
|:----------------|--------------------------------:|
|↑/k              |                              up |
│↓/j              |                            down |
|g/home           |                     go to start |
|G/end            |                       go to end |
|enter            |                   play selected |
|space            |                    pause/resume |
|f                |              toggle as favorite |
|i                |                    station info |
|d                |                  delete station |
|p/shift+p        |           paste deleted station |
|s                |                     open search |
|/                |                  filter results |
|esc              |               go to now playing |
|#                |            go to station number |
|←/h/shift+tab    |                  go to prev tab |
|→/l/tab          |                  go to next tab |
|-/<              |                        volume - |
|+/>              |                        volume + |
|?                |                     toggle help |
|q                |                            quit |

## TODO

- [x] Search stations section
- [x] Display rich station information
- [ ] Configuration section

## License

Sonicradio is licensed under the [MIT License](LICENSE).

### Third-party dependencies

[Bubbletea](https://github.com/charmbracelet/bubbletea/blob/master/LICENSE) MIT License
