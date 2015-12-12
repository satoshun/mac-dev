# Mac Development

## Setup

Install Xcode & Homebrew & ansible

```shell
$ sudo xcodebuild -license
$ xcode-select --install
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew update
$ brew install ansible
```

Running ansible playbook.

```shell
$ ansible-playbook main.yml -i inventory
```
