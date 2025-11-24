# SSH Setup Notes - Tier 0 Foundation

## Keys Created

- Private key: `~/.ssh/id_ed25519_tier0_demo`
- Public key: `~/.ssh/id_ed25519_tier0_demo_pub`

## Config File

Location: `ssh_config.example`
Usage: Copy to `~/.ssh/config` and use `ssh demo-server`

## Security Notes

- Never share your private key
- Public keys can be shared safely
- Consider using passphrases for production keys
