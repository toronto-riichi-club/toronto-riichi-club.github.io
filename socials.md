---
title: Socials
layout: page
---

{::options parse_block_html="true" /}

Follow us on these platforms!

<div class="socials-list">

- [{% include icon.html id="discord" %} Discord]({{site.social_links_all.Discord}})
- [{% include icon.html id="globe" %} Website]({{site.social_links_all.Website}})
- [{% include icon.html id="bluesky" %} Bluesky]({{site.social_links_all.Bluesky}})
- [{% include icon.html id="x" %} X (Twitter)]({{site.social_links_all.X}})
- [{% include icon.html id="instagram" %} Instagram]({{site.social_links_all.Instagram}})
- [{% include icon.html id="github" %} GitHub]({{site.social_links_all.GitHub}})
- [{% include icon.html id="twitch" %} Twitch]({{site.social_links_all.Twitch}})

* * *

- [{% include icon.html id="discord" %} TORI Open Discord](https://discord.gg/XrhPZRwPMZ)

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
  padding: 1.5ex 1ex;
  border: 2px solid var(--bodyColour);
  border-radius: 1em;
  transition: background-image 300ms;
  background-color: white;
  background-image: linear-gradient(to right, #ffffff 25%, var(--linkColour));
  background-position: unset;
  background-size: unset;
  text-shadow: 0.1rem 0 3px #fff,0.15rem 0 3px #fff,-0.1rem 0 3px #fff,-0.15rem 0 3px #fff; /* from theme, with blur */
  box-shadow: 0.25em 0.25em 0.5em #00000040;
  color: black;
}
.socials-list li a:hover,
.socials-list li a:active,
.socials-list li a:focus {
  border-color: var(--linkColour);
  background-image: linear-gradient(to right, #ffffff 33%, #1aa0cd80);
  color: var(--hoverColour)
}

.socials-list a .icon--discord { color: #5865F2; }
.socials-list a .icon--globe   { color: #1AA0CD; }
.socials-list a .icon--bluesky { color: #0285FF; }
.socials-list a .icon--x       { color: #000000; }
.socials-list a .icon--instagram { color: #FF0069; }
.socials-list a .icon--github  { color: #181717; }
.socials-list a .icon--twitch  { color: #9146FF; }

.socials-list svg {
  vertical-align: sub;
  margin-right: 1ex;
}

.socials-list hr {
  padding-top: 1rem;
  padding-bottom: 1rem;
}
</style>
