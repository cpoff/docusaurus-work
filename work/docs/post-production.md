---
title: Add videos to Posts
sidebar_label: Add videos to Posts
slug: video-prod
---

Posts are the default WordPress content vehicle, unlike Pages - which are index/landing pages that lead to deeper content. Posts are that deeper content, the ideal destination for users seeking specific content. They WP admin internace contains key content elements such as hed, summary/excerpt, featured images & video, plus enhanced data (categories, tags, etc.).

## Create event in Outlook Calendar

-Create a new event. Best to use the Office 365 version of Outlook in a web browser.<br />
-Select site calendar where you want the event to appear: PAG-Main, RTA-Main (includes RTA & RTAnext), or PAG/RTA-Shared (appears on both sites)<br />
-Add standard date, start/end times, reminder (optional)<br />
-Add only internal attendees (e.g. committee chair) and no external attendees. (External attendees will be added later, after the event is fully produced.)<br />
-Reserve conference room, or select Virtual<br />
-Go into Response Options, select Hide Attendee List&#42; and Allow Forwarding. Leave Request Responses unchecked for virtual meetings and checked if we host the meeting at PAG. <br />
-Send<br />

:::important
The Hide Attendee List is only available using Outlook in Office 365. So you'll need to edit the event using a web browser.
:::

That creates your new meeting/event without making it visible to the public. At this point everything is still private.

## Approvals

Two things require approvals: the associated documents, and the meeting itself. 

-Sheila will deliver approved documents through a separate workflow, and those docs should be attached to the meeting in Outlook. Documents require specific naming convention. [See below](/docs/event-workflow#document-naming-convention)

-Approval for the meeting as a whole (the final go-ahead) will also come from Sheila. Once approval is given, go into the event in Outlook and add the **Green category**. 

:::tip
The sole purpose of the **Green** category is to indicate status, with **Green** being equivalent to LIVE. If it's **Green**, it's eligible to be viewed by the public. That's why the category should only be added once past the approvals threshold. Without the **Green** category it's not eligible and will not appear on the public calendars. There shouldn't be any need to change the category once the docs & event are approved and set to **Green**.
:::

After **Green** has been applied, you can start adding external attendees. They will get a copy of the meeting invitation via e-mail along with all subsequent updates to the Outlook event. Make sure you only add them once the event has been fully built, edited, and approved. Attendees get every subsequent update to the meeting/event invitation in Outlook, no matter how minor. So make sure you have 100% sign off on the original pre-event invitation as it is intended to be the only communication sent via Outlook.

The website version of the event will be an exact mirror of the Outlook event pulled automatically via API that has front-end logic looking specifically for items in the **Green** category that are no more than **7 days** in the future. 

## Document naming convention
COMMITTEE ACRONYM YYYY-MM-DD TITLE OF CONTENTS.pdf

:::warning
No punctuation is allowed except dash (`-`) and underscore (`_`). No exceptions.
:::

Examples:<br />
RTACAC YYYY-MM-DD Safety Subelements Handout<br />
RTATMC YYYY-MM-DD Agenda<br />
RTACART YYYY-MM-DD Legal Actions<br />
RTABoard YYYY-MM-DD Item_5A Project Delivery Status Report<br />
POPTECH YYYY-MM-DD Meeting Minutes<br />
PAGTIPSUB YYYY-MM-DD Presentation_1 Slides That Were Shown

## Public calendars

| Site        |      Assigned Calendars      |
| ------------- | :-----------: | 
| PAG      | PAG-Main, PAG/RTA-Shared |
| RTA      |   RTA-Main, PAG/RTA-Shared    |
| RTA Next |   RTA-Main, PAG/RTA-Shared    |