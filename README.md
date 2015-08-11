# jg-creative
Creative resources for Jung Digital LLC.

# Abbreviations

In an effort to organize files/resources the following abbreviations will be observed:

- stk, stock
- lgo, logo
- cut, final cut up graphic assets
- gx, graphics
- c, C/C++ code
- js, Node.js or front-end code

All Files Copyright(C) 2015 by Joshua Jung and Jung Digital LLC

# Personal Access Token (Wordpress)

fac0438af6ff5425bc7aaa4832bab8cf9158f203

Configuring the plugin

Create a personal oauth token with the public_repo scope. If you'd prefer not to use your account, you can create another GitHub account for this.
Configure your GitHub host, repository, secret (defined in the next step), and OAuth Token on the WordPress GitHub sync settings page within WordPress's administrative interface. Make sure the repository has an initial commit or the export will fail.
Create a WebHook within your repository with the provided callback URL and callback secret, using application/json as the content type. To set up a webhook on GitHub, head over to the Settings page of your repository, and click on Webhooks & services. After that, click on Add webhook.
Click Export to GitHub or if you use WP-CLI, run wp wpghs export all === from the command line, where === = the user ID you'd like to commit as.