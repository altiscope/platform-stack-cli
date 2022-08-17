# `stack` CLI
Airbus UTM Platform `stack` CLI

## Installation

### macOS/Linux
```
curl -sSL https://github.com/altiscope/platform-stack-cli/releases/download/v1.10.0/stack_$(
    bash -c '[[ $OSTYPE == darwin* ]] && echo darwin || echo linux'
  )_amd64 -o stack && chmod a+x stack && sudo mv stack /usr/local/bin/
```
