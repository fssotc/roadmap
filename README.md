MTCFSS Roadmap
===
[![Stories in Workshops](https://badge.waffle.io/mtcfss/roadmap.svg?label=training-proposal&title=Workshops)](http://waffle.io/mtcfss/roadmap)
[![Stories in Challenges](https://badge.waffle.io/mtcfss/roadmap.svg?label=challenges-proposal&title=Challenges)](http://waffle.io/mtcfss/roadmap)
[![Stories in Events](https://badge.waffle.io/mtcfss/roadmap.svg?label=events-proposal&title=Events)](http://waffle.io/mtcfss/roadmap)
[![Stories in Ready](https://badge.waffle.io/mtcfss/roadmap.svg?label=ready&title=Ready)](http://waffle.io/mtcfss/roadmap)

MTCFSS Roadmap (events, workshops, challenges) using Kanban/Issues model.
All issues are managed on [this waffle board](https://waffle.io/mtcfss/roadmap).

### Workflow:

- There are 4 type of tasks: _`Workshop/Training`_, _`Events`_, _`Challenges`_, _`Others`_
- Every task (card) is done on 4 steps:
  - **Backlog:** Idea is still not approved
  - **Ready:** Idea approved and waiting for someone to do it
  - **In progress:** Task is being worked on by someone (development, testing, admin,...)
  - **Done:** Task completed and well tested.
- Each Task has a _description_ and _comments_
- Task can be assigned to one or more persons
- Task can added to a GitHub _milestone_ to track progress and dependency
- Task can have many _labels_ (tags)

```
                          Task Card Detail
  +------------------------------------------------------------------+
  | <ID>                                                  <ASSIGNED> |
  |                                                                  |
  | <TITLE>                                                          |
  |                                                                  |
  | <LABLES>        <LINK>  <STORY_POINTS>  <DESCRIPTION_&_COMMENTS> |
  +------------------------------------------------------------------+
```

### Permissions:

Only members of **@mtcfss/roadmap** team have write permission to the tasks (issues, PRs):
- Open, close, assign any task
- Change task labels, milestones
- Update descriptions and comments of the tasks

Non-members default permissions are read only others tasks and open new tasks.

To gaint write permissions, create a [new request](https://github.com/mtcfss/roadmap/issues/new) to join **@mtcfss/roadmap**.
