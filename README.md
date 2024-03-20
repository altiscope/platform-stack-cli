# `stack` CLI
Airbus UTM Platform `stack` CLI

## Installation

### macOS/Linux one-liner 
```
curl -sSL https://github.com/altiscope/platform-stack-cli/releases/download/v1.19.4/stack_$(
  bash -c '[[ $OSTYPE == darwin* ]] && (uname -m | grep -q arm && echo darwin_arm64 || echo darwin_amd64) || (uname -m | grep -q x86_64 && echo linux_amd64 || echo linux_arm64)'
) -o stack && chmod +x stack && sudo mv stack /usr/local/bin/
```
