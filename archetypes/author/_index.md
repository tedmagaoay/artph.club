---
title: "{{ replace .Name "-" " " | title }}"

role: Artist

social:
  - icon: briefcase
    icon_pack: fas
    link: /{{ path.Dir .File.Path }}

  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/
    label: Follow me on Twitter

highlight_name: false

user_groups:
  - Artists
---
