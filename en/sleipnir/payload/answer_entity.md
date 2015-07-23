# AnswerEntity

Describes answers

## example

```json
{
  "id": 1,
  "answer": "This is an answer.",
  "comment_count": 1,
  "smile_count": 1,
  "user": UserSlimEntity,
  "question": QuestionEntity,
  "created_with": ApplicationReferenceEntity,
  "subscribed": true,
  "created_at": 1437571999
}
```

## notes

there's a possible bug where the `subscribed` key will not appear

##### last revised on: 2015/07/23 06:07
