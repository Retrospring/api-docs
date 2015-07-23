# NotificationEntity

Describes a notification.

Polymorphic.

## example

```json
{
  "id": 1,
  "type": "Comment",
  "target": PolymorphicNotificationEntity,
  "new": false
}
```

## PolymorphicNotificationEntity

Pseudocode

```ruby
if type is "Comment"
  have keys "comment" as CommentEntity
elsif type is "CommentSmile"
  have keys "user" as UserSlimEntity and "comment" as CommentEntity
elsif type is "Smile"
  have keys "user" as UserSlimEntity and "answer" as AnswerEntity
elsif type is "Answer"
  have keys "answer" as AnswerEntity
elsif type is "Question"
  have keys "question" as QuestionEntity
elsif type is "Relationship"
  have keys "relationship" as RelationshipEntity
else
  have keys "id" as Int and "error" as String
```


##### last revised on: 2015/07/23 06:07
