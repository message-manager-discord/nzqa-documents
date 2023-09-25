# Sprint 3

- Start Date: 15/04/2022
- End Date: 18/05/2022
- Work Hard Rating (out of 5): 5

## Project board

### At start

![image](https://github.com/message-manager-discord/nzqa-documents/blob/11d87e57e6847e27de61ccc3531d9d21aae9e164/sprint_1/kanban_end_sprint_1.png)
(or kanban_start_sprint_3.png in sprint_3 folder)

### At end

![image](https://user-images.githubusercontent.com/52091960/168931702-5df6a234-4321-4f1c-b595-3dc02a1907cb.png)
(or see kanban_at_end_sprint_3.png in sprint_3 folder)

## Reflection and Summary

### Summary

This sprint was an extended sprint that ran over a month, due to the holidays. During this sprint I focused on getting the permissions rewrite finished and out. In the last sprint I mentioned that there was an issue with the current deployment, which meant that I needed to get the overall rewrite out as soon as possible. However this issue resolved itself a few days after the last sprint ended (which I assume was due to the issue being caused by something external).

### Major Changes and Achievements

I rewrote permissions to a bitfield system.
This was a major change as it was a move away from the previous system of having a single permission per target, with a inherited hierarchy.
I choose to use a bitfield system as it allows for more granular control.

Changes:

- remove the singular management role system
- add a bitfield system for permissions
- move permission checks to a centralised system
- add a new permission to manage permissions
- add a new permission to manage config
- move logging from commands to the permissions logic
- move logging from commands to the messages logic
- add a new command to manage permissions
- add presets with a quickstart to setup permissions quickly
- add a couple of stronger rules to eslint

### Reflection

Overall I think this sprint went really well and I got a decent amount of work done (~30 hours). I think that this sprint brings me a lot closer to releasing the rewrite, and moving on to the website.

## Notes for next sprint

During the next sprint I will wrap up a few things left to do on the permissions rewrite, and then wrap up a few issues with stability with the overall rewrite. After that I will release the new rewrite.
I'm estimating that this will take up most of next sprint, and I should be able to move on to the website the sprint after that.
