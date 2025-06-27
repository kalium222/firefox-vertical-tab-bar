# 2025/6 Use sidebar provided by firefox itself

# firefox-vertical-tab-bar

Let Firefox show a vertical bar instead of a horizontal one.
Based on a firefox addon, [sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/).

All of the content about side bar is extracted from [VerticalFox](https://github.com/christorange/VerticalFox).

We first need to know [how to customize firefox through css](https://www.reddit.com/r/firefox/wiki/userchrome/).

## Set up 

First set up `sidebery` addon to let it has a proper
look when hiding it.
- Install `sidebery`
- Copy the content in the `./sidebery_style.css` in to the `Sidebery/Styles Editor`.

Then, enable auto hiding and showing of sidebery.
- Copy all the content to our `userChrome.css` file.

If we hope to set a background image at `newtab`, see 
`userContent.css` file and put the image in the `chrome/`.
