# Activity

#|Title
---|-----
1|[Overview](./st_activity.md/#overview)
2|[Activity Behavior](./st_activity.md/#activity-behavior)
3|[Activity Options](./st_activity.md/#activity-options)

## Overview

the Activity is the **Edges** /Lines that get out from **form**, and it describes how the flow "next form" in the process.
in most cases, we have for the form three Activities so we call **first three Activities** in code:

1. approve
2. rejected
3. return
and in any case, we have an extra option we can call it and a related name like "extra button".  
**Note** if there is more than Edge/Line get out from the same form all count as one activity with the same name "Like: activity 1  in [this](./general.md/#general-image)"
**Note** There is one extra activity that works all over the process called "end request" that end and kills the request.

## Activity Behavior

for each process the activity has one of **three behavior**:

1. Sequence: when the activity has a specific order and a specific person or grope of people that end-User **cant** change or assign a different person to it.
Like:
2. route/ manual: when the activity can be assigned to a specific person or group of people
**Like:**  
sending Emails "Form" => "To".
3. parallel: it's a compost between sequence and arrow that the activity has specific order but as default behavior but could also assign to other people.
Like:

-----

## Activity Options

1. lookTask: that we can disable the [request](./Terms.md) form the other users if the request assign to a person
2. task or copy:if the user can edit we count it as "task" /if the user can edit we count it as "copy" (LIKE:the difference between "to" and "cc" in email)
