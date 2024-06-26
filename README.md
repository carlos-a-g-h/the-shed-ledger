# My Shed's Ledger

## What is this now?

This is a very simple inventory manager, it only supports fungible items at the moment

### DISCLAIMER

I do not know anything about accounting, or have any background on warehousing or inventory management solutions, this is my first project of that nature, and I'm relying on my common-sense, so if you check out the code, expect some non-standard terminology in the naming of things

## Features

More will be added but this is what you can do right now:

- Create (define) and delete items
- Small search engine to quickly find items
- Add modification records to items

### Pending

- User (and external app) authentication
- Propper API for external clients and frontends

## This is built on what?

### Backend

- AioHTTP (Python)
- MongoDB (using the motor driver)

### Frontend

- Vainilla HTML/CSS
- HTMX (It is bundled along with this project but you can provide your own if you want to)

## How Do I run this ?

First of all, open up the "config.yaml" file and adjust it to your needs

After setting it up, you can run Shed Ledger:

like this

```
$ chmod +x shled; ./shled
```
or like this if you're not running the binary from the release

```
$ python3 main.py
```

### How to customize the CSS

You can customize the looks of this thing by editing the "custom.css" file, feel free to adjust it to your needs

btw, If you're going to edit anything related to the popup messages, please check the "popup.css" file from your browser's CSS Editor. The "popup.css" file is baked in the program so you can only see it while the program runs or in the source code
