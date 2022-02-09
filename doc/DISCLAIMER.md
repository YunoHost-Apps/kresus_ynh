## Demo

* [Official demo](https://kresus.org/en/demo.html) Don't set up a connection to your bank accounts, or everybody would be able to look at your private bank information!

32 bits architectures are not supported because nodejs does not provide builds for 32 bits anymore.

## Limitations

* By default, all users have access to the accounts. The admin needs to manually select the authorised user through YunoHost Administration Panel.

## Roadmap

* works fine:

  * [x] install/remove/backup/remove/upgrade with x86_64

* to be confirmed
  * [x] ARM support

* to be added:
  * [ ] URL cannot be changed
  * [ ] Email support
  * [ ] Improve log file and add logrotate
  * [ ] Add user who will access the app (by default every one has access to the installed app)
