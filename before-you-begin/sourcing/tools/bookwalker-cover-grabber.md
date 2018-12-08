# Bookwalker Cover Grabber

[Book Walker](https://bookwalker.jp)'s often very large volume covers can be very useful for use in making character images or banners, or simply to have a very high quality cover you can immediately upload to the website for the [XL cover](../../image-dimensions-and-template.md) feature.

* Make a new bookmark and paste the following JavaScript in the Address/URL field:

```javascript
javascript:(function(a){var b=document.createElement("textarea"),c=document.getSelection();b.textContent=a,document.body.prepend(b),b.style.position='fixed'}("https://c.bookwalker.jp/coverImage_" + (parseInt($('meta[property="og:image"]').attr('content').split("/")[3].split("").reverse().join(""))-1) + ".jpg"))()
```

* Find the volume you want to use the cover of and press the bookmark

  Example: [紺田照の合法レシピ（１）](https://bookwalker.jp/deae06677d-973d-42d1-bfb3-f24d841dbd13/)

* A box will pop up containing a direct link to the larger image which you can paste into a new tab to access and save. Example: [https://c.bookwalker.jp/coverImage\_1936781.jpg](https://c.bookwalker.jp/coverImage_1936781.jpg)

{% hint style="info" %}
[Image Max URL,](https://qsniyg.github.io/maxurl/) a website and userscript that redirects images to the original versions, has Bookwalker functionality included as of [0.74](https://github.com/qsniyg/maxurl/commit/5d5a77c08f9461c5d7c4ceac209fca240b776d7b#diff-27f9d4a32bb1055d6e25712679ce34afR21594) - [https://github.com/qsniyg/maxurl](https://github.com/qsniyg/maxurl).

Please be aware that the userscript affects a large number of sites, which may not be desired.
{% endhint %}

