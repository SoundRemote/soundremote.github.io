---
layout: default
---

{% assign repos = site.github.public_repositories %}
{% assign android_repo = repos | where: "name", site.client_android | first %}
{% assign windows_repo = repos | where: "name", site.server_windows | first %}

#### Android client

Source code: [GitHub]({{ android_repo.html_url }})

Latest release: [download]({{ android_repo.html_url }}/releases/latest)

#### Windows server

Source code: [GitHub]({{ windows_repo.html_url }})

Latest release: [download]({{ windows_repo.html_url }}/releases/latest)
