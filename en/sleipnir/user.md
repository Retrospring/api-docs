# /sleipnir/user

## Formats

- `json`
- `msgpack`

## Endpoints

### [GET /me.json](user/me.md)

`GET https://retrospring.net/api/sleipnir/user/me.json`

Current user's profile

### [GET /timeline.json](user/timeline.md)

`GET https://retrospring.net/api/sleipnir/user/timeline.json`

Current user's timeline

### [GET /public.json](user/public.md)

`GET https://retrospring.net/api/sleipnir/user/public.json`

Public timeline

### [GET /new.json](user/new.md)

`GET https://retrospring.net/api/sleipnir/user/new.json`

Current user's new numbers

### [GET /inbox.json](user/inbox.md)

`GET https://retrospring.net/api/sleipnir/user/inbox.json`

Current user's inbox

### [DELETE /inbox.json](user/inbox.md)

`DELETE https://retrospring.net/api/sleipnir/user/inbox.json`

Delete entries from a user's inbox

### [GET /notifications.json](user/notifications.md)

`GET https://retrospring.net/api/sleipnir/user/notifications.json`

Current user's notifications

### [PATCH /notifications/:id.json](user/notifications/:id.md)

`PATCH https://retrospring.net/api/sleipnir/user/notifications/:id.json`

Mark notification as read

### [PATCH /inbox/:id.json](user/inbox/:id.md)

`PATCH https://retrospring.net/api/sleipnir/user/inbox/:id.json`

Mark inbox as read

### [DELETE /inbox/:id.json](user/inbox/:id.md)

`DELETE https://retrospring.net/api/sleipnir/user/inbox/:id.json`

Delete entry from a user's inbox

### [GET /:id/profile.json](user/:id/profile.md)

`GET https://retrospring.net/api/sleipnir/user/:id/profile.json`

Given user's profile

### [GET /:id/questions.json](user/:id/questions.md)

`GET https://retrospring.net/api/sleipnir/user/:id/questions.json`

Given user's questions

### [GET /:id/answers.json](user/:id/answers.md)

`GET https://retrospring.net/api/sleipnir/user/:id/answers.json`

Given user's answers

### [GET /:id/followers.json](user/:id/followers.md)

`GET https://retrospring.net/api/sleipnir/user/:id/followers.json`

Given user's followers

### [GET /:id/following.json](user/:id/following.md)

`GET https://retrospring.net/api/sleipnir/user/:id/following.json`

Given user's following

### [POST /me/ask.json](user/me/ask.md)

`POST https://retrospring.net/api/sleipnir/user/me/ask.json`

Ask all your followers a question

### [POST /:id/ask.json](user/:id/ask.md)

`POST https://retrospring.net/api/sleipnir/user/:id/ask.json`

Ask user a question

### [POST /:id/follow.json](user/:id/follow.md)

`POST https://retrospring.net/api/sleipnir/user/:id/follow.json`

Follow given user

### [DELETE /:id/follow.json](user/:id/follow.md)

`DELETE https://retrospring.net/api/sleipnir/user/:id/follow.json`

Unfollow given user

### [GET /:id/avatar.json](user/:id/avatar.md)

`GET https://retrospring.net/api/sleipnir/user/:id/avatar.json`

Specified user's profile picture

### [GET /:id/header.json](user/:id/header.md)

`GET https://retrospring.net/api/sleipnir/user/:id/header.json`

Specified user's profile header

### [POST /:id/ban.json](user/:id/ban.md)

`POST https://retrospring.net/api/sleipnir/user/:id/ban.json`

Ban specified user

### [DELETE /:id/ban.json](user/:id/ban.md)

`DELETE https://retrospring.net/api/sleipnir/user/:id/ban.json`

Unban specified user

##### last revised on: 2015/07/19 23:22
