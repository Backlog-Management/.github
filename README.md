# Milestone 1 - Backlog Manager
## Table of Contents

1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview

### Description

Maintain backlog lists of movies, television shows, and other media types. Can add items from 3rd-party APIs (TMDB, Big Book API...), share lists, receive recommendations, track milestones for completing backlogged content.

### App Evaluation

- **Category:** Entertainment
- **Mobile:** Being on a mobile device means being able to add things to backlog lists in the moment instead of having to wait. It also enables adding upcoming content to lists and receiving availability notifications.
- **Story:** In a world where there are far too many things to watch, read, or experience and more coming each day, one app looks to help you stay on top of the content you're most interested in by keeping track of it all.
- **Market:** The market is potentially quite wide, since it's not uncommon for people of all kinds to be interested in a piece of media while also not necessarily having the ability to consume it immediately. Being able to keep lists of things to watch/read/etc in time is broadly applicable.
- **Habit:** Social features (sharing lists, receiving or sharing recommendations to other users' lists, commenting on lists) as well as the inherent nature of the app as something that is used to keep track of ideas/suggestions that come up in the moment should keep users checking in. There would also be cyclical milestones (watch/read/etc X items, watch/read/etc X (genre) items...) to encourage engaging with the app to check things off of lists and add new ones.
- **Scope:** V1 would just encompass adding a movie from TMDB to a list and storing it. V2 would expand functionality to TV shows and include episode progress information per show. V3 would expand to books via Big Book API. V4 would incorporate milestones (maybe just weekly) for consuming pieces of media, potentially incorporating genre-based milestones if the user has high enough concentrations in a given genre. V5 could include some social functionality (adding items to others' lists as suggestions).

## Product Spec

### 1. User Features (Required and Optional)

**Required Features**

1. Create backlog lists limited to a given type of media
2. Search APIs for items.
3. Add items from APIs to user-created/locally stored backlog lists.
4. Users can create accounts
5. Users can check items off of backlog lists to indicate that they've been finished  

**Optional Features**

1. Rate recommendations
2. Comment on other users' lists
3. Multiple lists per media type
4. View other users' lists
5. Add recommendations to other users' lists
6. Track cyclical (weekly/monthly/yearly) milestones for checking items off of backlog lists.

### 2. Screen Archetypes

- Login
    - User can login
- Registration
    - User can register a new account
- Creation
    - Create a new backlog list, specifying a name and media type
    - Add an item to a personal list by searching an API and selecting from the results
    - Add a recommendation to a user's list from an API
    - Add comments to other users' lists
- Stream
    - View all backlog lists
    - View one backlog list.
    - View search results from an API while adding new items
    - Long-press an item to mark it as consumed
    - Double-tap a recommendation to 'Like' it
    - View milestones for checking off items
- Detail
    - Get more information about a backlog item (overview, creator(s), cast, episode progress, etc)
    - Get more information about a search result
        - Add a search result to a list

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Lists
* Add
* Profile
* Friends
* Milestones

**Flow Navigation** (Screen to Screen)

- Login
  - -> Lists
- Registration
  - -> Create New Account
- Stream (User Lists)
    - -> Stream (Individual list)
    - -> Detail (Single milestone)
- Stream (Individual List)
    - -> Creation (new list item)
    - -> Detail (existing list item)
- Stream (Search)
    - -> Detail (search result details)
- Stream (Milestones)
    - -> Possibly none
- Creation (New list)
    - -> Stream (The new list)
- Creation (Add comments)
    - None
- Creation (Add recommendation)
    - -> Stream (The list that received the recc)
- Detail (Backlog item)
    - -> Back to the list the item came from
- Detail (Search result)
    - None

## Wireframes

I just made Figma wireframes:

<img src="https://i.imgur.com/PNydn7H.png" width=600>
<img src="https://i.imgur.com/R6vo1df.png" width=600>
<img src="https://i.imgur.com/kSrFH5M.png" width=600>


<br>

<br>

### [BONUS] Digital Wireframes & Mockups

<img src="https://i.imgur.com/PNydn7H.png" width=600>
<img src="https://i.imgur.com/R6vo1df.png" width=600>
<img src="https://i.imgur.com/kSrFH5M.png" width=600>

### [BONUS] Interactive Prototype

<br>

# Milestone 2 - Build Sprint 1 (Unit 8)

## GitHub Project board

[Add screenshot of your Project Board with three milestones visible in
this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Issue cards

- [Add screenshot of your Project Board with the issues that you've been working on for this unit's milestone] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>
- [Add screenshot of your Project Board with the issues that you're working on in the **NEXT sprint**. It should include issues for next unit with assigned owners.] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Issues worked on this sprint

- List the issues you completed this sprint
- [Add giphy that shows current build progress for Milestone 2. Note: We will be looking for progression of work between Milestone 2 and 3. Make sure your giphys are not duplicated and clearly show the change from Sprint 1 to 2.]

<br>

# Milestone 3 - Build Sprint 2 (Unit 9)

## GitHub Project board

[Add screenshot of your Project Board with the updated status of issues for Milestone 3. Note that these should include the updated issues you worked on for this sprint and not be a duplicate of Milestone 2 Project board.] <img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## Completed user stories

- List the completed user stories from this unit
- List any pending user stories / any user stories you decided to cut
from the original requirements

[Add video/gif of your current application that shows build progress]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

## App Demo Video

- Embed the YouTube/Vimeo link of your Completed Demo Day prep video
