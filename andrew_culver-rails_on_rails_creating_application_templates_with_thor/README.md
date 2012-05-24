# Rails on Rails: Creating Application Templates with Thor

Ruby on Rails provides an incredible amount of goodness out-of-the-box when you type "rails new …", but if you spin up Rails projects, you know that in the minutes following that, you end up performing a lot of the same tasks over and over. A lot of this breaks down to:

- Adding a favorite gem.
- Running some generators.
- Editing some configuration files.
- Rinse.
- Repeat.

Enter Thor!

With Thor, we can create templates that automate a lot of the initial setup that is the same from project to project. For example, by setting up a personalized template for our apps, we can instantly: 

- Switch to and configure our preferred testing library and tools.
- Switch to a preferred templating language (e.g. Haml) and convert existing templates automatically.
- Configure authentication libraries like Devise, including Facebook, Twitter, and other OAuth authentication methods.
- Installing common assets missing from Rails like reset stylesheets and jQuery UI images.
- Removing standard Rails files like index.html, README, favicon.icon.
- Configure the app to adhere to your personal best practices.
- Anything else you do on every project!

We've used Thor to create our own Rails application template and it saves us hours every time we start a new project. To enable others to do the same, I'll show them how to get Thor running shell commands, generators, and performing all the common file manipulations. We'll also bundle it in a command-line Ruby gem, so it's easy to share with others.

- Preferred presentation day: no preference
- Presentation language: English

## Andrew Culver
## アンドリュー・カルバー 

## We Are Titans
## ウィー・アー・タイトンズ

Andrew is a Ruby on Rails and iOS Developer at We Are Titans in Norfolk, VA. He also runs Limelight for app developers. Andrew graduated from the Software Engineering program at Mohawk College in Hamilton, ON, Canada and is an avid productivity hacker. He loves Japan, Japanese, and providing for his wife and kids doing what he loves.

- [We Are Titans](http://www.wearetitans.net)
- [Limelight](http://limelightapp.com/)
- [Gypsum](http://github.com/andrewculver/gypsum/)
- [@andrewculver on Twitter](https://twitter.com/#!/andrewculver)
- [Comments on Hacker News](http://news.ycombinator.com/threads?id=aculver)
- [Past Talk: "Being Good at Life"](http://public.iwork.com/document/?a=p115143142&d=Being_Good_At_Life.key)

![](https://github.com/andrewculver/sprk2012-cfp/blob/rails_on_rails_creating_application_templates_with_thor/andrew_culver-rails_on_rails_creating_application_templates_with_thor/andrew.jpg?raw=true)
