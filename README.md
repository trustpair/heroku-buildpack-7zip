# trustpair-7zip
Buildpack to add 7zip binary to Heroku applications.

## Features
- Use [official ubuntu 22 7zip binary](https://packages.ubuntu.com/jammy/7zip). It may change as it depends on the Heroku stack. Tested on stack 22
- Version locked to 21.07
- For retro-compatibility, alias `7zz` (official binary name) to `7z`
