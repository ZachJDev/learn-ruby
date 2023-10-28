<!-- omit in toc -->
# Learn Ruby: a resource list

Hi! As a second-career developer who didn't go through a bootcamp, I've found it helpful to keep a road map of learning resources—building my own curriculum, in a way. I hope this list helps you too!

If you notice any broken links here, please let me know by [opening an issue](https://github.com/fpsvogel/learn-ruby/issues/new).

<!-- omit in toc -->
## Table of contents

The "not done" sections (currently "Fundamental tools" and below) are somewhat chaotic because I haven't yet seen what's worth keeping there.

- [Preliminaries](#preliminaries)
- [Basics](#basics)
  - [Front-end basics](#front-end-basics)
  - [Ruby basics](#ruby-basics)
  - [Rails basics](#rails-basics)
  - [Getting hired](#getting-hired)
  - [Ruby/Rails communities](#rubyrails-communities)
- [Fundamental tools](#fundamental-tools)
  - [SQL](#sql)
  - [Git](#git)
  - [How the Internet works](#how-the-internet-works)
  - [Linux / command line](#linux--command-line)
- [Advanced Ruby and Rails](#advanced-ruby-and-rails)
  - [Advanced Ruby](#advanced-ruby)
  - [Advanced Rails](#advanced-rails)
- [Front end](#front-end)
  - [Web standards](#web-standards)
  - [Hotwire](#hotwire)
- [Expanding my horizons](#expanding-my-horizons)
- [Games in Ruby](#games-in-ruby)
- [Ruby blogs, podcasts, screencasts](#ruby-blogs-podcasts-screencasts)
- [Rails codebases to study](#rails-codebases-to-study)

## Preliminaries

- **If you want to keep it simple** and use just *one* resource that can take you from zero to hireable, I suggest the free [Odin Project](https://www.theodinproject.com/paths). If you want more variety and more depth on certain topics, keep reading!
- **If you're wondering why I chose Ruby** and not full-stack JavaScript, [I explain why on my blog](https://fpsvogel.com/posts/2021/why-learn-ruby). And [here's a second opinion](https://medium.com/learn-love-code/why-teach-ruby-bac8416c77ba) by the founder of a bootcamp that teaches Ruby.
- **Make sure your day job is conducive to part-time studying** if you're a working adult looking to switch careers. I used to be a teacher and spent hours grading in the evenings and on weekends, which would have made studying very difficult. So I switched to a remote customer support job to free up my schedule.
- **Find a system for keeping *organized* notes**, code snippets, and bookmarked links. I use [a simple text file](https://fpsvogel.com/posts/2021/plain-text-knowledge-base).
- **You should spend more time *coding* than *reading about* coding**. I mention this because below I list lots of books and courses but not many hands-on projects. Why? Because starting a project and getting into a coding routine is easy (if you can't think of any project ideas, try these lists: [1](https://github.com/codecrafters-io/build-your-own-x), [2](https://github.com/practical-tutorials/project-based-learning#ruby), [3](https://projectbook.code.brettchalupa.com)), whereas knowing what to read/study is not at all obvious at the beginning. Hence the focus on books and courses here.
- **Last but not least, take care of yourself!** Exercise and get plenty of sleep, and you'll better retain what you learn. If you develop wrist pain from heavy computer use, act swiftly: get an ergonomic keyboard ([the one I use](https://fpsvogel.com/posts/2021/keyboardio-atreus) has a learning curve, but I love it *and* it was affordable), [do daily wrist stretches](https://youtube.com/watch?v=fdD7CgN5FGg), and try using a break app such as [Workrave](https://workrave.org/).

Without further ado, here is my learning road map. Resources marked with a dollar sign (💲) cost money. You may be able to find books for free (from your local library, interlibrary loan, or more dubious sources) but buy them if/when you can, to support the authors.

## Basics

### Front-end basics

- **Learn some HTML, CSS, and JavaScript:**
  - [x] [The Odin Project - Foundations path](https://www.theodinproject.com/paths/foundations/courses/foundations). Or if that doesn't click with you, try resources under ["Front end"](#front-end) below.
- **Build a blog from scratch:**
  - [x] [Here's the first iteration of my blog](https://fpsvogel-2020.netlify.app), and [here's how I built it](https://fpsvogel.com/posts/2020/zs). Building a blog is not only a good exercise in itself, but it might also give you extra motivation to write about what you learn.

### Ruby basics

- **Basics:**
  - [x] [The Odin Project - Ruby](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby)
  - [x] [GoRails - Ruby for Beginners](https://gorails.com/series/ruby-for-beginners) if you prefer videos.
  - [x] [Try Ruby](https://try.ruby-lang.org/) and [BigBinary Academy](https://academy.bigbinary.com/learn-ruby) if you prefer an interactive approach.
  - [x] [The Well-Grounded Rubyist](https://livebook.manning.com/book/the-well-grounded-rubyist-third-edition) if you prefer an in-depth book. [Here's a discount code.](https://freecontent.manning.com/slideshare-ruby-for-everyone/)
- **Guided practice:**
  - [x] [Exercism](https://exercism.org/tracks/ruby). Be sure to take notes each time you learn something new in an exercise, and at the end you could write up your reflections ([here are mine](https://fpsvogel.com/posts/2020/exercism-ruby)).
- **OOP:**
  - [x] 💲[Sandi Metz - Practical Object-Oriented Design](https://www.poodr.com)
  - [x] 💲[Sandi Metz & Katrina Owen - 99 Bottles of OOP](https://sandimetz.com/99bottles-sample-ruby)
- **Build stuff with Ruby.** Here are some ideas:
  - [x] A CLI (command-line interface) app. I made [one that gives statistics on a reading log](https://fpsvogel.com/posts/2021/my-first-ruby-app-lessons-learned).
  - [x] A game. See the [Games in Ruby](#games-in-ruby) section.
  - [x] A site using [Bridgetown](https://github.com/bridgetownrb/bridgetown). Maybe [rebuild your blog](https://fpsvogel.com/posts/2021/build-a-blog-with-bridgetown)? Be sure to [join the Bridgetown Discord server](https://discord.gg/Cugms94QFM)—the maintainers are very welcoming and helpful to newbies.
- **Reference:**
  - [x] [Ruby API](https://rubyapi.org). Mentioning it up here because it's the best Ruby docs site but very little-known. Since its search uses a query param, you can add a search keyword to your browser to let you quickly search from the address bar, for example "rb partition" would take you to https://rubyapi.org/3.2/o/s?q=partition

### Rails basics

Only books and courses are listed below, but be sure to *build things* as you learn. I myself [started building a large-ish Rails app](https://fpsvogel.com/posts/2021/first-rails-app-plain-reading) at first, but then I found it more helpful to build a series of small throwaway apps ([1](https://fpsvogel.com/posts/2021/gpt3-ai-story-writer), [2](https://fpsvogel.com/posts/2021/wikipedia-explorer-discover-articles-like-stumbleupon), [3](https://fpsvogel.com/posts/2021/pass-the-story-collaborative-writing-game), [4](https://fpsvogel.com/posts/2022/doctor-lookup-health-provider-search-tool)).

- **Rails basics:**
  - [x] [GoRails - Build a Blog with Ruby on Rails](https://gorails.com/series/build-a-blog-with-rails-7)
  - [x] [The Odin Project - Rails](https://www.theodinproject.com/paths/full-stack-ruby-on-rails)
- **Testing:**
  - [x] 💲[Jason Swett - The Complete Guide to Rails Testing](https://www.codewithjason.com/complete-guide-to-rails-testing/)
  - [x] 💲[Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/effective-testing-with-rspec-3/)
  - [x] 💲[The Minitest Cookbook](https://chriskottom.com/minitestcookbook)
- **Polishing up:**
  - [x] [Style guides](https://ruby.style/) for Ruby, Rails, and RSpec

### Getting hired

- **Get real-world experience to put on your resume:**
  - Contribute to open source projects. I've written [a short guide on how to get started](https://fpsvogel.com/posts/2021/how-to-contribute-to-open-source-ruby-rails).
  - Apply to become a member of [The Agency of Learning](https://agencyoflearning.com/).
- **The job search:**
  - [Notes on my job search in 2021-2022](https://fpsvogel.com/posts/2022/how-to-find-ruby-rails-job)

### Ruby/Rails communities

Here are some places where you can learn with others or ask questions when you get stuck.

- **Communities:**
  - [Ruby on Rails Link community on Slack](https://www.rubyonrails.link/)
  - [Code with Jason Meetup](https://www.codewithjason.com/meetup)
- **Newsletters:**
  - [Short Ruby](https://newsletter.shortruby.com/)
  - [Ruby Weekly](https://rubyweekly.com/)
  - [Ruby Radar](https://rubyradar.dev/)
- **Mentorship:** I got mentorship about a year after starting with Rails, but you may benefit from it earlier.
  - [First Ruby Friend](https://firstrubyfriend.org) where aspiring and first-year developers are connected with a mentor.
  - [The Rails subreddit](https://www.reddit.com/r/rails) is another good place to find a mentor. It's not uncommon for someone to post asking if anyone is available to mentor, and these posts typically get quite a few replies from potential mentors.

## Fundamental tools

### SQL

- [x] [SQL Teaching](https://www.sqlteaching.com)
- [x] [SQLBolt](https://sqlbolt.com)
- [x] [Select Star SQL](https://selectstarsql.com)
- [ ] [SQL Murder Mystery](https://mystery.knightlab.com/)
- [x] [SQLZoo](https://sqlzoo.net/wiki/SQL_Tutorial)
- [x] [Next-Level Database Techniques for Developers](https://sqlfordevs.com/ebook)
- [ ] 💲[SQL Antipatterns, Volume 1](https://pragprog.com/titles/bksap1/sql-antipatterns-volume-1/)
- [ ] [Markus Winand - Use the Index, Luke!](https://use-the-index-luke.com/sql/preface)
- [ ] 💲[Markus Winand - SQL Performance Explained](https://sql-performance-explained.com)
- [ ] [Advanced Topics in SQL](https://www.edx.org/course/advanced-topics-in-sql) course from Stanford
- [ ] [Postgres Playground](https://www.crunchydata.com/developers/tutorials)
- [ ] [Yeah, Postgres can do that](https://dev.to/efertsch/series/20415)
- [ ] 💲[High Performance PostgreSQL for Rails](https://pragprog.com/titles/aapsql/high-performance-postgresql-for-rails/)
- [ ] Blog posts on Rails + Postgres: [lots on Paweł Urbanek's blog](https://pawelurbanek.com/blog), [this one at Honeybadger](https://www.honeybadger.io/blog/rails-postgresql-queries/), [this one at Thoughtbot](https://thoughtbot.com/blog/advanced-postgres-performance-tips).
- [ ] 💲[The Art of PostgreSQL](https://theartofpostgresql.com/)
- [ ] 💲[PostgreSQL Query Optimization: The Ultimate Guide to Building Efficient Queries](https://link.springer.com/book/10.1007/978-1-4842-6885-8)

### Git

- [x] [Oh My Git!](https://ohmygit.org/)
- [x] [Oh Shit, Git!?!](https://ohshitgit.com/)
- [x] [Git Katas](https://github.com/eficode-academy/git-katas)
- [x] [The Git Parable](https://youtube.com/watch?v=ANNboouhNHE)
- [x] [Git Flight Rules](https://github.com/k88hudson/git-flight-rules)
- [x] [Thoughtbot - Rebuilding Git in Ruby](https://thoughtbot.com/blog/rebuilding-git-in-ruby)
- [ ] [Pro Git](https://git-scm.com/book)
- [ ] 💲[Building Git](https://shop.jcoglan.com/building-git)

### How the Internet works

- [ ] [Computer Networks from Scratch](https://www.networksfromscratch.com) (WIP, and possibly abandoned because Ch. 5 has been "coming soon" for a year now)
- [ ] 💲[Web Security for Developers: Real Threats, Practical Defense](https://www.amazon.com/Web-Security-Developers-Malcolm-McDonald-ebook/dp/B07V78WH7V) and the accompanying site [Hacksplaining](https://www.hacksplaining.com/)
- [ ] [MDN Web Doc on HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [x] 💲[Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/eighth.htm)
- [ ] [Jesse Storimer - Working with TCP Sockets](https://workingwithruby.com/wwtcps/intro)
- [ ] Build a web server from scratch. Here are Ruby resources:
  - [Ruby HTTP server from the ground up](https://www.dmitry-ishkov.com/2021/07/ruby-http-server-from-ground-up.html)
  - [How to Build a Web App with and without Rails Libraries](https://shopify.engineering/building-web-app-ruby-rails)
  - [A Reddit discussion with helpful comments](https://www.reddit.com/r/ruby/comments/vfc02l/newb_here_have_you_written_your_own_web_server)

### Linux / command line

- [x] Install and use Linux. [My post on switching to Linux](https://fpsvogel.com/posts/2023/switch-to-linux-from-windows) might give you some pointers.
- [ ] 💲[How Linux Works](https://nostarch.com/howlinuxworks3)
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- [ ] [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
- [ ] ["Linux CLI and shell scripting" list](https://learnbyexample.github.io/curated_resources/linux_cli_scripting.html)
- [ ] [Julia Evans - Your Linux Toolbox](https://jvns.ca/blog/2019/10/21/print-collection-of-my-first-7-zines/)
- [ ] 💲[Julia Evans - Bite Size zine pack](https://wizardzines.com/zines/bite-size-pack/)
- [ ] 💲[Julia Evans - How Containers Work](https://wizardzines.com/zines/containers/)
- [ ] 💲[Wicked Cool Shell Scripts](https://nostarch.com/wcss2)
- [ ] [Jesse Storimer - Working with Unix Processes](https://workingwithruby.com/wwup/intro)
- [ ] 💲[Josef Strzibny - Deployment from Scratch](https://deploymentfromscratch.com/)

## Advanced Ruby and Rails

### Advanced Ruby

- **Reference:**
  - [ ] Victor Shepelev (zverok) - [The Ruby Reference](https://rubyreferences.github.io/rubyref/) (Ruby 2.7) plus [Ruby Changes](https://rubyreferences.github.io/rubychanges/3.0.html) (for Ruby 3+). [Ruby Evolution](https://rubyreferences.github.io/rubychanges/evolution.html) is also great.
  - [ ] [RuboCop performance rules](https://github.com/rubocop/rubocop-performance)
  - [ ] [RuboCop security rules](https://docs.rubocop.org/rubocop/cops.html#department-security)
- **Scripting:**
  - [x] [Enhanced Shell Scripting with Ruby](https://www.devdungeon.com/content/enhanced-shell-scripting-ruby)
  - [x] 💲[Text Processing with Ruby](https://pragprog.com/titles/rmtpruby/text-processing-with-ruby)
  - [x] [Ruby Regexp](https://learnbyexample.github.io/Ruby_Regexp)
  - [x] [Ruby one-liners cookbook](https://learnbyexample.github.io/learn_ruby_oneliners/)
  - [x] Tools for Ruby on the command line: [ru](https://github.com/tombenner/ru), [rb](https://github.com/thisredone/rb), [pru](https://github.com/grosser/pru), [rexe](https://github.com/keithrbennett/rexe)
- **Concurrency:**
  - [ ] [Jesse Storimer - Working with Ruby Threads](https://workingwithruby.com/wwrt/intro)
  - [ ] [Async Ruby](https://brunosutic.com/blog/async-ruby)
- **Learn other app frameworks:** Jobs in Ruby are mostly in Rails, but it's still valuable to broaden my horizons and learn different approaches.
  - [x] [Roda](https://roda.jeremyevans.net/) via [an example Roda app using Hotwire](https://github.com/janko/budget)
  - [ ] [Hanami](https://hanamirb.org/) which will be easier to get started with once it hits 2.1. Example apps:
    - [github.com/decafsucks/decafsucks](https://github.com/decafsucks/decafsucks)
    - [github.com/bkuhlmann/hemo](https://github.com/bkuhlmann/hemo)
    - [github.com/katafrakt/palaver](https://github.com/katafrakt/palaver)

### Advanced Rails

- **Reference:**
  - [x] 💲[Noah Gibbs - Rebuilding Rails](http://rebuilding-rails.com/)
  - [ ] [Rails Guides](https://guides.rubyonrails.org/)
  - [ ] [Rails API docs](https://api.rubyonrails.org/)
- **Architecture:**
  - [x] 💲[Layered Design for Ruby on Rails Applications](https://www.amazon.com/Layered-Design-Ruby-Rails-Applications/dp/1801813787)
  - [ ] [Litestack](https://github.com/oldmoe/litestack)
  - [ ] 💲[Learning Domain-Driven Design](https://www.oreilly.com/library/view/learning-domain-driven-design/9781098100124/) (not Rails-specific)
  - [ ] [Gradual Modularization for Ruby and Rails](https://leanpub.com/package-based-rails-applications)
- **Performance:**
  - [ ] 💲[Nate Berkopec - The Complete Guide to Rails Performance](https://www.railsspeed.com/)
  - [ ] 💲[Nate Berkopec - The Ruby on Rails Performance Apocrypha](https://www.speedshop.co/2021/01/14/announcing-apocrypha.html)
  - [ ] [Mature Optimization Handbook](https://carlos.bueno.org/optimization/) (not Rails-specific)
- **Background jobs:**
  - [ ] 💲[Nate Berkopec - Sidekiq in Practice](https://nateberk.gumroad.com/l/sidekiqinpractice)
  - [ ] [AcidicJob](https://github.com/fractaledmind/acidic_job)

## Front end

### Web standards

- **HTML:**
  - [ ] [MDN - Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
  - [ ] [MDN - HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
  - [ ] [htmlreference.io](https://htmlreference.io/)
- **CSS:**
  - [ ] 💲[The Spicy Web - CSS Nouveau](https://www.spicyweb.dev/css-nouveau)
  - [ ] [MDN - CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
  - [ ] [cssreference.io](https://cssreference.io/)
  - [ ] [CSS Selectors: A Visual Guide & Reference](https://fffuel.co/css-selectors/)
  - [ ] [The Odin Project - Intermediate HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/intermediate-html-and-css)
  - [ ] [The Odin Project - Advanced HTML and CSS](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/advanced-html-and-css)
  - [ ] [CUBE CSS](https://cube.fyi)
  - [ ] [Every Layout](https://every-layout.dev/)
  - [ ] [Magic of CSS](https://adamschwartz.co/magic-of-css/)
  - [ ] [Under-Engineered Patterns](https://adrianroselli.com/2023/05/under-engineered-patterns-for-wcbuf.html)
  - [ ] [Stephanie Eckles - Modern CSS Solutions](https://moderncss.dev/)
  - [ ] [Stephanie Eckles - SmolCSS](https://smolcss.dev/)
  - [ ] [CSS Naked Day](https://css-naked-day.github.io/)
  - [ ] 💲[Julia Evans - Hell Yes! CSS!](https://wizardzines.com/zines/css/)
  - [ ] [Modern Font Stacks](https://modernfontstacks.com/#font-stacks)
  - [ ] [Type Is Design: Fix Your UI with Better Typography and CSS](https://www.youtube.com/watch?v=1Pe7oGIKkqc)
- **CSS games:**
  - [ ] [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies)
  - [ ] [Grid Critters](https://gridcritters.com/)
  - [ ] [CSS Diner](https://flukeout.github.io/)
  - [ ] [Flexbox Froggy](https://flexboxfroggy.com/)
  - [ ] [CSS Grid Garden](https://cssgridgarden.com/)
  - [ ] [CSSBattle](https://cssbattle.dev/)
- **Practice:**
  - [ ] [Codewell](https://www.codewell.cc/)
  - [ ] [Frontend Mentor](https://www.frontendmentor.io/)
  - [ ] [Frontend Practice](https://www.frontendpractice.com/)
- **Accessibility:**
  - [ ] [Responsible Web Applications](https://responsibleweb.app/)
  - [ ] [web.dev - Learn Accessibility](https://web.dev/learn/accessibility/) (among [their other courses](https://web.dev/learn/))
  - [ ] In Rails: [Accessibility is a Requirement](https://www.youtube.com/watch?v=BF3D_IqOknk), [Accessible by Default](https://www.youtube.com/watch?v=4j2zlvE_Yj8)
- **JavaScript:**
  - [ ] [MDN - JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) tutorials
  - [ ] [The Odin Project - JavaScript](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/javascript)
  - [ ] [JavaScript for impatient programmers](https://exploringjs.com/impatient-js/)
  - [ ] [What the heck is the event loop anyway?](https://youtube.com/watch?v=8aGhZQkoFbQ)
  - [ ] [The Modern JavaScript Tutorial](https://javascript.info/)
  - [ ] [JavaScript30](https://javascript30.com/) for practice
- **Web components:**
  - [ ] [Rob Eisenberg - "Hello Web Components"](https://eisenbergeffect.medium.com/hello-web-components-795ed1bd108e)
  - [ ] [Dave Rupert - HTML with Superpowers: The Guidebook](https://daverupert.com/2023/01/html-with-superpowers-the-guidebook/) or 💲[the course version](https://frontendmasters.com/courses/web-components/)
  - [ ] [Web components section](https://javascript.info/web-components) in the Modern JavaScript Tutorial
  - [ ] [Web Components Today](https://webcomponents.today/)
  - [ ] [Lit docs](https://lit.dev/)
  - [ ] Explore component libraries: [Shoelace](https://shoelace.style/), [Nord](https://nordhealth.design/components/)
  - [ ] Read [the Shoelace source code](https://github.com/shoelace-style/shoelace)
  - [ ] 💲[Fullstack Web Components: Complete Guide to Building UI Libraries with Web Components](https://www.newline.co/courses/fullstack-web-components)
  - [ ] Build a UI following [Jared White - How Ruby and Web Components Can Work Together](https://www.fullstackruby.dev/fullstack-development/2022/01/04/how-ruby-web-components-work-together/)
  - [ ] Experiment using [Turbo](https://turbo.hotwired.dev/) to drive front-end behavior: *"Turbo 7.2.0 (currently in beta) allows you to define your own Stream actions which can be any JS code you want. By combining a custom Stream action or two with web components, you can essentially drive reactive frontend behavior from the backend stupidly easily. Loooove it! 😍 […] For a turnkey example, you could check out https://github.com/hopsoft/turbo_ready "* —Jared White on [The Spicy Web](https://discord.com/channels/811491992285741077/811493083068760104/1019024338042761297) Discord
- **UI and usability:**
  - [x] 💲[Don't Make Me Think](https://sensible.com/dont-make-me-think/)
  - [x] 💲[The Design of Everyday Things](https://www.nngroup.com/books/design-everyday-things-revised/)
  - [ ] [Growth.Design](https://growth.design/)
  - [ ] [Roast My Landing Page blog](https://blog.roastmylandingpage.com/)
  - [ ] [George Moller - UI tips](https://georgemoller.gumroad.com/)
  - [x] [Victor Ponamariov - 50 UI Tips](https://fifty.user-interface.io/50_ui_tips.pdf)
  - [ ] [Victor Ponamariov - How to design almost any UI element](https://user-interface.io/articles/how-to-design-almost-any-ui-element)
  - [ ] 💲[Victor Ponamariov - 100 UI/UX Tips & Tricks](https://akcium.gumroad.com/l/ui-ux-tips) (or on [the landing page](https://hundred.user-interface.io/))
  - [ ] 💲[Victor Ponamariov - Re:Form](https://reform.user-interface.io/)
  - [ ] 💲[Master UI Design](https://www.masteruibook.com/)
  - [ ] 💲[Refactoring UI](https://www.refactoringui.com/book)

### Hotwire

- **Community and news:**
  - [StimulusReflex community on Discord](https://discord.com/invite/stimulus-reflex)
  - [Hotwire dev newsletter](https://masilotti.com/hotwire/)
  - [The Hotwire Club](https://hotwire.club/)
- **Basics:**
  - [ ] [What is the difference between Turbo and Stimulus, and what exactly is Hotwire?](https://www.ducktypelabs.com/turbo-vs-stimulus/)
  - [ ] [Hotwire.io](https://hotwire.io) (better than the official docs site)
  - [ ] [Write Software, Well - A Brief Introduction to Hotwire](https://www.writesoftwarewell.com/introduction-to-hotwire/)
  - [ ] [Write Software, Well - You Don't Need Rails to Start Using Hotwire](https://www.writesoftwarewell.com/using-hotwire-without-rails/)
  - [ ] [Write Software, Well - Turbo Streams: How They Work and Differ From Turbo Frames](https://www.writesoftwarewell.com/understanding-hotwire-turbo-streams/)
  - [ ] Evil Martians [talk](https://www.youtube.com/watch?v=sIxvxp7E0xg) and [blog post](https://evilmartians.com/chronicles/hotwire-reactive-rails-with-no-javascript)
  - [ ] [Alexandre Ruban - Turbo Rails Tutorial](https://www.hotrails.dev/)
  - [ ] [David Colby - Turbo Rails 101](https://www.colby.so/posts/turbo-rails-101-todo-list)
  - [ ] [Hotwire Handbook, Part 1](https://philreynolds.dev/posts/2022/hotwire-handbook-part-1), [Part 2](https://purpleriver.dev/posts/2023/hotwire-handbook-part-2-redux), [Part 3](https://purpleriver.dev/posts/2023/hotwire-handbook-part-3)
  - [ ] [30 days of Hotwire tips](https://twitter.com/ilrock__/status/1631315562390519809) which turned into the book 💲[Hotwire Cookbook](https://www.hotwirecookbook.com/)
  - [ ] [Andrea Fomera - Learn Hotwire by Building a Forum](https://store.afomera.dev/learn-hotwire)
  - [ ] [David Colby - Hotwired ATS: Modern, full-stack Rails development](https://book.hotwiringrails.com/)
  - [ ] [Hotwire Cases](https://hotwiredcases.dev)
- **Screencasts and blogs:**
  - [ ] [Mix & Go screencasts on Hotwire](https://www.youtube.com/playlist?list=PLBhH0uX92r6oiwiLBjdE-3NNsyRqyLAV9)
  - [ ] [SupeRails screencasts on Hotwire](https://www.youtube.com/playlist?list=PLdTytUiloS16epXsqHswpCUMND_rksjr4)
  - [ ] [Rapid Ruby screencasts on Hotwire](https://www.youtube.com/playlist?list=PL2OcwqOUtdpCqddncOH61f0phQKtum3yQ)
  - [ ] [SupeRails blog](https://blog.corsego.com) which includes even more Hotwire tips.
  - [ ] [David Colby's blog](https://www.colby.so)
- **Examples and snippets:**
  - [ ] [Hotwire examples](https://github.com/thoughtbot/hotwire-example-template/branches/active) from Thoughtbot
  - [ ] [Better Stimulus](https://www.betterstimulus.com/)
  - [ ] [Stimulus-Use](https://stimulus-use.github.io/stimulus-use)
  - [ ] [Stimulus Components](https://www.stimulus-components.com/) for inspiration
- **Hotwire extensions:**
  - [ ] [TurboPower](https://github.com/marcoroth/turbo_power-rails)
  - [ ] [TurboBoost Commands](https://github.com/hopsoft/turbo_boost-commands)
  - [ ] [TurboBoost Streams](https://github.com/hopsoft/turbo_boost-streams)
  - [ ] [TurboBoost Elements](https://github.com/hopsoft/turbo_boost-elements)
- **Multi-platform:**
  - [ ] 💲[Ayush Newatia - The Rails and Hotwire Codex](https://railsandhotwirecodex.com/)
- **Other similar libraries:**
  - [ ] [HTMX](https://htmx.org/): read the book [Hypermedia Systems](https://hypermedia.systems) and/or watch [Carson Gross — Return To Hypermedia: Solving Javascript Fatigue Using Fundamental Web Architecture](https://youtube.com/watch?v=LRrrxQXWdhI)

## Expanding my horizons

- **Be a mentor:**
  - [x] [Exercism](https://exercism.org/mentoring)
  - [ ] [First Ruby Friend](https://firstrubyfriend.org/mentors)
- **Career advancement:**
  - [ ] [The Software Engineer's Guidebook](https://www.engguidebook.com)
  - [ ] [The Tech Resume Inside Out](https://thetechresume.com/)
- **Computer science:**
  - [x] 💲[Code: The Hidden Language of Computer Hardware and Software](https://www.informit.com/store/code-the-hidden-language-of-computer-hardware-and-software-9780137909100)
  - [ ] [NandGame](https://nandgame.com)
  - [x] *From Nand to Tetris* course ([Part 1](https://www.coursera.org/learn/build-a-computer), [Part 2](https://www.coursera.org/learn/nand2tetris2)), optionally with the textbook 💲[The Elements of Computing Systems: Building a Modern Computer from First Principles](https://mitpress.mit.edu/books/elements-computing-systems-second-edition)
  - [x] 💲[Data Structures and Algorithms in Java](https://www.amazon.com/Data-Structures-Algorithms-Java-2nd/dp/0672324539)
  - [ ] 💲[The Algorithm Design Manual](https://www.algorist.com/) plus [lecture videos](https://www3.cs.stonybrook.edu/~skiena/373/videos/)
  - [x] 💲[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP/)
  - [ ] 💲[Computer Systems: A Programmer's Perspective](https://csapp.cs.cmu.edu/)
  - [ ] [Crafting Interpreters](https://craftinginterpreters.com/)
- **Coding challenges:**
  - [ ] [CodeWars](https://www.codewars.com)
  - [ ] [Advent of Code](https://adventofcode.com/2022/events)
  - [ ] [Project Euler](https://projecteuler.net/)
  - [ ] Gilded Rose kata: tests [included](https://github.com/knowndecimal/gilded_rose_kata) or [not](https://github.com/emilybache/GildedRose-Refactoring-Kata), plus [Sandi Metz's talk](https://www.youtube.com/watch?v=8bZh5LMaSmE)
  - [ ] [Exercises at cyber-dojo](https://cyber-dojo.org/creator/choose_problem) (or see [the source code](https://github.com/cyber-dojo/exercises-start-points/tree/main/start-points))
  - [ ] [Kata compiled by Emily Bache](https://github.com/emilybache?tab=repositories&sort=stargazers)
  - [ ] [Kata at Coding Dojo](https://codingdojo.org/kata/)
  - [ ] [Kata at CodeKata](http://codekata.com/)
  - [ ] Kata by Luca Minudel: [Refactoring legacy code driven by tests](https://github.com/lucaminudel/TDDwithMockObjectsAndDesignPrinciples/tree/master/TDDMicroExercises#readme), [Tensions and synergies between design principles](https://github.com/lucaminudel/tensions_and_synergies_between_design_principles/blob/master/README.md), [Objects relationships](https://github.com/lucaminudel/Objects-relationships-Coding-Dojo/blob/master/README.md)
  - [ ] [Awesome Katas](https://github.com/gamontal/awesome-katas)
  - [ ] [A curated list of programming kata](https://hackmd.io/@pierodibello/A-curated-list-of-programming-kata)
- **Design patterns:**
  - [x] 💲[Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/9781492077992/)
  - [x] [Refactoring.Guru](https://refactoring.guru/)
  - [ ] [Thoughtbot - Ruby Science](https://thoughtbot.com/ruby-science) (or [EPUB/PDF](https://thoughtbot.gumroad.com/l/ruby-science))
- **Monitoring:**
  - [ ] 💲[Practical Monitoring](https://www.oreilly.com/library/view/practical-monitoring/9781491957349/)
  - [ ] 💲[Observability Engineering](https://www.oreilly.com/library/view/observability-engineering/9781492076438/)
- **Documentation**
  - [ ] [Divio Documentation System](https://documentation.divio.com/) (a.k.a. [Diataxis](https://diataxis.fr/))
- **Learn Crystal:** Whenever you need to make an isolated bit of Ruby code run faster than Ruby can run, porting it to Crystal is easy because they're so similar.
  - [ ] [Crystal for Rubyists (doc page)](https://crystal-lang.org/reference/1.9/crystal_for_rubyists/index.html)
  - [ ] [Crystal for Rubyists (book)](https://www.crystalforrubyists.com/)
  - [ ] [Crystal on Exercism](https://exercism.org/tracks/crystal)
  - [ ] [Crystal Koans](https://github.com/ilmanzo/crystal-koans)
  - [ ] Learn how to offload CPU-intensive tasks from a Ruby app into Crystal. There are several approaches ([1](https://github.com/contribsys/faktory), [2](https://github.com/hugopl/sidekiq.cr), [3](https://github.com/crimson-knight/fruit_juice), [4](https://www.youtube.com/watch?v=sTGfi98XXS4)).
- **Learn functional programming:**
  - [ ] 💲[Data-Oriented Programming: Reduce software complexity](https://livebook.manning.com/book/data-oriented-programming)
  - [ ] 💲[Grokking Simplicity: Taming complex software with functional thinking](https://livebook.manning.com/book/grokking-simplicity)
  - [ ] [Wikibooks - Haskell](https://en.wikibooks.org/wiki/Haskell)
  - [ ] [Functional Programming in Haskell](https://www.youtube.com/playlist?list=PLF1Z-APd9zK7usPMx3LGMZEHrECUGodd3)
  - [ ] [Codeworld - Haskell](https://code.world/haskell)
  - [ ] [The Haskell Phrasebook](https://typeclasses.com/phrasebook)
  - [ ] 💲[Effective Haskell](https://pragprog.com/titles/rshaskell/effective-haskell/)
  - [ ] 💲[Algebra-Driven Design](https://leanpub.com/algebra-driven-design/)
  - [ ] [Parallel and Concurrent Programming in Haskell](https://simonmar.github.io/pages/pcph.html)
  - [ ] [IHP](https://ihp.digitallyinduced.com/) or [Yesod](https://www.yesodweb.com/) for web app development
  - [ ] [Pandoc](https://github.com/jgm/pandoc) as an example project outside of web dev

## Games in Ruby

The minimalist route is to build a text-based game, [as I'm doing](https://fpsvogel.com/posts/2023/ruby-text-adventure-real-time-input).

For graphical games, I recommend 💲[DragonRuby Game Toolkit](https://dragonruby.itch.io/dragonruby-gtk) because it has the liveliest community. You may qualify for a free license (see "Free Unrestricted License" on the homepage), and the creators regularly give it away for free during game jams and other special occasions.

**DragonRuby tutorials:**

- [Building Games with DragonRuby](https://book.dragonriders.community/)
- [Let's make Tetris with DragonRuby Game Toolkit, Part 1](https://www.youtube.com/watch?v=xZMwRSbC4rY) and [Part 2](https://www.youtube.com/watch?v=C3LLzDUDgz4)
- [Notes on DragonRuby Game Toolkit](https://dev.to/presidentbeef/series/16166)

**DragonRuby community and reference:**

- [Discord server](discord.dragonruby.org)
- [Docs](http://docs.dragonruby.org.s3-website-us-east-1.amazonaws.com/)
- [Scale](https://github.com/DragonRidersUnite/scale) template
- [DragonRuby Zine, Issue 1](https://dragonridersunite.itch.io/dragonruby-zine-issue-1)
- [DragonRuby Recipes](https://www.dragonriders.community/recipes)
- [Awesome DragonRuby](https://www.dragonriders.community/awesome-dragonruby/)

**Other Ruby game libraries:** [Ruby 2D](https://www.ruby2d.com/), [Gosu](https://www.libgosu.org/), [MiniGL](https://github.com/victords/minigl), [Taylor](https://taylor.oequacki.com/).

## Ruby blogs, podcasts, screencasts

- **Blogs:** There are lots more out there; these are just my favorites.
  - [Code with Jason](https://www.codewithjason.com/articles/)
  - [Write Software, Well](https://www.writesoftwarewell.com/)
  - [zverok on lucid code and open data](https://zverok.substack.com/)
  - [Fly.io - The Ruby Dispatch](https://fly.io/ruby-dispatch/)
  - [Noel Rappin's Blog](https://noelrappin.com/blog/)
- **"Let's build" screencasts:** These are channels that have at least one series that uses Rails 7.
  - [Dr. Nic](https://www.youtube.com/@MocraVideos/playlists)
  - [TypeFast](https://www.youtube.com/@typefastco/playlists)
  - [Mix & Go](https://www.youtube.com/@mixandgo/playlists)
  - [SupeRails](https://www.youtube.com/@SupeRails/playlists)
  - [Justin Searls](https://www.youtube.com/@JustinSearls/playlists)
  - [Web-Crunch](https://www.youtube.com/@Webcrunch/videos)
  - [CJ Avilla](https://www.youtube.com/@cjav_dev/playlists)
- **Topical screencasts:**
  - [Code with Jason Meetup](https://www.youtube.com/@codewithjason/videos)
  - 💲[GoRails](https://gorails.com)
  - 💲[Drifting Ruby](https://www.driftingruby.com)
- **Podcasts:**
  - [Ruby for All](https://www.rubyforall.com/)
  - [Fullstack Ruby](https://www.fullstackruby.dev/topics/podcast)
  - [Remote Ruby](https://remoteruby.transistor.fm/episodes)
  - [Rooftop Ruby](https://www.rooftopruby.com)
  - [Ruby on Rails Podcast](https://www.therubyonrailspodcast.com/), especially starting at [episode 372](https://www.therubyonrailspodcast.com/372) went they went independent, brought on co-hosts, and hired an editor.
  - [The Tightly Coupled Book Club](https://rss.com/podcasts/tightly-coupled-book-club/)
  - [The Rubber Duck Dev Show](https://www.rubberduckdevshow.com/)
  - [Code with Jason](https://www.codewithjason.com/podcast)
  - [Code and the Coding Coders who Code it](https://podcast.drbragg.dev/)
  - [The Rails Changelog](https://www.railschangelog.com/)
  - [The Bike Shed](https://www.bikeshed.fm/)
  - [IndieRails](https://www.indierails.com/)
  - [Running in Production – Rails](https://runninginproduction.com/tags/rails)

## Rails codebases to study

I've chosen the codebases below based on a these criteria:

- Is active, with recent commits.
- Does not use a JS framework on the front end, though I made exceptions.
- Is well-known *or* it solves a problem that's interesting to me.

If you want to explore more widely, here are other places to find open-source Ruby projects:

- [OpenSourceRails](https://opensourcerails.org/)
- [Ruby projects on CodeTriage](https://www.codetriage.com/?language=Ruby), though not all of them are Rails apps
- [Real World Rails](https://github.com/eliotsykes/real-world-rails) (and [how to search through it](https://www.hexdevs.com/posts/massive-list-of-open-source-ruby-on-rails-applications-you-can-use-as-a-reference/))
- [Awesome Ruby and Rails Open Source Apps](https://github.com/asyraffff/Open-Source-Ruby-and-Rails-Apps)

**Small codebases:** Less than 50k lines of Ruby code.

- [github.com/SpinaCMS/Spina](https://github.com/SpinaCMS/Spina) (5k lines): *CMS (Content Management System).*
- [github.com/codetriage/codetriage](https://github.com/codetriage/codetriage) (6k lines): *Issue tracker for open-source projects.*
- [github.com/joemasilotti/railsdevs.com](https://github.com/joemasilotti/railsdevs.com) (12k lines): *The reverse job board for Ruby on Rails developers.*
- [github.com/RailsEventStore/ecommerce](https://github.com/RailsEventStore/ecommerce) (12k lines): *Example app showing DDD (Domain-Driven Design), CQRS, and Event Sourcing.*
- [github.com/lobsters/lobsters](https://github.com/lobsters/lobsters) (13k lines): *Hacker News clone.*
- [github.com/thoughtbot/upcase](https://github.com/thoughtbot/upcase) (14k lines): *Learning platform for developers.*
- [github.com/houndci/hound](https://github.com/houndci/hound) (14k lines): *Automated code review for GitHub PRs.*
- [github.com/feedbin/feedbin](https://github.com/feedbin/feedbin) (25k lines): *RSS reader.*
- [github.com/rubygems/rubygems.org](https://github.com/rubygems/rubygems.org) (26k lines): *Where Ruby gems are hosted.*
- [github.com/AlchemyCMS/alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms) (36k lines): *CMS (Content Management System).*
- [github.com/SumOfUs/Champaign](https://github.com/SumOfUs/Champaign) (39k lines): *Digital campaigning platform. A Rails app generator.*

**Larger codebases:** More than 50k lines of Ruby code.

- [github.com/solidusio/solidus](https://github.com/solidusio/solidus) (72k lines): *E-commerce platform.*
- [github.com/mastodon/mastodon](https://github.com/mastodon/mastodon) (75k lines): *Like Twitter but self-hosted and federated.*
- [github.com/openfoodfoundation/openfoodnetwork](https://github.com/openfoodfoundation/openfoodnetwork) (102k lines): *An online marketplace for local food.*
- [github.com/forem/forem](https://github.com/forem/forem) (103k lines): *Powers the blogging site [dev.to](https://dev.to/). Uses Preact on the front end.*
- [github.com/alphagov/whitehall](https://github.com/alphagov/whitehall) (117k lines): *Publishes government content on [gov.uk](https://www.gov.uk/).*
- [github.com/decidim/decidim](https://github.com/decidim/decidim) (288k lines): *The participatory democracy framework.*
- [github.com/discourse/discourse](https://github.com/discourse/discourse) (322k lines): *Discussion forum platform. Has an Ember.js front end.*
- [github.com/instructure/canvas-lms](https://github.com/instructure/canvas-lms) (745k lines): *A popular LMS (learning management system).*
- [gitlab.com/gitlab-org/gitlab](https://gitlab.com/gitlab-org/gitlab) (1.8 million lines): *Like GitHub but with CI/CD and DevOps features built in. Has great [docs on architecture](https://docs.gitlab.com/ee/development/architecture.html).*
