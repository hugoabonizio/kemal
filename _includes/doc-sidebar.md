<div class="doc-sidebar">

  <h1 class="doc-heading">Guide</h1>

  <ul class="doc-list">
    {% for post in site.docs %}
      <li>
        <h2>
          <a class="doc-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <h1 class="doc-heading">Examples</h1>

  <ul class="doc-list">
    {% for post in site.examples %}
      <li>
        <h2>
          <a class="doc-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
</div>