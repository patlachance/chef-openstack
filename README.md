# Chef-OpenStack GitHub Page

Our GitHub Page for Chef-OpenStack is a branded theme made using [Bootstrap CSS](http://getboostrap.com) and served up with Jekyll. It is a minimal way to create static landing pages for each repo and publish them on our GitHub Pages.

## Before Starting

To harness all the power for this theme, you need to install Ruby and Jekyll (a Ruby gem). However, you do not have to install either to make your own page. By making just a few changes to the `_config.yml` file, you can [create a page on-the-fly in minutes](#configuration).

Of course, should you prefer to have all the power, keep reading.

## Downloading

Two download options are available.

- [Download the latest release](https://github.com/softlayer/chef-openstack/archive/master.zip).
- Clone the repo: `git clone https://github.com/softlayer/chef-openstack.git`.

Search our [Getting Started](../getting-started) page for information on installing, configuring, and much more.

Below is a list of some other documentation related to this project.

- [Install Jekyll on Windows](../install-jekyll-windows)
- [Technical Documents](../documents)
- To learn more about Jekyll, check out their [documentation](http://jekyllrb.com/docs/home).

## Configuration

The `_config.yml` file contains everything necessary to make a page on-the-fly in minutes. Open it using any editor and edit the specified fields before pushing it up to the `gh-pages` branch.

- `project`: the *public* name for the project
- `lead`: high-level description for the product
- `repo`: url for the GitHub repository
- `star`: url that lets users to "star" us on GitHub without leaving the page (see the GutHub URL section)
- `fork`: url that lets users to "fork" us on GitHub without leaving the page (see the GutHub URL section)
 

### GitHub URL

Rather than generating a new url, you can easily modify the GitHub user, path, and type by modifying three references:

- `user=`: GitHub username, i.e. "softlayer"
- `repo=`: GitHub repo name
- `type=`: defines which procedure to support, i.e. "fork" or "watch"

# Community

Keep track of development and community news.

- Follow [@SoftLayerDev on Twitter](http://twitter.com/softlayerdev).
- Fork any of our public [GitHub repo’s](http://github.com/softlayer).
- Get the latest new and join conversations on our [Customer Forum](http://forums.softlayer.com/).

# Finding Support

- For more information on Jekyll, visit [Jekyll's Wiki](https://github.com/mojombo/jekyll/wiki).
- For more information on GitHub Pages, visit [GitHub Pages](http://pages.github.com).

# Copyright and License

Copyright (c) 2013 SoftLayer Technologies, Inc., an IBM Company. We license our code under the [MIT license](LICENSE). By contributing your code, you agree to license your contribution under the terms of this license.
