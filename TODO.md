# TODO APP PLANNING

## TODO SCHEMA
```
{
    unique Id: string
    parentTask: ObjectId
    title: string
    description: string
    subTasks: [
        ObjectId,
        ...
    ]
    done: boolean
    deadline: dateTime
    list: ObjectId,
}
```
## REQUIREMENTS
- Can Add Task
- Can Remove Task
- Can Add Deadline For A Task
- Can Mark A Task As Done
- Can Add Subtasks
- Can Drag Task To Change Its Priority 
- Can create multiple lists
- Can add tasks to lists