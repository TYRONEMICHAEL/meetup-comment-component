## Meetup Comments Component

![](https://tyronemichael.ghost.io/content/images/2014/Jul/Screen-Shot-2014-07-29-at-6-56-15-PM.png)

[Presentation](http://www.meetup.com/CodedInBraam/events/191593992/) - Amidst all the frameworks. plugins, and libraries there has been a new movement brewing. This movement is better know as the declarative renaissance. The movement's goal is to build web components, which simplify the web by providing a unified way to create new elements that encompass rich functionality without the need for all the extra libraries.

To run you need to have [Bower](http://bower.io/) installed. Then just clone the repo and first run `bower install` to install all the dependancies.

Open up index.html and find the following
`<meetup-comments key="YourKey" groupId="4162452"></meetup-comments>`. Substitute `YourKey` with your [meetup API key](https://secure.meetup.com/meetup_api/key/). Change the `groupId` if you wish.

Start a static server with `python -m SimpleHTTPServer 4000`. Open your browser @ http://localhost:4000.

Please also view the blog post [here](http://tyronemichael.com/a-declarative-renaissance-with-web-components-and-polymer/) for sample code and referance links.
