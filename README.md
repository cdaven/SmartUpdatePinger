# Smart Update Pinger (inactive since 2006)

Smart Update Pinger replaces the built-in update ping functionality. Instead of always pinging when saving a post, the plugin only pings when the post has not previously been published. Edits of posts are "silent", in contrast with the default behaviour. Also, you can see a log for the latest pings, together with error messages (in the options page).

Motivation: "update pings" to blog services includes the URL of your blog, not of a specific post. You should only ping when you have added a new post to your blog since there is no way of telling which post was edited and caused the blog tool (WordPress) to ping. If you edit several already published posts, everyone will cause a new ping frenzy, unless you have Smart Update Pinger installed. You don't want to be banned for pingspamming, do you?

As of version 2.0, WordPress' built-in ping functions are ignored. Instead, a copy of that code, with some improvements, has been put inside this plugin. This was necessary to give detailed log reports. You can see which services accepted and rejected your ping, and why.

Another new functionality in 2.0 is the "Ping Services Now!" button in the options page, which lets you ping all services without writing a post. Should come in handy if there are problems.

## History

This repository is imported from local file, without commit history.
