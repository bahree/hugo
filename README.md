# Hugo related things

## Embedding Mastodon Toots in Hugo
To embedd toots, you need to two things:
* Copy toot.html (see [code](https://github.com/bahree/hugo/tree/main/toots)) to your shortcode folder.
  * Typically this is found in `[your-hugo-root-directory]/layouts/shortcocodes/`
* Copy the toot.css to your css folder.
  * Typically this is found in `[your-hugo-root-directory]/assets/`

And then you can call this embedding the shortcode using the instance and the toots ID.

`{{<toot "https://mastodon.online/@bahree/109371226849674784" >}}`

For example my introduction toot on Mastodon is shown below.

<img width="284" alt="image" src="https://user-images.githubusercontent.com/3529468/213935720-e38d2797-443c-4d6d-9d53-2966d93b46cd.png">

And the URL that is using is: https://mastodon.online/@bahree/109371226849674784 - and this is the same one you embed in the shortcut.

You can see this in action my [blog](https://blog.desigeek.com/about/). The CSS is still funky, and needs fine-tuning, and not being a CSS and JS expert, this is something I can't be bothered. 🤓 Happy to get PR's if anyone is tweeks it.
