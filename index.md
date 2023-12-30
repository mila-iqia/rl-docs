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

## Docker Templates
To make it easier to scale experiments and have code be more mobile, it is best to use docker and virtual machines. Have a look at the docker templates provided [here](docker.md).

## Contributors

<VPTeamMembers size="small" :members="members" />
