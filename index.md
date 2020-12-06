---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<header class="text-center mb-5">
  <h1 class="display-4 mb-4">{{ site.title }}</h1>
  <p class="lead text-muted mb-0">
    {{ site.description }}
  </p>
</header>

{% include countdown.html %}


<div class="row mb-5">
	<div class="col text-center">
		<a class="twitter-follow-button"
		  href="https://twitter.com/gvtshtdwn"
		  data-size="large"
		  data-show-count="false">
			Follow @GvtShtDwn
		</a>
		<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
	</div>
</div>

{% include faq.html %}

<div class="alert alert-info" role="alert">
  <i class="fas fa-info-circle"></i> <u><a href="https://www.congress.gov/contact-us" target="_blank">Contact your member of Congress</a></u> to ask them to fund the government.
</div>