---
title: Socials
layout: page
---

{::options parse_block_html="true" /}

Follow us on these platforms!

<div class="socials-list">

- [{% include icon.html id="discord" %} Discord]({{site.social_links.Discord}})
- [{% include icon.html id="globe" %} Website](https://www.torontoriichi.club/)
- [{% include icon.html id="x" %} X (Twitter)]({{site.social_links.X}})
- [{% include icon.html id="github" %} GitHub]({{site.social_links.GitHub}})
- [{% include icon.html id="twitch" %} Twitch]({{site.social_links.Twitch}})

</div>

<style>
.socials-list ul li {
  list-style-type: none;
  margin-left: 0;
  font-size: 1.3em;
}

@media (min-width: 640px) {
  .socials-list ul li {
    font-size: inherit;
  }
}

.socials-list ul li + li {
  margin-top: 1ex;
}

.socials-list li a {
  display: inline-block;
  width: 100%;
  padding: 1ex;
  border: 2px solid var(--bodyColour);
  border-radius: 1em;
  background-image: none !important;
}
.socials-list a:hover {
  border-color: var(--linkColour);
}

.socials-list a:hover .icon--discord { color: #5865F2; }
.socials-list a:hover .icon--x       { color: #000000; }
.socials-list a:hover .icon--github  { color: #181717; }
.socials-list a:hover .icon--twitch  { color: #9146FF; }

.socials-list svg {
  vertical-align: sub;
  margin-right: 1ex;
}
</style>
