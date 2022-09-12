# jet-busybox
Jet Ready Auto Configurable Busybox Environment

## Setup

```bash
$ brew install bitwarden-cli
$ brew install chezmoi

$ bw login

? Email address: <your-email-address>
? Master password: [hidden]
You are logged in!

$ bw unlock #important

# Set the session token
export BW_SESSION=<bitwarden-personal-token>
```


## Usage

```bash
chezmoi -- init --apply diegodisant
```