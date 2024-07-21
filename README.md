# Open Feedback
The open-source feedback collection tool for your website or web-app.

<h2>Installation</h2>
Add the following code snippet to your desired application somewhere where it will be rendered on all of your desired pages (ex: your page layout file or template). <b>Please ensure to change the config variables as well!</b><br><br>

```html
<script>
  window.OPEN_FEEDBACK_CONFIG = {
    "discord": "<your-discord-webhook-here>",
  }
</script>
<script src="https://cdn.jsdelivr.net/gh/michael8u/feeder/dist/index.js"></script>
```

<h2>Development</h2>
To spin up a development environment for Open Feedback, follow the script below and it will automatically create a build from your source-code, spin up a new web-server with an embed to your latest build to test in tmux, and begin watching your files for any changes (to reinitialize the build).<br><br>

```bash
npm config set -g production false && npm i && npm run dev
```


