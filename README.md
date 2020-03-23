# digital-vaiven 🇵🇷
Freeze dried tumblr blog via httrack

## Steps to view site locally

1. Clone this repository + cd into it
    ```sh
     $ git clone https://github.com/irLh/digital-vaiven.git
     $ cd digital-vaiven
     ```
2. Open in default browser
    ```sh
    $ open index.html
    ```

## Steps to reproduce (OSX)

1. Install httrack with [Homebrew](https://brew.sh/):
  
    ```sh
    $ brew install httrack
    ```
2. Make a scratch directory and cd into it:
   
   ```sh
    $ mkdir ~/Desktop/httrack
    $ cd ~/Desktop/httrack
    ```
3. Run it!
    ```sh
    $ httrack https://digitalvaiven.tumblr.com --verbose
    ```
    
## Notes
CLI options may need to be tweaked in the future. For reference, see: https://forum.httrack.com/readmsg/36755/36754/index.html
