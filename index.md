---
layout: default
---

{% assign repos = site.github.public_repositories %}
{% assign android_repo = repos | where: "name", site.client_android | first %}
{% assign windows_repo = repos | where: "name", site.server_windows | first %}

#### Android client

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
    alt="Get it on F-Droid"
    height="80">](https://f-droid.org/packages/io.github.soundremote)

- Latest release: [download]({{ android_repo.html_url }}/releases/latest)
- Source code: [GitHub]({{ android_repo.html_url }})

#### Windows server

- Latest release: [download]({{ windows_repo.html_url }}/releases/latest)
- Source code: [GitHub]({{ windows_repo.html_url }})

* * *

[**Donate**](./donate.html)
