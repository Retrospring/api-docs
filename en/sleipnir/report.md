# /sleipnir/report

## Formats

- `json`
- `msgpack`

## Endpoints

### [GET report.json](root/report.md)

`GET https://retrospring.net/api/sleipnir/report.json`

Get reports

### [POST /user/:id.json](report/user/:id.md)

`POST https://retrospring.net/api/sleipnir/report/user/:id.json`

Report a user

### [POST /question/:id.json](report/question/:id.md)

`POST https://retrospring.net/api/sleipnir/report/question/:id.json`

Report a question

### [POST /comment/:id.json](report/comment/:id.md)

`POST https://retrospring.net/api/sleipnir/report/comment/:id.json`

Report a comment

### [POST /answer/:id.json](report/answer/:id.md)

`POST https://retrospring.net/api/sleipnir/report/answer/:id.json`

Report an answer

### [GET /:id.json](report/:id.md)

`GET https://retrospring.net/api/sleipnir/report/:id.json`

Get a report

### [DELETE /:id.json](report/:id.md)

`DELETE https://retrospring.net/api/sleipnir/report/:id.json`

Delete report

### [GET /:id/comment.json](report/:id/comment.md)

`GET https://retrospring.net/api/sleipnir/report/:id/comment.json`

Get report comments

### [POST /:id/comment.json](report/:id/comment.md)

`POST https://retrospring.net/api/sleipnir/report/:id/comment.json`

Comment on report

### [DELETE /:id/comment/:comment_id.json](report/:id/comment/:comment_id.md)

`DELETE https://retrospring.net/api/sleipnir/report/:id/comment/:comment_id.json`

Delete report comment

### [POST /:id/vote.json](report/:id/vote.md)

`POST https://retrospring.net/api/sleipnir/report/:id/vote.json`

Vote a report up

### [DELETE /:id/vote.json](report/:id/vote.md)

`DELETE https://retrospring.net/api/sleipnir/report/:id/vote.json`

Vote a report down

##### last revised on: 2015/07/19 23:22
