---
layout: default
group: cloud
subgroup: 080_setup
title: Enable SSH keys
menu_title: Enable SSH keys
menu_order: 20
menu_node:
level3_menu_node: level3child
level3_subgroup: workspace
version: 2.0
github_link: cloud/before/before-workspace-ssh.md
redirect_from:
  - /guides/v2.0/cloud/before/before-setup-env-1_get-start.html
  - /guides/v2.1/cloud/before/before-setup-env-1_get-start.html
  - /guides/v2.2/cloud/before/before-setup-env-1_get-start.html
---

#### Previous step:
[Install Magento prerequisites]({{ page.baseurl }}cloud/before/before-workspace-magento-prereqs.html)

The [SSH protocol ](https://en.wikipedia.org/wiki/Secure_Shell){:target="_blank"} is designed to maintain a secure connection between two systems&mdash;in this case, your local working environment and your Magento Enterprise Cloud Edition Git project.

{% include cloud/enable-ssh.md %}


#### Next step
[Set up the Magento file system owner]({{ page.baseurl }}cloud/before/before-workspace-file-sys-owner.html)