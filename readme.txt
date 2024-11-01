=== Twitter Blockquotes oEmbed ===
Contributors: kovshenin
Donate link: http://theme.fm/2011/08/embedding-tweets-in-wordpress-with-twitter-blockquotes-1548/
Tags: twitter, embed, tweet, oembed
Requires at Least: 3.1
Tested Up To: 3.2.1
Stable tag: 1.0

Embed tweets in your posts and pages just like you would a YouTube video -- just copy and paste the tweet URL on a separate line. Works like oEmbed.

== Description ==

The plugin works out of the box, just like oEmbed, but not really using Twitter's oEmbed. It creates blockquote elements out of your links to tweets with the cite element containing the tweet author. Just paste a URL to a tweet on a separate line in your editor. Like this:

* `http://twitter.com/#!/themefm/status/101217888383410176`

Tweets are cached for better performance. The plugin itself has got a custom CSS field where you can style your twitter blockquotes however you like. Use the `blockquote.tweet` CSS selector and add an image with some padding on the left, or perhaps style the tweet author differently. Hardcore theme and plugin developers can take advantage of the many filters inside the plugin to make Twitter Blockquotes do whatever they like -- add the author avatars, time and date, action intents and more. Code is well commented and easy to understand.

Read these articles for more control over the plugin: 

 * [Embedding Tweets in WordPress with Twitter Blockquotes](http://theme.fm/2011/08/embedding-tweets-in-wordpress-with-twitter-blockquotes-1548/)
 * [How to: Display Avatars with Twitter Blockquotes for WordPress](http://theme.fm/2011/09/how-to-display-avatars-with-twitter-blockquotes-for-wordpress-2227/)

== Installation ==

1. Download the plugin zip archive.
2. Extract it in your `wp-content/plugins` folder or upload via admin panel.
3. Browse to your plugins section and active the plugin.
4. Use it in your posts and pages by linking to tweets on a separate line.
5. (Optional) Give it some extra styling using the Custom CSS field in the plugin settings.

== Frequently Asked Questions ==

= Where do I get the link to a tweet? =

Good question. It really depends on the Twitter application/client that you're using. If you're using twitter.com then take a close look at the tweets and you'll see that the date of when the tweet has posted (1 hour ago, etc) is a link. That link is the one you're looking for. If you're using the Twitter for Mac application, you can right click any of the tweets and select View on Twitter.com which will take you to that particular tweet in your browser.

= Can I add author avatars? =

Yes, if you're comfortable with PHP and WordPress' Filters API. Read throughout the source code of this plugin and spot the calls to `apply_filters`. That's where you have to hook in to add avatars, time and dates, reply, retweet and favorite actions and more.

More info in this post: [Embedding Tweets in WordPress with Twitter Blockquotes](http://theme.fm/2011/08/embedding-tweets-in-wordpress-with-twitter-blockquotes-1548/)


= Tell me more about styling it! =

Sure thing, there's a [Gist available](https://gist.github.com/1134325) that provides a few examples. Go ahead and copy/paste them into your Custom CSS field in the plugin options. There's no all-in-one solution since it really depends on your theme. Some might want an icon, others a right margin. Somebody wants a different typeface, others would want the author to stand out. So what I have created is a simple skeleton that works out of the box, rest is up to you.

== Screenshots ==
1. This is how your embedded tweets will appear on your blog or site.
2. This is how you embed your tweets in the editor -- just a link on it's own line.

== Changelog ==

= 1.0 =
* First release.
