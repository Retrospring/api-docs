# /sleipnir/user

APIs that interact with users.

## Formats

- `json`
- `msgpack`

## Endpoints

### [GET me.json](user/me.md)

OAuthenticated User's full profile.

### [GET inbox.json](user/inbox.md)

OAuthenticated User's inbox.

### [GET notifications.json](user/notifications.md)

OAuthenticated User's notifications.

### [GET me/ask.json](user/me/ask.md)

Ask a question to all of the OAuthenticated User's followers.

### [GET :id/profile.json](user/:id/profile.md)

Given user id's public profile.

### [GET :id/questions.json](user/:id/questions.md)

Given user id's questions.

### [POST :id/ask.json](user/:id/ask.md)

Ask given user id a question.

### [GET :id/answers.json](user/:id/answers.md)

Given user id's answers.

### [GET :id/followers.json](user/:id/followers.md)

Given user id's followers.

### [GET :id/following.json](user/:id/following.md)

Given user id's following.

### [POST :id/follow.json](user/:id/follow.md)

Follow given user id.

### [DELETE :id/follow.json](user/:id/follow.md)

Unfollow given user id.

### [GET :id/avatar.json](user/:id/avatar.md)

Retrieve given user id's avatar.

### [GET :id/header.json](user/:id/header.md)

Retrieve given user id's header.

##### last revised on: 2015/06/28 11:01
