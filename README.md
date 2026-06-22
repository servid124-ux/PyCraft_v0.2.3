# PyCraft
> Minecraft Classic server (protocol 7) — built from scratch in Python.

Runs on **Android (Termux)** and **Linux**.

---

## Download

```bash
wget https://github.com/user-attachments/files/29197772/PyCraft_v0.2.3.zip
```

---

## Installation

### Android (Termux)

```bash
pkg install python unzip
unzip PyCraft_v0.2.3.zip -d PyCraft
cd PyCraft
sh Start.sh
```

### Linux

```bash
sudo apt install python3 unzip
unzip PyCraft_v0.2.3.zip -d PyCraft
cd PyCraft
sh Start.sh
```

---

## Connecting

Open **ClassiCube** → Options → Servers → Direct connect

| Field | Value |
|---|---|
| Host | `localhost` |
| Port | `25565` |

To connect from another device on the same network, use your local IP instead of `localhost`.

---

## Commands

| Command | Description |
|---|---|
| `/help` | List all commands |
| `/players` | Show connected players |
| `/spawn` | Teleport to spawn |
| `/pos` | Show your position |
| `/me <text>` | Action message |
| `/msg <player> <text>` | Private message |
| `/r <text>` | Reply to last private message |
| `/plugins` | List active plugins |

**OP only:**

| Command | Description |
|---|---|
| `/tp <player>` | Teleport to player |
| `/kick <player>` | Kick a player |
| `/ban <player>` | Ban a player |
| `/op <player>` | Grant OP |
| `/deop <player>` | Revoke OP |
| `/setspawn` | Set spawn to your position |
| `/save` | Save the world manually |

---

## Configuration

Edit `server.properties` to customize your server.

```properties
server-name=My Server
max-players=20
port=25565
world-generator=normal
```

---

## Version

**0.2.3** — Classic protocol 7
