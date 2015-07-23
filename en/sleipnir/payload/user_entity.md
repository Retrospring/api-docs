# UserEntity

Describes a user

## example

```json

  "id": 1,
  "screen_name": "mack2",
  "display_name": "Hans Emmerich",
  "avatar": ProfilePictureProxy,
  "header": ProfileHeaderProxy,
  "motivation_header": "",
  "website": "",
  "location": "",
  "bio": "",
  "flags": {
    "admin": true,
    "moderator": false,
    "supporter": false,
    "blogger": false,
    "contributor": false,
    "translator": false,
    "app_developer": false
  },
  "banned": {
    "banned": false,
    "until": 0,
    "reason": ""
  },
  "locale": "en",
  "friend_count": 1,
  "follower_count": 1,
  "question_count": 0,
  "answer_count": 1,
  "comment_count": 1,
  "smile_count": 1,
  "comment_smile_count": 0,
  "allow_anonymous_questions": true,
  "allow_stranger_answers": true,
  "member_since": 1437611356
}
```

# ProfilePictureProxy

Describes a profile picture

## example

```json
{
  "large": "https://retrospring.net/images/large/no_avatar.png",
  "medium": "https://retrospring.net/images/medium/no_avatar.png",
  "small": "https://retrospring.net/images/small/no_avatar.png"
}
```

# ProfileHeaderProxy

Describes a profile header

## example

```json
{
  "web": "https://retrospring.net/images/header/web/no_header.jpg",
  "mobile": "https://retrospring.net/images/header/mobile/no_header.jpg",
  "retina": "https://retrospring.net/images/header/retina/no_header.jpg"
}
```

##### last revised on: 2015/07/23 06:07
