# <img src="(optional logo URL)" width="32" height="32"> StaffCore  
> Advanced staff management plugin for Minecraft servers.

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Spigot Version](https://img.shields.io/badge/Spigot-1.16.5%20to%201.20.4-blue)](https://www.spigotmc.org/)
[![GitHub Issues](https://img.shields.io/github/issues/<yourname>/StaffCore)](https://github.com/<yourname>/StaffCore/issues)

---

## ✨ Features  
- **Moderation Tools**:  
  - Ban/Mute/Warn players with customizable reasons.  
  - Freeze players and block movement.  
  - Clear chat globally or per-player.  
- **Staff Utilities**:  
  - Vanish mode (fully hidden from players).  
  - Staff chat with private messaging.  
  - Teleportation and inventory inspection (`/invsee`).  
- **Advanced Systems**:  
  - Alt-account detection (IP-based).  
  - Punishment history tracking.  
  - Configurable messages and permissions.  

---

## 📥 Installation  
1. Download the latest JAR from [Releases](https://github.com/<yourname>/StaffCore/releases).  
2. Place the JAR in your server’s `plugins/` folder.  
3. Restart the server.  

---

## 🛠 Commands  
| Command | Description | Permission |  
|---------|-------------|------------|  
| `/ban <player> [reason]` | Ban a player. | `staffcore.ban` |  
| `/vanish` | Toggle invisibility. | `staffcore.vanish` |  
| `/staffchat [message]` | Send staff-only messages. | `staffcore.staffchat` |  
| **...** | **[Full Command List](COMMANDS.md)** |  

---

## ⚙ Permissions  
```yaml
staffcore.*: # Full access  
  children:  
    staffcore.ban: true  
    staffcore.mute: true  
    staffcore.vanish: true  
staffcore.admin: # Admin perms  
  default: op  
staffcore.mod: # Moderator perms  
  default: false  
