# DokuWiki Slack Notifier
This plugin is fored from https://github.com/mallchin/dokuwiki-slack-notifier .
A DokuWiki plugin that notifies the same name of slack channel corresponding with the dokuwiki page name.

![](./example.png)
## Install
Clone the repository into your DokuWiku plugins folder:
```
$ git clone https://github.com/TetsuakiBaba/dokuwiki-slack-notifier /var/lib/dokuwiki/lib/plugins/slack-notifier
```

## Configure

1. Create an Incoming Webhook on slack
2. Enter the webhook into the slackhq configuration section in DokuWiki's Configuration Settings
3. Create slack channel you wanna get notified, and also create a dokuwiki page you wanna send notification. Both have to be a same name. 

    Make sure that your Dokuwiki page name is conrrespondin with slack channel name. If you want to notify to a slack channnel named #test, you have to create same name page under the namespace, namespace:test. 
