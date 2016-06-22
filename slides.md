## Open Source is Everywhere
### Tales of devops

Notes:
* Who's actively using open source projects? Any particular examples/why?
* Anyone running open source projects? Tell us about it.
* Anyone not contributed to open source before?

---

## About me

* David Beitey
* @davidjb / @davidjb_
* Developer, Sys Admin, Enthusiast

---

## Let's discuss!

(Ask questions, tell me I'm wrong,  
share your experiences etc)

---

## You've used open source

![Open source logos](img/oss.png) <!-- .element: class="plain stretch" style="background: white;" -->

Notes:
* OS (Linux, FreeBSD, Android, OpenStack)
* Web (Firefox/Chromium, Apache, Nginx, Wikipedia, Wordpress, Drupal, Bootstrap)
* Apps, DBs and utilities (Open/LibreOffice, Postgres/MariaDB/MySQL)
* Programming (Node, Python, Ruby etc)

---

## Open source is

Stuff released under terms that allow:
* Free sharing (*libre*)
* Reuse for any purpose
* Modification by anyone

Different definitions exist (FSF vs OSI)

Notes:
* *Free software* vs *open source* differ on fundamental values (freedom of
  speech vs p2p development model)
* Practical difference is small
* Free in terms of speech, not free as in beer
* Not just software (Hardware [Arduino], OpenStreetMap, recipes, beer etc)
* Open-source brewery does exist

---

## Open source != freeware

though it *can* cost money

Notes:
* Usually doesn't cost money (haven't see it yet)
* Definitely not shareware either

---

## My experience



Made lots of contributions to various projects  
(mostly docs, oddly)


### One particular example



* **Early 2013**: started implementation of nginx/Shibboleth

  ![nginx](img/nginx.svg) <!-- .element: class="plain stretch" style="width: 200px;" -->
  ![Shibboleth](img/shibboleth.png) <!-- .element: class="plain stretch" style="width: 200px;" -->

* **April 2013**: released initial integration code
  * Not formalised, quite hacky
  * Lots of comments from keen users
* **2013-2014**: ...

Notes:
* Long standing compatibility issue, essentially preventing the use of
  *anything* but Apache/IIS.
* nginx is a high-perf web server (+ proxy etc etc)
* Shibboleth underpins SSO in Universities/Institutions/federations worldwide
  and uses SAML
* Released as some code patches in a repo + docs



## Late one night, this turned up

![nginx Module email](img/nginx-module-email.png)

Notes:
* **Nov 2014**: Luca (Debian project) reached out to help
* My response was a little `OTT`, but I was really stoked to have the help.


# :)


## ⏩ to 2016

* Worked to formalise code
* Shared GitHub organisation
* Now in use in dozens of countries/Universities
* PRs closed, bug reports etc

Notes:
* Exciting, but I'm not out to conquer the world.
* I'm stoked to be helping people solve the same problems I've had
* I'm excited to have their help because it's usually just me on this
* Which highlights why open source

---

## Why open source?

* Shoulders of giants
* Quality
* Freedom
* Community
* Price

Notes:
* Writing from scratch sucks. Might be interesting, but don't reinvent
  the wheel. Faster is better.
* Reusing projects typically means it's been battle-tested, especially for
  well worn code
  * Solves things you haven't thought of yet
  * Good for security etc
* Freedom: an open licence means you can extend, reuse etc the work. 
  * Compare to a closed-source model; you can't even tell if it's working
    correctly without black-boxing.
  * I own a BT remote control car that's now unusable because the original dev
    didn't save his code or use VCS.  Oops.
* Community: typically open to discussion. Find an issue and be appreciated.
  * Build a community and have them help you too (2 way street)
  * Compare to closed orgs: security issues with local companies and get
    ignored/rejected/vilified.
* Price:  Python would take 286 years to develop and cost $16m

---

## Helps you

* Warm fuzzy feeling
* Skills + CV + public profile

Notes:
* Equivalent of thinking 'I need to toast bread' and you can get a world-class
  toaster at likely no charge that you can hack on.
* Employers looking for contributors through GH profiles etc
* But that's not all...

---

## Open source doesn't discriminate.

Notes:
* The joy of open source is that it doesn't discriminate. The code is there
  and it's available for anyone to do what they will with it.
* This is why it's important to help.

---

## Get involved

It takes all skills, not just devs.

Notes:
* Just using open source apps is a great start


* Use/test open source apps or projects
* Evangelise
* Write documentation
* Report bugs
* Contribute fixes
* Share your work / code
* Donate

---

## Starting out?

Begin with the project you're working on.

* Pain points
* Documentation
* Unfixed bugs
* Features

Notes:
* Anyone not contributed to open source before?
* You'll know the pain points of the software you're using
* Eventually you'll hit an unfixed bug or implement a new feature you need


### Key points

* Every project is different
* Larger projects have a style/contributor's guide
* **Be professional**

Notes:
* Not everyone will be professional back, don't stoop
* Don't take it to heart if your contribution is rejected


## Demo

Let's improve the docs for `Reveal.js`  
(this slide deck)

https://github.com/hakimel/reveal.js#external-markdown

Notes:
* Unclear docs as to what separators mean what
* Fixing on GitHub requires a GH account
* Only one file at a time TTW
* Click `Edit` and you can modify any file immediately
* GH forks the project for you so you can make a change locally
* If you have access to the project, you'll make the change directly
* <https://github.com/hakimel/reveal.js/compare/dev...davidjb:markdown-doc-fix>

---

## On the tech side of things...

* Report and fix bugs
* Implement new features
* Add (or fix) tests


* Reach out first
* Adhere to contributor guides and code style
* Add tests

![Travis CI logo](img/travis-ci.png)

Notes:
* Reach out for anything you're unsure about: bug report, feature suggestion,
  mailing list, stalk the developer on email, FB etc.
* Tests help prove your code doesn't suck.  Free testing environments like
  Travis exist so use them

---

## What's next?

Open sources means freedom to change

1. Report issues, fix documentation, be professional
1. Contribute your first fix ([mine](https://github.com/cherokee/web/pull/5))
1. Learn Git (version control)
1. Share your code
1. Create code host profiles (GitHub, BitBucket, GitLab)
1. Learn a bit about licences: <http://ChooseALicense.com>

Notes:
* In short, it's a great feeling to know you're helping people.
* The oddest sensation is that you'll never know how many people you've helped -- because
open source is everywhere.

