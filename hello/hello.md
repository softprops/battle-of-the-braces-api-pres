!SLIDE

# Meetup _API_
HackRU / 21042012

!SLIDE
<div id="me">
<h1>I</h1>
<ul>
<li>am <em>Doug</em> (hi)</li>
<li>code for <em>Meetup</em> (~1.2yr)</li>
<li>code for <em>fun</em> (<a href="http://github.com/softprops">github</a>)</li>
</ul>
</div>

!SLIDE

# Meetup is

* Worlds largest hosted collection of
 _local communities_
* 100.5+K Meetups
* 10.6+M members
* 2+M YES RSVPs a month
* _face_ to _face_ platform

!SLIDE

<div id="hiring">
<em>hiring</em>
<ul>
<li><a href="http://meetup.com/jobs">meetup.com/jobs</a></li>
<li>jobs@meetup.com</li>
<li><a href="making.meetup.com/gitCurses">making.meetup.com/gitcurses</a></li>
</div>

!SLIDE

# API is

* Well Documented
* _Auth_entic
* _REST_ful
* _Stream_y
* A community

!SLIDE

# /docs

## [meetup.com/api](http://www.meetup.com/api/)

## [api.meetup.com](http://api.meetup.com)

<pre><code>
# documentation hack idea
curl http://api.meetup.com/docs 2>/dev/null | pj --
</code></pre>

!SLIDE

# /auth

* api key ?*key*=__
* signed ?*key*=__&*sign*=true
* oauth 2 ?*access_token*=__
* oauth 1.0a ?*oauth_xxx*=__

!SLIDE

# /rest

<pre>
   GET https://api.meetup.com/2/events
   POST https://api.meetup.com/2/event/:id
   GET https://api.meetup.com/2/event/:id
   DELETE https://api.meetup.com/2/event/:id 
</pre>

!SLIDE

# /stream ~>

* [meetup.github.com/stream](http://meetup.github.com/stream/)
* [bitly.com/meetupjs](https://bitly.com/meetupjs)
* auth not required
* connection throttling

!SLIDE
# /stream

* chunked HTTP
<pre>
curl stream.meetup.com/2/rsvps
</pre>

* websockets/long polling
<pre>
mu.Rsvps(function(rsvp) {
&nbsp;&nbsp;console.log(rsvp)
});
</pre>

!SLIDE

# /community

* [meetup.com/Meetup-API-Testing](http://www.meetup.com/Meetup-API-Testing/)
* [groups.google.com/group/meetup-api](https://groups.google.com/group/meetup-api/)
* @[meetupApi](http://twitter.com/meetupapi)

!SLIDE

# répondez s'il vous plaît
### { [meetup.com/battle-of-the-braces](http://meetup.com/battle-of-the-braces) }
## _Doug Tangren_
### doug@meetup.com
