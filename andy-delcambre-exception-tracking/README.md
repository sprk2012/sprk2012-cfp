# Exception Tracking

Exception tracking has won in ruby. But could it be better? How many users did this exception affect? What are all of the exceptions that happen for a specific post? Is this exception localized to a single application server? None of these questions are easily answered in the current crop of exception tracking systems.

I have been experimenting with using Elastic Search as a document database for exception data. This allows searching and grouping on any field which turns out to be a very nice property for an exception tracker. I will describe the architecture I am using with Elastic Search to accomplish this. As well as some background on Elastic Search in general.

- Preferred presentation day: no preference
- Presentation language: English

## Andy Delcambre
## Engine Yard, Inc

Andy Delcambre is an engineer at Engine Yard and lives in San Francisco. Previously he hailed from Portland where he was a Rails consultant at Planet Argon. He snowboards, backpacks, travels, rock climbs, eats delicious food and rides his bike as often as he can manage.

- [My website](http://andy.delcambre.com)
- [My twitter](https://twitter.com/#!/adelcambre)
- [Rubyconf 2011 Slides](https://speakerdeck.com/u/adelcambre/p/release-early-and-release-often)
- [Rubyconf 2011 Video](http://confreaks.com/videos/667-rubyconf2011-release-early-and-release-often-reducing-deployment-friction)
- [RubyKaigi 2011 Slides](http://andy.delcambre.com/rubykaigi-2011)
- [RubyKaigi 2011 Video](http://vimeo.com/26510145)
- [Úll Sponsor Talk Slides](https://speakerdeck.com/u/adelcambre/p/ruby-rails-and-engine-yard-ull)
