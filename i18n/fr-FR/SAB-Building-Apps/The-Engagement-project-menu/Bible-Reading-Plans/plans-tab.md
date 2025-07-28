---
title: The Plans tab (for adding and modifying plans)
sidebar_position: 1
slug: /plans-tab
---

# The Plans tab (for adding and modifying plans) {#23980858a4b680edb76bf060f67a05b0}

You can create your own reading plans, or add ones that someone else has created.

On the Plans tab, use the **Add Plan From Gallery…** button to add one of the plans that come with SAB.

Use the **Add Plan…** button to add a plan you or someone else has created.

Plans are defined in text files with the following format:

**\id** PLAN1

**\title** Read through the Gospels

**\descr** Read the Gospels of Matthew and Mark, learning about Jesus, what he did, what he said and why he came.

**\img** plan1.jpg

**\day** 1

**\ref** MAT 1:1-17

**\day** 2

**\ref** MAT 1:18-25

**\ref** MRK 1:1-8

**\day** 3

**\ref** MAT 2

The standard format markers to use are as follows:

| **\id**      | Unique identifier for the plan (for internal use)                                                                                                                                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **\title**   | Title of the plan (seen by the user)                                                                                                                                                                                           |
| **\descr**   | Description of the plan (seen by the user)                                                                                                                                                                                     |
| **\img**     | Image                                                                                                                                                                                                                                             |
| **\day**     | Day in the plan (\day 1, \day 2, \day 3, etc.)                                                                                                                                                                 |
| **\ref**     | Scripture reference to read.<br/>There can be one or more \ref lines for each day. References are defined using the Paratext book codes (GEN, EXO, LEV, etc.). |
| **\heading** | Heading to include before one or more references for a day.                                                                                                                                                                       |

If you need to translate a plan for different user interface languages, you can do this by adding the language code in square brackets after the standard format marker:

**\id** PLAN1

**\title [en]** Read through the Gospels

**\title [fr]** Lire les évangiles

**\descr [en]** Read the Gospels of Matthew and Mark, learning about Jesus, what he did, what he said and why he came.

**\descr [fr]** Lire les évangiles de Matthieu et de Marc, et apprendre à connaître Jésus, ce qu'il a fait, ce qu'il a dit et pourquoi il est venu.

**\day** 1

**\ref** MAT 1:1-17

Double-click the plan in the table to edit the name, description or image. Below are some screenshots of the Plans feature in action.

![](/notion_imgs/plans-tab.23980858-a4b6-80a5-ab66-f9deaaa31cb6.png)

![](/notion_imgs/plans-tab.23980858-a4b6-8086-ab1b-c140410bf597.png)

![](/notion_imgs/plans-tab.23980858-a4b6-8010-8ec1-dca2b90e56a2.png)

![](/notion_imgs/plans-tab.23980858-a4b6-8099-9fd7-d0b3ec485abe.png)

:::tip

_When naming the plan, don’t put the number of days in the plan name as SAB will automatically put that in the subtitle. Don’t forgot to use the Translations button to add titles and descriptions in all your interface languages if they do not already exist in the plan file._

:::



