---
setting: logs-nickname
---

# Logs-nickname

A custom set message to be posted when a user changes their nickname in the server.

# Usage

- `$conf logs-nickname default`
- `$conf logs-nickname disable`
- `$conf logs-nickname embed`
- `$conf logs-nickname [message]`

# Variables

- `{user}` or `{user.mention}` will mention the user
- `{user.name}` will return the username
- `{user.id}` will return the user id
- `{user.avatar}` will return the user avatar url
- `{user.discrim}` or `{user.discriminator}` will return the user discriminator
- `{user.tag}` will return the user tag
- `{user.created}` will return the user's created date
- `{user.nick}` or `{user.nickname}` will return the new nickname
- `{user.oldnick}` or `{user.oldnickname}` will return the old nickname
- `{guild.name}` or `{server.name}` will return the guild name
- `{guild.id}` or `{server.id}` will return the guild id
- `{guild.members}` or `{server.members}` will return the number of members in the guild
- `{now}` will return the current date and time
- `{now.time}` will return the current time
- `{now.date}` will return the current date
