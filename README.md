# Drag
A desktop image loader powered by Vue/Electron/Node

<img src="http://res.cloudinary.com/da4uixfcu/image/upload/v1478526931/jddyy8yyuchd4ur0i9ep.png" alt="drag home" style="height:420px;">

## Install
``` bash
# Clone the repository once
$ git clone https://github.com/shengxihu/Drag/

# Go into the repository (rename it as you wish)
$ cd Drag

# Install the 7 only dependencies once
$ npm install
```

## Dev
Run this two commands in two different prompts to start developing with hot reloading.
``` bash
# Webpack builds once and watches to apply only the changes
$ npm run dev

# Start you electron app
$ npm run start

# Package you electron app
$ npm run package
```

## Usage
You don't really need more stuff to upload you image to Image Hosting，just drag it!

- input you account details.
- drag into the drag area.
- wait a little while

## Warning

- it use express to run a local server,so if you want to use,close your vpn or adjust it to national pattern.

## Template structure
```
├── Drag/               # Your project's name

    ├── app/

        ├── build/                      # Webpack will bundle your css/js/img here

        ├── src/

            ├── assets/                 # Images go here
                
            ├── components/             # Webcomponents go here

            ├── Main.vue                # Vue app. Your global css can go here
            ├── Menue.vue               # Vue app. Your global css can go here
            ├── entry.js                # App entry. Your global js can go here

        ├── mian.html                  # Single Page Application HTML, it only uses build's files
        ├── menue.html                  # Single Page Application HTML, it only uses build's files

    ├── main.js                         # Electron app init
    ├── package.json
    ├── webpack.config.js               # Minimal webpack setup
```


