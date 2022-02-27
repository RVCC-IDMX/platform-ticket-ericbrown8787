# Platform Ticket

## Introduction

This project is an attempt at using modern HTML and CSS in order to visually recreating a "Platform Ticket", which in this case was issued to guests of an 1895 event at the New Metropolitan Opera House celebrating the 80th birthday of suffragist Elizabeth Cady Stanton.

![Image of the platform ticket](platform-ticket.png)

The original ticket appears to use at at least nine different typefaces. This does not include the New Metropolitan Opera House Logo in the top left, which may have been a single block, and there may be a possible tenth in the vertical "and" in "Pioneers and Friends of Woman's Progress".

For this project, I attempted to find fonts that were similar to the ones used in the original ticket, as well as recreate the appearance of printed text, including opacity and artifacts of the printing process such as ink bleeds.

## Sources and inspiration

[Olivia Ng's Train Ticket Codepen](https://codepen.io/oliviale/pen/MZZYyO)

## Fonts Used

All fonts are free for personal use.

- [Black Widow](https://www.ffonts.net/Black-Widow.font)

- [Boden Esperanto](https://www.ffonts.net/Boden-Esperanto.font)

- [Bold Box](https://www.ffonts.net/Bold-Box.font)

- [Courier Prime Bold](https://www.ffonts.net/CourierPrime-Bold.font)

- [IM Fell English SC](https://fonts.google.com/specimen/IM+Fell+English+SC)

- [They Killed Kenny!](https://www.ffonts.net/They-Killed-Kenny.font)

- [Ravenscroft](https://www.ffonts.net/Ravenscroft.font)

- [Syne Bold](https://www.ffonts.net/Syne-Bold.font)

- [Traditionell Sans Bold](https://www.ffonts.net/TraditionellSans-Bold.font)

## How to use this repo

1. Clone the repo
1. In your terminal, run
   ```bash
   npm install
   ```
1. In your terminal, run the parcel watcher
   ```bash
   npm run dev
   ```

### The Parcel dev script

The Parcel dev script will watch your files for changes automatically and will live update your browser.

1. In your browser, go to `http://localhost:1234/`
1. ParcelJS will reload the page when changes are made

### How to stop a watcher

When you want to stop the watcher, click in the terminal and press ctrl-c

## When you are ready to go to production

1. In your terminal, run

   ```bash
   npm run build
   ```

1. The final version of your site will be in the `dist` folder.
