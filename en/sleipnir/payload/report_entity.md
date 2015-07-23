# ReportEntity

Describes a report

Polymorphic

## example

```json
{
  "id": 1,
  "votes": 1,
  "type": "Reports::Answer",
  "target": PolymorphicReportEntity
}
```

## PolymorphicReportEntity

pseudocode

```ruby
if type is "Reports::Answer"
  be a AnswerEntity
elsif type is "Reports::Comment"
  be a CommentEntity
elsif type is "Reports::Question"
  be a QuestionEntity
elsif type is "Reports::User"
  be a UserSlimEntity
else
  have keys "id" as Int and "error" as String
end

##### last revised on: 2015/07/23 06:07
