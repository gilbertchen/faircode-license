# The Faircode License

Table of Contents
- [The license](#the-license-version-021)
- [Roadmap to 1.0](#roadmap-to-10)
- [How can I help?](#how-can-i-help)
- [Kickstarter backers](#kickstarter-backers)
- [FAQ](#faq)
  - [How do I use an alpha license?](#how-do-i-use-an-alpha-license)
  - [What happens if a Faircode Licensed project is abandonded by it's creator?](#what-happens-if-a-faircode-licensed-project-is-abandonded-by-its-creator)
  - [Doesn’t that mean anyone can steal the software and start charging for that instead?](#doesnt-that-mean-anyone-can-steal-the-software-and-start-charging-for-that-instead)
  - [What stops companies from using that clause in MIT to just not pay for the project?](#what-stops-companies-from-using-that-clause-in-mit-to-just-not-pay-for-the-project)
  - [Where can I read more?](#where-can-i-read-more)
  - [Who's behind this?](#whos-behind-this)
- [License to use this license](#license-to-use-this-license)

This is the public repository of the Faircode License. It's a young and experimental license for people who want to make a living from their code by selling licenses to companies and organizations (but keep their code free for individuals and small businesses). It's meant to be an alternative to, or complement to, [OSI](https://opensource.org/) Open Source licenses.

The goals for this license are:

- It should foster collaboration, openness and creativity.
- It should enable creators of software to charge for their work.
- It should be short and comprehensible.
- It should be easy and clear for companies to work with, even when licensing thousands of packages.
- It should not dictate what you do with the income. For-profit or for-charity should work equally well.

There are two ways to use the license:

- Use it as the single license of your project.
- Dual license with an Open Source license. This makes your project both OSI Open Source and Faircode, and users of it may choose to license it under either terms. Usually this is done with a protective copyleft license, such as GPLv3 which requires users to contribute back to Open Source by releasing anything built with it under the same license.

The motivation behind creating this license is that we want to enable people to work on what they're passionate about. If you love programming, and you're creating something awesome, you should be able to easily charge those who can afford it, so that you can keep developing it. We're programmers ourselves and would like to have the opportunity to do this ourselves. We also think this is in the interest of companies, who by paying for the software they rely on can increase chances it doesn't become abandoned as the developers get burned out.

Although the license is made to work well on the [Faircode](https://faircode.io) platform, we don't want it to be limited to that. It should work equally well if you want to use it independently or with other platforms.

## The license (version 0.2.1)

This is the full license text and can be copied into your repository.

```
## {Project name} license (Faircode v0.2.1)

Copyright (C) {Year} {Copyright holder}

Permission is hereby granted to any person obtaining a copy of this software
and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies ("Use") of
the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

If you are a commercial entity with a revenue in excess of 1,000,000 USD of
the previous fiscal year, and/or organization with a budget in excess of
1,000,000 USD, you must acquire a commercial license grant from
{Copyright holder} to Use this software. A commercial license grant can be
acquired at [{Purchase url}]({Purchase url}).

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Roadmap to 1.0

Currently the license is in an alpha stage. The roadmap towards a 1.0 release is as follows:

- Now until Jan 9 2018: **Feedback & comments period.** We'll iterate the license based on how people use it and the feedback we get.
- After Jan 9 2018: **Legal review period.** At this point we get the lawyers involved. We'll clean up any legal kinks and specks that make things needlessly ambiguous or unclear. We'll continuously merge changes back to the repo so people can see what's going on.
- When the review is done: **1.0 release.**

The work doesn't stop after 1.0 though, it's just the first milestone to have a workable license. After that we'll iterate and improve as needed, depending on what real world problems and solutions we see.

## How can I help?

We do not accept PRs, but we do read issues and comments. Feel free to post your feedback; we might not be able to respond to all of it but we'll do our best. We think above all it's important we have a debate about this; the Faircode License is meant to be _a_ solution to a problem, but there will likely be cases where it doesn't fit. Through a debate we may inspire other solutions as well.

Some things we'd love to hear about:

- How you use the Faircode License, or how you want to use it.
- Problems using the Faircode License would raise or is raising for you.
- Problems your company would face if they were to use Faircode licensed code.
- Alternative solutions you are currently employing and how they are working out.
- Analysis of the legal implications of the license.
- And of course, if this license is helping you we'd love to hear about that! Both from companies and developers.

Things we _don't_ have much use for:

- Opinions on Open Source _vs._ Faircode. It's just licenses, and they're solving different needs.

You can also sponsor the [Kickstarter campaign](https://www.kickstarter.com/projects/839120961/the-faircode-license) so we can pay the lawyers. If we raise more than we need for the lawyers, we'll donate the rest to projects on Faircode, by distributing it equally to all Faircode licensed projects on the platform.

And finally, you can help out by letting people know about this repo. Share it with your friends and on social media. We'll use the [@faircodeio](https://twitter.com/faircodeio) account on Twitter to share news.

## Kickstarter backers

See [BACKERS](BACKERS.md).

## FAQ

### How do I use an alpha license?

Keep an eye on this repository as the license evolves. We'll use semver to version it (see changes in the [CHANGELOG](CHANGELOG.md)). We recommend upgrading to the latest version as soon as it comes out. It's not for everyone to try something new like this, but those who do will help shape what this license is and how it's used, and set examples for future developers who want to try something similar.

### What happens if a Faircode Licensed project is abandonded by it's creator?

Sometimes life takes us to places where we can’t continue to support the software we’ve built before. In those cases, it’s important that there’s a path forward for the people who rely on this software. This is why the Faircode License is based on MIT; anyone can pick up the software and start a new project around it, where the development can continue of the software. This is all possible because MIT allows sub-licensing.

### Doesn’t that mean anyone can steal the software and start charging for that instead?

In theory, yes. But there are a few barriers to this to an alive project. Links, search results, stars and downloads all stay with the original project even if someone clones it. The same goes for social media accounts (twitter for instance) and “claimed” names on package repositories (for instance if you publish the package “hello” to npm, and someone clones it, “hello” on npm will still point to your repository). None of this is watertight, but “overtaking” someones project is also not as easy as just cloning it and starting to charge for it.

### What stops companies from using that clause in MIT to just not pay for the project?

Again in theory, a company can ask someone (they couldn’t do it themselves because then they’d need to pay for it) to clone your project, re-license it and then publish that and use it. If the company you work at suggest doing this, you should seriously consider alternative employers.

### Where can I read more?

- [Hacker News discussion: Changing the Ungit license from MIT to Faircode](https://news.ycombinator.com/item?id=15628786)
- [Issue on the Ungit repo](https://github.com/FredrikNoren/ungit/issues/974)

### Who's behind this?

[Fredrik Norén](https://github.com/FredrikNoren) is the original author and owner of the repo. But anyone who wants to get involved is part of it. The license is for you.

## License to use this license

Finally, the license is to be considered free and fully available to anyone and everyone. You may use it, copy it, create derivatives and do whatever you want with it. Use it at your own risk, we take no responibility in any damages caused in the usage of this license. Make sure you've read and understood it before applying it to your project.
