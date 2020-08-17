## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- right
- of course
- that sounds good
- correct
- yeah
- thanks
- thankyou
- ok
- okay
- cool

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really
- nope
- nah

## intent:query_entity
- When are the [holidays](object_type)?
- show me all [holidays](object_type)
- [holidays](object_type)
- [holiday]{"entity": "object_type", "value": "holidays"} list
- Hey bot, I am bored, can you tell me next [holiday](object_type) please?
- on which [day](attribute) is [1](mention)
- [3](mention) is on which [day](attribute)
- which [day](attribute) does [the first one]{"entity": "mention", "value": "1"} fall on
- which [day](attribute) does [the second one]{"entity": "mention", "value": "2"} fall on
- which [day](attribute) does [the third one]{"entity": "mention", "value": "3"} fall on
- which [day](attribute) does [the last one]{"entity": "mention", "value": "last"} fall on
- does [any](mention) [holiday](object_type) fall on a [monday]{"entity": "attribute", "value": "day"}
- which holiday gives me a long weekend
- show me all [holidays](object_type) in this month
- [holidays](object_type) in [Sep](month)
- [holidays](object_type) in [oct](month)
- [holidays](object_type) in [Dec](month)
- [holidays](object_type) in [november](month)
- [Oct](month) [holidays](object_type)
- [Sept](month) [holidays](object_type)
- [nov](month) [holidays](object_type)
- what [day](attribute) is [Bhai Dooj](holidays) on?
- what [day](attribute) is [Anant Chaturdashi]("entity": "object_type", "value": "holidays") on?
- what [day](attribute) is [Gandhi jayanti](holidays) on?
- [Bhai Dooj](holidays) is on what [day](attribute))?
- [holidays](object_type) in [Oct](month)
- [holiday]{"entity": "object_type", "value": "holidays"}
- [number](attribute) for [IS](object_type)
- [IS](object_type) details 
- [IS](object_type) contact 
- [IS](object_type) extension 
- [IS](object_type) helpdesk number 
- whats the extension for [IS](object_type)
- [is](object_type:IS) extension number
- [RMG](object_type) contact numbers 
- contact [RMG](object_type)
- contact [rmg](object_type:RMG)
- what is the contact number for [RMG](object_type)
- [RMG](object_type) extension
- extension for [RMG](object_type)
- phone for [RMG](object_type)
- [resource management](object_type:RMG) group extension number
- extension for [training](object_type)
- [training](object_type) department contact
- [training](object_type) dept number
- [training](object_type) ext 
- [train](object_type) number 
- what is the number for the [training](object_type) department?
- number for [training](object_type)
- number for [RMG](object_type)
- number for [rmg](object_type:RMG)


## synonym:1
- the first one

## synonym:2
- the second one

## synonym:3
- the third one

## synonym:Nov
- nov
- november
- November

## synonym:Oct
- oct
- octo
- october
- October

## synonym:Sep
- sep
- sept
- september
- September

## synonym:day
- monday

## synonym:holidays
- holiday
- leave
- leaves

## synonym:last
- the last one

