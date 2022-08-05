# Sprint 2

- Start Date: 01/04/2022
- End Date: 14/04/2022
- Work Hard Rating (out of 5): 5

## Project board

No change

## Reflection and Summary

### Reflection

This sprint did not achieve goals as set out to, however a lot of work was done. The sprint was interrupted with time away from school and classtime, and I also had to focus energy elsewhere on the project.

Near the start of the sprint I discovered an issue with the existing infrastructure (that is user facing and deployed) that was causing significant downtime. I was not able to narrow down the exact cause of the issue, but I did have a plan to resolve it.  
However this required the deployment of a new system, which wasn't quite finished yet (something that wasn't in the scope of this project). That new system was a rewrite, that was being completed alongside (and in parallel) the project.  
Because this was urgent I decided to delay work on the scope of the project, and focus on the rewrite (fix) to the issue.  
I am nearly finished with that fix, and I will deploy it over the weekend. After that I will then move back to focusing on the progressing of the main focus of the project (the website and dashboard interface).

#### Brief summary of the "rewrite"

The project is the creation of a dashboard, and api to allow users to manage messages through the dashboard, and not just through discord directly.

There is an existing project and code base, that currently only allows users to manage messages through discord.
Before the project started I was in the process of rewriting the system to use discord interactions instead of plain messages. This rewrite would then be built off to create the dashboard api.

I did not consider the rewrite part of this project as this project was mainly focused upon the dashboard and api.

#### The issue

The issue that started occurring near the start of the sprint was an issue with connecting to discord. I'm still not sure why it is occurring, but I suspect it is because the old system relies on libraries that are not maintained anymore.
![error](https://user-images.githubusercontent.com/52091960/182989141-6013be76-b627-455a-ba02-6e1b6ffa6da4.png)

After this started, I switched focus to getting the rewrite out as soon as possible. The bare minium for the rewrite was to get feature parity with the existing system.

#### Work completed

The majority of the work on the rewrite was already completed before this issue happened. However there were still a few features lacking.

- An info / docs command. This replaced the `/info` commands from the existing system. 03431f9feab2e7b3cec77e34c38535d70d55ceca

- Completed the integration of a logging system that matches the existing logging system into the rewrite. fadce517efe80a17c673e5a4d2d79ef4fdaf3e9a This took up the majority of the time as it was a massive piece of work

- A method to migrate to the new system. This is still being worked on at the end of this sprint, but is near completion.
  ![wakatime](https://user-images.githubusercontent.com/52091960/182989153-73654dd5-9675-43a1-81f7-4f6660a54240.png)

## Testing

- Self testing to ensure that the rewrite worked. Eg each interaction is responded to correctly

## Notes for next sprint

Start on work that was meant to happen this sprint.
