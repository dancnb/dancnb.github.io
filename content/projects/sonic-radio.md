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
|p/enter          |                   play selected |
|space            |                      play/pause |
|f                |              toggle as favorite |
|i                |   station info(not implemented) |
|s                |    open search(not implemented) |
|/                |                  filter results |
|esc              |               go to now playing |
|1                |             go to favorites tab |
|2                |       go to station browser tab |
|←/h/shift+tab    |                  go to prev tab |
|→/l/tab          |                  go to next tab |
|?                |                     toggle help |
|q                |                            quit |

## TODO

* [ ] Search stations section
* [ ] Display rich station information
* [ ] Configuration section

## License

Sonicradio is licensed under the [MIT License](LICENSE).

### Third-party dependencies

[Bubbletea](https://github.com/charmbracelet/bubbletea/blob/master/LICENSE) MIT License
