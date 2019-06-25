# IAD2017.Chat blubbe

## Index

In the following the styles and the behavior of the Blubbe chat are explained and pointed out. This chat was developed as part of a task during the course HFIAD2017.

### [Styleguide](#styleguide)
  - [Font-selection](#font-selection)
  - [Type-system](#type-system)
  - [Colors](#colors)
  - [Grid-system-for-desktop](#grid-system-for-desktop)
  - [Grid-system-for-mobile](#grid-system-for-mobile)

### [Functions and responsive behaviour](#functions-and-responsive-behaviour)

#### [Desktop](#desktop)
  - [Contacts desktop](#contacts-desktop)
  - [Chat desktop](#chat-desktop)
  - [Header desktop](#header-desktop)

#### [Mobile](#mobile)
  - [Contacts mobile](#contacts-mobile)
  - [Chat mobile](#chat-mobile)
  - [Header mobile](#header-mobile)

### [Texting](#texting)

### [Notifications](#notifications)


### [Optical feedback](#optical-feedback)

---

### Styleguide

#### Font selection

![Inter Font](https://i.imgur.com/4rlAEwI.png)

In this work the inter typeface family was used. This choice is based on the following reason: this font has been designed for the best possible readability on display applications.

Link to the font site: [Inter](https://rsms.me/inter/)

#### Type system

The font sizes have been chosen to work on mobile and desktop. The same font size is used on all devices. It is possible to change the viewport on the desktop without changing the typeface. By using a few fonts, the design remains visually consistent.

| Style         | Size Mobile | Size Desktop  |
| ------------- |-------------| --------------|
| h1            | 24px        | 24px          |
| p             | 15px        | 15px          |
| p-small       | 12px        | 12px          |
| counter       | 11px        | 11px          |

#### Colors

![Colors](https://i.imgur.com/qXv80DS.png)

There are four main colors.
* 28978A – dark green, is used as a markup color and shows actions of the user.
* Green gradient - is used in the header.
* E2E2E2 – the gray is used by p-small to display informations.
* 0F0F0F – Font color.

#### Grid system for desktop

The desktop version is based on a 12-column grid. But not all 12 columns are used on the largest possible viewport. Everything over 1400 pixels will be limited. This ensures that the chat retains its functionality even on very large screens.

![Grid desktop](https://imgur.com/xAk9A5m.png)

As soon as the viewport drops below 1400 px, the chat takes up the entire width. As can be seen in the following example.

![Grid under 1400px](https://imgur.com/DTLLWKq.png)

#### Grid system for mobile

On mobile, the grid is based on a 6-column system.

![Mobile grid](https://imgur.com/b3c0JLy.png)

### Functions and Responsive behaviour

#### Desktop
##### Contacts desktop
![Contacts](https://imgur.com/wkJWdB3.png)

1. Contact with unread messages and notification
2. Hover on contact
3. Active Chat highlighted with the markup color

As can be seen in the example, the contacts column has a minimum width of 280px. This prevents unsightly smaller viewports. If the column threatens to fall below 280px, only the window with the current conversation shrinks. Until the chat finally changes to the mobile view.

##### Chat desktop
The chat bubbles have a maximum width, so even on large screens a good readability is achieved. At the same time, the chat has marging left and right, so the bubbles are never too far apart. Once the mobile view is reached, the bubbles take the whole width, so that this does not happen too suddenly, this change is supported by an animation.

##### Header desktop
The chat on desktop has 2 options for the header. Option 1: If the viewport is very large (over 1400px) the chat must have a limited width. Option2: At 1400px the chat will be displayed on the whole viewport.






## Lizenz
Code unter MIT, Assets unter CC BY-SA 4.0 
