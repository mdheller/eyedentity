# eyedentity-backend

![brain](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/160/apple/155/brain_1f9e0.png)

## Setting up

You can run this via Vagrant, just type this command in your prompt:

    $ vagrant up

## Manual installation

You should make sure you have:

-   at least `python3.5` with `pip`. You might want to create venv
-   `npm`
-   globaly installed `webpack`

Then type

    $ pip install -r requirements.txt
    $ npm --save-dev install
    $ npm run build

Use `npm run start` to run sanic server with react app.
