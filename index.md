# Welcome to Crimson Skies

This is a website dedicated to promotion, reviewing and making of **Dungeon Synth** music and related topics. Yes, the name is a reference to the lyrics of Candlemass - Under the Oak.

## What is Dungeon Synth?

tl;dr evil? video game music

Atmospheric electronic music with symphonic/neoclassical influences. It has it's root in the 90s having artists like Jim Kirkwood and Mortiis forging it's inception.

It usually covers topics like mythology, fantasy and magic with Tolkien influences. But there really are no rules, as long as it's close to stylistic characteristics it's fair game.

Speaking of, Dungeon Synth is very similar to 2nd wave black metal stylistically. It's probably because a lot of the earlier artists also made that kind of music. Mortiis was the bass player for Emperor, Wongraven was created by Satyricon's vocalist and Mirkwood was created by a Summoning's vocalist, these are just a few examples of the joint history of the two genres. So close in fact that I sometimes click at an album thinking it's going to be black metal but it's actually dungeon synth (I'm looking at you [Thangorodrim](https://thangorodrimsynth.bandcamp.com/album/taur-nu-fuin-remaster)). The key difference being the stronger fantasy influences. Another characteristic the genre has adopted is obscurity as part of it's identity. 

## Where can I find Dungeon Synth?

[The Dungeon Synth Archives YouTube Channel](https://www.youtube.com/channel/UChmm356a5qe1luUsoatAgjA) is one of the most well known places you can stream dungeon synth, as far as I know the guy that runs the channel got permission for all the uploads on his channel.

[Bandcamp](https://bandcamp.com/tag/dungeon-synth), this is where most artists put up their albums for sale, usually digital copies but if they're good enough to get a record label to print some cassettes you can also get some physical copies.

If you plan to sail the seven seas beware of the shitty transcoded audio files which are very common. If you can, support the artists, you also get access to lossless audio files.

It is rare but you can also find some in streaming services like Spotify.

You might also find some cassettes hidden in the woods, who knows.

## Who are we

- Cythraul - Head writer, website programmer, music enjoyer, business owner, gamer
- Suovaeltaja - Writer

## Special Thanks to

- Github Pages for having the website hosted.
- The artists that contributed to the genre.
- All the kitties of the world.

## Recent Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.date | date: "%Y-%m-%-d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<script src="https://utteranc.es/client.js"
repo="lsaa/crimson-skies"
issue-term="pathname"
theme="photon-dark"
crossorigin="anonymous"
async>
</script>