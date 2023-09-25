# `stack` CLI
Airbus UTM Platform `stack` CLI

## Installation

### macOS/Linux one-liner 
```
curl -sSL https://github.com/altiscope/platform-stack-cli/releases/download/v1.19.0/stack_$(
    bash -c '[[ $OSTYPE == darwin* ]] && echo darwin || echo linux'
  )_amd64 -o stack && chmod a+x stack && sudo mv stack /usr/local/bin/
```

### macOS
```
curl -sSL https://github.com/altiscope/platform-stack-cli/releases/download/v1.19.0/stack_darwin_amd64 -o stack && chmod a+x stack && sudo mv stack /usr/local/bin/
```

### Linux
```
curl -sSL https://github.com/altiscope/platform-stack-cli/releases/download/v1.19.0/stack_linux_amd64 -o stack && chmod a+x stack && sudo mv stack /usr/local/bin/
```
