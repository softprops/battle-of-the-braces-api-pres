!SLIDE

# Meetup _API_
{ battle\_of\_the\_braces.js }

!SLIDE

# Meetup is

* Worlds largest hosted collection of
 _local communities_
* 105+K Meetups
* 11.3+M Members
* 2+M YES RSVPs a month
* _face_ to _face_ platform

!SLIDE

<div id="hiring">
<em>hiring</em>
<ul>
<li><a href="http://meetup.com/jobs">meetup.com/jobs</a></li>
<li>jobs@meetup.com</li>
<li><a href="http://making.meetup.com/post/21273810443/cursemetrics">making.meetup.com/post/21273810443/cursemetrics</a></li>
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
curl http://api.meetup.com/docs 2>/dev/null | pj -- | less
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

* [meetup.github.com](http://meetup.github.com/)
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
