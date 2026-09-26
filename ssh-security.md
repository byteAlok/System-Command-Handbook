# 📦 Chunk 4C (Commands 206–220)
### Security & Remote Administration

### 🔐 Category 17: SSH & Security (Commands 206–220)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 206 | `ssh` | Securely connects to remote Linux servers over SSH. | `ssh ubuntu@192.168.1.10` |
| 207 | `ssh-keygen` | Generates secure public and private SSH key pairs. | `ssh-keygen -t ed25519` |
| 208 | `ssh-copy-id` | Copies public SSH key to remote server. | `ssh-copy-id ubuntu@server` |
| 209 | `scp` | Securely copies files between local and remote systems. | `scp app.jar user@server:/opt/apps` |
| 210 | `sftp` | Securely transfers files using SSH file transfer. | `sftp user@server` |
| 211 | `ssh-agent` | Manages SSH private keys for authentication sessions. | `eval $(ssh-agent -s)` |
| 212 | `ssh-add` | Adds private keys to running SSH agent. | `ssh-add ~/.ssh/id_ed25519` |
| 213 | `openssl` | Generates certificates and performs cryptographic operations securely. | `openssl version` |
| 214 | `gpg` | Encrypts, decrypts, and digitally signs sensitive files. | `gpg -c secrets.txt` |
| 215 | `base64` | Encodes or decodes data using Base64 encoding. | `echo "Hello" \| base64` |
| 216 | `sha256sum` | Calculates SHA-256 checksum for integrity verification. | `sha256sum app.zip` |
| 217 | `sha512sum` | Calculates SHA-512 checksum for stronger integrity verification. | `sha512sum app.zip` |
| 218 | `md5sum` | Calculates MD5 checksum for quick file comparison. | `md5sum app.zip` |
| 219 | `hostnamectl` | Displays or changes system hostname configuration safely. | `hostnamectl set-hostname web-server` |
| 220 | `timedatectl` | Displays or configures system date and timezone. | `timedatectl status` |

> **Chunk 4C Complete (Commands 206–220)**
> Covered Categories:
> - 🔐 Category 17: SSH & Security (206–220)
