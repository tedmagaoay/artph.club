---
title: "{{ replace .Name "-" " " | title }}"

role: Illustrator

social:
  - icon: briefcase
    icon_pack: fas
    link: /{{ path.Base (path.Dir .File.Path) }}

  - icon: twitter
    icon_pack: fab
    link: 
    label: Follow me on Twitter

  - icon: coffee
    icon_pack: fas
    link: 
    label: Support me on Ko-fi
    
  - icon: instagram
    icon_pack: fab
    link: 
    label: Instagram

  - icon: behance
    icon_pack: fab
    link: 
    label: Behance

  - icon: dribbble
    icon_pack: fab
    link: 
    label: Dribbble

highlight_name: true

user_groups:
  - Artists
  - Top Artists
---
