# DOCUMENTATION: Pimp my intra

default name: style
type: .css

## Properties types

┌───────────────────────────────────┬───────────────┐
│             HEADER                │  PROPERTIES   │
├───────────────────────────────────┼───────────────┤
│ custom-header-logo-background     │ background    │
│ custom-header-background          │ background    │
├───────────────────────────────────┼───────────────┘
│               GPA                 │
├───────────────────────────────────┼───────────────┐
│ custom-gpa-display                │ display       │
│ custom-before-gpa                 │ content       │
│ custom-after-gpa                  │ content       │
├───────────────────────────────────┼───────────────┘
│             SIDEBAR               │
├───────────────────────────────────┼───────────────┐
│ custom-sidebar-background         │ background    │
│ custom-sidebar-hover-background   │ background    │
├───────────────────────────────────┼───────────────┘
│             PROFILE               │
├───────────────────────────────────┼───────────────┐
│ custom-profile-picture            │ background    │
├───────────────────────────────────┼───────────────┘
│              LOGIN                │
├───────────────────────────────────┼───────────────┐
│ custom-login-button               │ background    │
├───────────────────────────────────┼───────────────┘
│              GRAPH                │
├───────────────────────────────────┼───────────────┐
│ custom-log-graph-fill             │ fill & stroke │
├───────────────────────────────────┼───────────────┘
│           INFORMATION             │
├───────────────────────────────────┼───────────────┐
│ custom-pedago-i-display           │ display       │
├───────────────────────────────────┼───────────────┘
│               TABS                │
├───────────────────────────────────┼───────────────┐
│ custom-top-tabs-background        │ background    │
├───────────────────────────────────┼───────────────┘
│             SECTIONS              │
├───────────────────────────────────┼───────────────┐
│ custom-sections-color             │ background    │
├───────────────────────────────────┼───────────────┘
│         MAIN BACKGROUND           │
├───────────────────────────────────┼───────────────┐
│ custom-main-background            │ background    │
└───────────────────────────────────┴───────────────┘

### Configuration example
```
custom-profile-picture=url(https://pbs.twimg.com/profile_images/771263594025537540/zw3cvfor_400x400.jpg)
custom-login-button=url(https://pbs.twimg.com/profile_images/771263594025537540/zw3cvfor_400x400.jpg)
custom-header-logo-background=url(https://cdn.freebiesupply.com/logos/large/2x/github-octocat-logo-black-and-white.png)
custom-header-background=url(https://github.com/Neotoxic-off/pmi/raw/master/img/wall.jpg)
custom-top-tabs-background=#000
custom-log-graph-fill=#000
custom-main-background=#000
custom-sections-color=rgba(255, 255, 255, 0.5)
custom-sidebar-background=#000
custom-sidebar-hover-background=grey
custom-gpa-display=block
custom-pedago-i-display=block
before-gpa=66
after-gpa=99
email=user.login@epitech.eu

END=HERE
```