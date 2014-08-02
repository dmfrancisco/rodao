## Ródão

Ródão is a minimalist theme for [Ghost](https://github.com/TryGhost), the free and open blogging platform. It is heavily based on two great open source themes, [Clonium](https://github.com/cparaiso/clonium) and [Readium](https://github.com/starburst1977/Readium). Ródão was named after a lovely town in Portugal, [Vila Velha de Ródão](http://dmfranc.com/assets/rodao.jpg).

### Features

- Responsive design
- Infinite scrolling
- Blurry scrolling (like Medium does — the background blurs as the page is scrolled down)
- Enhances progressively (and works when the client has JavaScript disabled)
- Support for Disqus comments
- Support for Google Universal Analytics

### Getting started

Installing Ródão on your blog is straight forward:

1. Clone this repository and place it in `content/themes` alongside Casper, the default theme
2. Add two background images to the `assets/images` directory called `bgd.jpg` and `bgd-blurred.jpg` to display in the index page (the second one is used to create a simple blurry scrolling like Medium does).

Now open the `partials/config.hbs` file and set the following settings (optional):

- `googleAnalyticsID`: Your Google Analytics tracking ID
- `googleAnalyticsURL`: Your Google Analytics default URL (your domain)
- `disqusShortname`: Your Disqus forum shortname

To switch to the newly added theme:

1. Restart Ghost. At the moment, Ghost won't notice that you've added a new folder so you'll need to restart it
2. Login to your Ghost admin, and navigate to `/ghost/settings/general/`
3. Select your Theme name in the 'Theme' options dropdown
4. Click 'Save'
5. Visit the frontend of your blog and marvel at the new theme!

---

### Copyright & License

Copyright (c) 2013-2014 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
