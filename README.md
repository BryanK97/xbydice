## XBYDice

XBYDice v 0.1

## Run your own dice site

If you want to run your own dice casino, all you need to do is clone/fork this project, create an app at Moneypot (https://www.moneypot.com/apps/new), and set the `config.app_id` at the top of the `app.js` file.

## Host it on Github

1. Fork this project
2. Rename the repository from `untitled-dice.github.io` to `{YOUR_USERNAME}.github.io`
3. Edit the config at the top of `app.js`
4. Visit `https://{YOUR_USERNAME}.github.io`

## Run it locally (for development)

    cd untitled-dice
    npm install
    python -m SimpleHTTPServer 5000

Then visit <http://localhost:5000>

## License

MIT
