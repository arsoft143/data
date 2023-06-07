# IPTV

Collection of publicly available IPTV (Internet Protocol television) channels from all over the world.

## Table of contents

- 🚀 [How to use?](#how-to-use)
- 📺 [Playlists](#playlists)
- 🗄 [Database](#database)
- 👨‍💻 [API](#api)
- 📚 [Resources](#resources)
- 💬 [Discussions](#discussions)
- ❓ [FAQ](#faq)
- 🛠 [Contribution](#contribution)
- ⚖ [Legal](#legal)
- © [License](#license)

## How to use?

Simply insert one of the links below into [any video player](https://github.com/iptv-org/awesome-iptv#apps) that supports live streaming and press _Open_.

![VLC Network Panel](https://github.com/iptv-org/iptv/raw/master/.readme/preview.png)

## Playlists

There are several versions of playlists that differ in the way they are grouped.

### Main playlist

Playlist includes all known channels except adult channels.

```
https://iptv-org.github.io/iptv/index.m3u
```

And here is the full version:

```
https://iptv-org.github.io/iptv/index.nsfw.m3u
```

### Grouped by category

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _category_ as a group title:

```
https://iptv-org.github.io/iptv/index.category.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Category</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td>Kannada</td><td align="right">15</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/auto.m3u</code></td></tr>
    <tr><td>Hindi</td><td align="right">44</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/animation.m3u</code></td></tr>
    <tr><td>Telugu</td><td align="right">53</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/business.m3u</code></td></tr>
    <tr><td>Tamil</td><td align="right">54</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/classic.m3u</code></td></tr>
    <tr><td>Comedy</td><td align="right">53</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/comedy.m3u</code></td></tr>
    <tr><td>Cooking</td><td align="right">21</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/cooking.m3u</code></td></tr>
    <tr><td>Culture</td><td align="right">63</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/culture.m3u</code></td></tr>
    <tr><td>Documentary</td><td align="right">60</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/documentary.m3u</code></td></tr>
    <tr><td>Education</td><td align="right">112</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/education.m3u</code></td></tr>
    <tr><td>Entertainment</td><td align="right">311</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/entertainment.m3u</code></td></tr>
    <tr><td>Family</td><td align="right">39</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/family.m3u</code></td></tr>
    <tr><td>General</td><td align="right">953</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/general.m3u</code></td></tr>
    <tr><td>Kids</td><td align="right">180</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/kids.m3u</code></td></tr>
    <tr><td>Legislative</td><td align="right">147</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/legislative.m3u</code></td></tr>
    <tr><td>Lifestyle</td><td align="right">76</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/lifestyle.m3u</code></td></tr>
    <tr><td>Movies</td><td align="right">269</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/movies.m3u</code></td></tr>
    <tr><td>Music</td><td align="right">425</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/music.m3u</code></td></tr>
    <tr><td>News</td><td align="right">622</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/news.m3u</code></td></tr>
    <tr><td>Outdoor</td><td align="right">43</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/outdoor.m3u</code></td></tr>
    <tr><td>Relax</td><td align="right">15</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/relax.m3u</code></td></tr>
    <tr><td>Religious</td><td align="right">351</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/religious.m3u</code></td></tr>
    <tr><td>Series</td><td align="right">166</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/series.m3u</code></td></tr>
    <tr><td>Science</td><td align="right">24</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/science.m3u</code></td></tr>
    <tr><td>Shop</td><td align="right">72</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/shop.m3u</code></td></tr>
    <tr><td>Sports</td><td align="right">188</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/sports.m3u</code></td></tr>
    <tr><td>Travel</td><td align="right">30</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/travel.m3u</code></td></tr>
    <tr><td>Weather</td><td align="right">14</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/weather.m3u</code></td></tr>
    <tr><td>XXX</td><td align="right">45</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/xxx.m3u</code></td></tr>
    <tr><td>Undefined</td><td align="right">4929</td><td nowrap><code>https://iptv-org.github.io/iptv/categories/undefined.m3u</code></td></tr>
  </tbody>
</table>

</details>

### Grouped by language

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _language_ as a group title:

```
https://iptv-org.github.io/iptv/index.language.m3
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Language</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>

   
</table>

</details>

### Grouped by country

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _country_ as a group title:

```
https://iptv-org.github.io/iptv/index.country.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Country</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
 
</table>

</details>

### Grouped by region

<details>
<summary>Expand</summary>
<br>

Playlist in which each channel has its _region_ as a group title:

```
https://iptv-org.github.io/iptv/index.region.m3u
```

Same thing, but split up into separate files:

<!-- prettier-ignore -->
<table>
  <thead>
    <tr><th align="left">Region</th><th align="left">Channels</th><th align="left">Playlist</th></tr>
  </thead>
  <tbody>
    <tr><td align="left">Africa</td><td align="right">271</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/afr.m3u</code></td></tr>
    <tr><td align="left">Americas</td><td align="right">3483</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/amer.m3u</code></td></tr>
    <tr><td align="left">Asia-Pacific</td><td align="right">1888</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/apac.m3u</code></td></tr>
    <tr><td align="left">Arab world</td><td align="right">341</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/arab.m3u</code></td></tr>
    <tr><td align="left">Association of Southeast Asian Nations</td><td align="right">416</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/asean.m3u</code></td></tr>
    <tr><td align="left">Asia</td><td align="right">2785</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/asia.m3u</code></td></tr>
    <tr><td align="left">Benelux</td><td align="right">243</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/benelux.m3u</code></td></tr>
    <tr><td align="left">Caribbean</td><td align="right">192</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/carib.m3u</code></td></tr>
    <tr><td align="left">Central Asia</td><td align="right">60</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cas.m3u</code></td></tr>
    <tr><td align="left">Central and Eastern Europe</td><td align="right">970</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cee.m3u</code></td></tr>
    <tr><td align="left">Central America</td><td align="right">186</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cenamer.m3u</code></td></tr>
    <tr><td align="left">Commonwealth of Independent States</td><td align="right">456</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/cis.m3u</code></td></tr>
    <tr><td align="left">Europe, the Middle East and Africa</td><td align="right">3574</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/emea.m3u</code></td></tr>
    <tr><td align="left">Europe</td><td align="right">3039</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/eur.m3u</code></td></tr>
    <tr><td align="left">Hispanic America</td><td align="right">1327</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/hispam.m3u</code></td></tr>
    <tr><td align="left">Latin America and the Caribbean</td><td align="right">1617</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/lac.m3u</code></td></tr>
    <tr><td align="left">Latin America</td><td align="right">1601</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/latam.m3u</code></td></tr>
    <tr><td align="left">Maghreb</td><td align="right">54</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/maghreb.m3u</code></td></tr>
    <tr><td align="left">Middle East and North Africa</td><td align="right">603</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/mena.m3u</code></td></tr>
    <tr><td align="left">Middle East</td><td align="right">560</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/mideast.m3u</code></td></tr>
    <tr><td align="left">Northern America</td><td align="right">1866</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/nam.m3u</code></td></tr>
    <tr><td align="left">Northern Europe</td><td align="right">121</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/neur.m3u</code></td></tr>
    <tr><td align="left">North America</td><td align="right">2392</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/noram.m3u</code></td></tr>
    <tr><td align="left">Nordics</td><td align="right">85</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/nord.m3u</code></td></tr>
    <tr><td align="left">Oceania</td><td align="right">56</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/oce.m3u</code></td></tr>
    <tr><td align="left">South Asia</td><td align="right">535</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sas.m3u</code></td></tr>
    <tr><td align="left">Southeast Asia</td><td align="right">439</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/sea.m3u</code></td></tr>
    <tr><td align="left">Southern Europe</td><td align="right">1019</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/ser.m3u</code></td></tr>
    <tr><td align="left">South America</td><td align="right">1091</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/southam.m3u</code></td></tr>
    <tr><td align="left">Sub-Saharan Africa</td><td align="right">205</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/ssa.m3u</code></td></tr>
    <tr><td align="left">West Africa</td><td align="right">104</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/wafr.m3u</code></td></tr>
    <tr><td align="left">Western Europe</td><td align="right">928</td><td align="left" nowrap><code>https://iptv-org.github.io/iptv/regions/wer.m3u</code></td></tr>
  </tbody>
</table>

</details>

## Database

All channel data is taken from the [iptv-org/database](https://github.com/iptv-org/database) repository. If you find any errors please open a new [issue](https://github.com/iptv-org/database/issues) there.

## API

The API documentation can be found in the [iptv-org/api](https://github.com/iptv-org/api) repository.

## Resources

Links to other useful IPTV-related resources can be found in the [iptv-org/awesome-iptv](https://github.com/iptv-org/awesome-iptv) repository.

## Discussions

If you have a question or an idea, you can post it in the [Discussions](https://github.com/iptv-org/iptv/discussions) tab.

## FAQ

The answers to the most popular questions can be found in the [FAQ.md](FAQ.md) file.

## Contribution

Please make sure to read the [Contributing Guide](CONTRIBUTING.md) before sending an issue or making a pull request.

And thank you to everyone who has already contributed!

### Backers

<a href="https://opencollective.com/iptv-org"><img src="https://opencollective.com/iptv-org/backers.svg?width=890" /></a>

### Contributors

<a href="https://github.com/iptv-org/iptv/graphs/contributors"><img src="https://opencollective.com/iptv-org/contributors.svg?width=890" /></a>

## Legal

No video files are stored in this repository. The repository simply contains user-submitted links to publicly available video stream URLs, which to the best of our knowledge have been intentionally made publicly by the copyright holders. If any links in these playlists infringe on your rights as a copyright holder, they may be removed by sending a [pull request](https://github.com/iptv-org/iptv/pulls) or opening an [issue](https://github.com/iptv-org/iptv/issues/new?assignees=freearhey&labels=removal+request&template=--removal-request.yml&title=Remove%3A+). However, note that we have **no control** over the destination of the link, and just removing the link from the playlist will not remove its contents from the web. Note that linking does not directly infringe copyright because no copy is made on the site providing the link, and thus this is **not** a valid reason to send a DMCA notice to GitHub. To remove this content from the web, you should contact the web host that's actually hosting the content (**not** GitHub, nor the maintainers of this repository).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](LICENSE)
