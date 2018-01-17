# jbTimelog

A web app that uses [AngularDart](https://webdev.dartlang.org/angular) and
[AngularDart Components](https://webdev.dartlang.org/components).

Created from templates made available by Stagehand under a BSD-style
[license](https://github.com/dart-lang/stagehand/blob/master/LICENSE).

## Planned Features
- Main page is a list of tracking entries (worklogs), top worklog space can be used 
to create a new time log entry manually or to setup and start a new time tracker.
- Start and end time for worklogs can be changed at all times 
(when creating or editing a time entry or tracker). 
- One time entry includes
    - Task Name (Entries with the same Task in one Day can be grouped)
    - Project (with or without assigned client) - with font in project color 
      for easier visual separation
    - Worklog start, end and duration values
    - a button to copy the worklog contents to a new tracker and start it
    - a description field
    
## Feature whishlist after 1.0
- Jira integration


## Why another time tracking app?
I've tried various Time Tracking Apps, but each had it's own flaws for my use case or in general.

### Jira Worklog Assistant
- Bad: Not very reliable, crashes sometimes and losses times with it. 
- Bad: Also has a floating bar for creating new time trackers, which is more bulky than i like.
- Good: editing of tracked times is very good

### Toggl
This was my main tracking tool. Unfortunately, it lacked some functionality I wanted, like: 
- separated fields for task name and description 
  (which makes grouping and detailed worklog description very difficult together)
- more detailed grouping options for worklogs  

Additionally it crashed occasionally. 

## SuperProductivity 
- Good: Has nice material design 
- Good: Has Jira integration
- Bad: Has a learning curve to it
- Bad: Does not play nice with my workflow 
 (I don't plan my day in tickets, but 
  I plan to work on one or two bigger topics and 
  search for the assigned tickets when I need them)
- because of the point before, the interface seems cluttered to me

## Bee Time Tracking for Mac 
- Good: very nice Jira integration (amongst others)
- Problem: Time Logs can't be edited after tracking and will be pushed directly to jira.

## MyHours 
- Good: Has a dedicated field for worklog descriptions
- Good: Worklog rounding happens with the click of a button 
  (+ and - buttons besides duration field)
- Bad: No coloring of projects 
- Bad: start and end times can't be edited when starting a tracker in compact ui mode