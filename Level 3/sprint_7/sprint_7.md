# Sprint 7

- Start Date: 9/07/2022
- End Date: 30/09/2022
- Work Hard Rating (out of 5): 5

## Project board

### At Start

![Screen Shot 2022-07-09 at 4 34 46 PM](https://user-images.githubusercontent.com/52091960/178091737-6ba34b0f-0b44-40a8-b48c-2d2e98befaf9.png)
(or kanban_at_start_sprint_7.png in sprint_7 folder)

### At End

![Screen Shot 2022-09-30 at 2 24 22 PM](https://user-images.githubusercontent.com/52091960/193169973-47b0bb75-2fcc-4e36-9817-09006fdb8ac3.png)
(or kanban_at_end_sprint_7.png in sprint_7 folder)

## Website

### At Start

(see site_at_start_sprint_7.png in sprint_7 folder)

### At End

(see site_at_end_sprint_7.png in sprint_7 folder)

## Reflection and Summary

### Major Changes and Achievements

(this is in time order)

Backend API:

- Bug Fix (ensuring message id is valid when accepting raw message ids) to avoid discord 400 errors - 405e958369efb04aa9044e8a2040261bf30fcb90
- Bug Fix: reduce modal title length when it is too long (with long channel names) - the was causing the modal to "fail" with just a generic error message displayed to users - d2f92b520b0fc1a52cb30d13f6790a00fc675ec1
- Documentation: improve overall comments and readability of code - 46ada2740d54e4313adaca5f53e1529ea8968b9a

Site:

- Rework website with remix and improve overall styles - 6d889465b1cf26efdfbd9bfd5d7f78942cabd074
- Improve overall comments and readability of code - e824dbf70276afefe0373f58aa82e38d221a7dbc

### Reflection

This sprint was pretty slow, as it was the final wrap up of the project. I did do a lot of work on the website, improving it's overall quality and ease of use (see screenshots). On the backend, I did a few bug fixes after the bugs were raised to me by users.
I also reviewed all the code so far, and improved the comments for documentation for readability in the future.
The project is in a position to submit.

## Testing

### Bug with message ids

There was a bug with message ids, where if a message id was invalid, it would cause a 400 error. This was fixed by ensuring the message id was valid before sending it to discord.  
!(image)[messageiderror1_sprint_7.jpg]  
!(image)[messageiderror2_sprint_7.jpg]

### Bug with long channel names

There was a bug with long channel names, where the modal title would be too long, and so the interaction response with the modal would fail with "interaction failed". This was fixed by reducing the length of the title when it was too long.  
!(image)[channellengtherror1_sprint_7.jpg]  
!(image)[channellengtherror2_sprint_7.jpg]
