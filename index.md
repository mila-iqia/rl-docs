---
outline: false
---

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  /*{
    avatar: 'https://www.github.com/USERNAME.png',
    name: 'NAME',
    title: 'PhD Student',
    org: "Mila - Quebec AI Institute",
    orgLink: "https://mila.quebec",
    links: [
      { icon: 'github', link: 'https://github.com/USERNAME' },
      { icon: 'twitter', link: 'https://twitter.com/USERNAME' }
    ]
  },*/
]
</script>

# Mila RL Technical Documentation

## Contributors

<VPTeamMembers size="small" :members="members" />
