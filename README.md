# setup-labs-mac

## Simply copy/paste this line into terminal and run

```
curl -sL "https://raw.githubusercontent.com/bleuf1sh/setup-labs-mac/master/setupLabsMac.sh?$(date +%s)" > setupLabsMac.sh && bash setupLabsMac.sh
```

## What makes this different than the other auto-setups out there
After using the others, it was difficult to switch to a different version of what was installed. For example, switching between different versions of node or switching from using OracleJDK to OpenJDK was extremely challenging.

Therefore, this scripts primary differentiator is it tries to use an already available version manager when installing different tools or languages to ease transitioning to a different version later, if desired.

It also configures and installs some additional things to make development easier.

### Languages
- OpenJDK 11.x via sdkman
- Gradle 5.2.x via sdkman
- SpringBoot 2.1.x via sdkman
- Node LTS via n
- Python3

### IDE's
- VS Code
- IntelliJ w/ Pivotal IDE Prefs
- *PyCharm w/ Pivotal IDE Prefs
- *goland w/ Pivotal IDE Prefs

### CLI's
- Brew
- Git
- SDK Man
- Cloud Foundry

### Browsers
- Firefox
- Google Chrome
- Google Chrome Canary

### Misc
- iTerm2
- Slack
- Docker
- Postman
- Go2Shell
- FlyCut
- ShiftIt
- The Unarchiver

### Notes
- all hidden files are visible in Finder
- ability to open a terminal from Finder
- default Mac dock is scrubbed of all distractions
- custom Peppermint color in terminals for better readability


*indicates optional