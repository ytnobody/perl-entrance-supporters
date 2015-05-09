template: default
---

<ul class="archives">
: for $blog.entries() -> $entry {
<li><a href="<: $entry.site_path() | uri_for :>"><: $entry.title :></a></li>
: }
</ul>
