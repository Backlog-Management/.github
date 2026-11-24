## New App Ideas
1. Mobile YAML Editor
    - Edit existing YAML files or generate new ones (from a blank file or a template). Share finished YAML files with friends, back them up to cloud storage, or upload them directly to specified endpoints (such as a personal server)
2. Backlog Manager
    - Maintain backlog lists of movies, television shows, and other media types. Can add items from 3rd-party APIs (TMDB, Big Book API...), share lists, receive recommendations, track milestones for completing backlogged content.
3. Kitchen Tool
    - Common kitchen unit conversions (temperature, volume, weight), a virtual 'pantry' of currently held ingredients, and a recipe book that parses user-added recipes so that it can be filtered according to pantry contents, desired ingredients, or other needs.
4. Enhanced Pomodoro Timer
    - Task-based time tracking with integrated Pomodoro (repeating cycles of 25 minutes spent focusing/5 minutes not focusing) functionality for a given task.
5. Media Journal
    - Take and store notes about media while consuming it. Can add a show/movie/etc from an API, then attach notes to characters, episodes, et cetera. Notes can be shared and time/pagestamped.
6. Playlist Sync
    - Sync playlists between music services, add new songs to multiple playlists at once via YouTube/Spotify URLs, share playlists.

## Top 3 Ideas
1. Backlog Manager
2. Mobile YAML Editor
3. Media Journal

## Evaluation & Categorization
1. Backlog Manager
    - **Description:** Maintain backlog lists of movies, television shows, and other media types. Can add items from 3rd-party APIs (TMDB, Big Book API...), share lists, receive recommendations, track milestones for completing backlogged content.
    - **Category:** Entertainment
    - **Mobile:** Being on a mobile device means being able to add things to backlog lists in the moment instead of having to wait. It also enables adding upcoming content to lists and receiving availability notifications.
    - **Story:** In a world where there are far too many things to watch, read, or experience and more coming each day, one app looks to help you stay on top of the content you're most interested in by keeping track of it all.
    - **Market:** The market is potentially quite wide, since it's not uncommon for people of all kinds to be interested in a piece of media while also not necessarily having the ability to consume it immediately. Being able to keep lists of things to watch/read/etc in time is broadly applicable.
    - **Habit:** Social features (sharing lists, receiving or sharing recommendations to other users' lists, commenting on lists) as well as the inherent nature of the app as something that is used to keep track of ideas/suggestions that come up in the moment should keep users checking in. There would also be cyclical milestones (watch/read/etc X items, watch/read/etc X (genre) items...) to encourage engaging with the app to check things off of lists and add new ones.
    - **Scope:** V1 would just encompass adding an entity from an API to a list and storing it. V2 would incorporate milestones (maybe just weekly) for consuming pieces of media, potentially incorporating genre-based milestones if the user has high enough concentrations in a given genre. V3 could include some social functionality (adding items to others' lists as suggestions).

2. Mobile YAML Editor
    - **Description:** Edit existing YAML files or generate new ones (from a blank file or a template). Share finished YAML files with friends, back them up to cloud storage, or upload them directly to specified endpoints (such as a personal server)
    - **Category:** Productivity
    - **Mobile:** This is more of a convenience tool for someone who might want to work with YAML files on a mobile device than an app that leverages mobile device functions. 
    - **Story:** YAML is a widely used data serialization solution, particularly in the increasingly accessible self-hosting hobby. Being able to create YAML files for services or edit existing ones via dropdowns, radio buttons, and other mobile-friendly inputs would make handling them without a full keyboard more convenient-- perfect for getting a cool new service ready to spin up while out and about.
    - **Market:** The market is fairly specific, likely limited to folks who are at least mildly tech-inclined.
    - **Habit:** It could be possible to upload YAML templates for others to use, rate, comment on, et cetera to increase habituation.
    - **Scope:** V1 would be limited to parsing a pre-existing, use-specific YAML template, editing, and saving it. V2 would bring in the ability to create a new YAML file by specifying fields and their values. V3 could incorporate Docker-specific templating for blank YAML files so that users could build Docker Compose files via pre-filled dropdowns. V4 could incorporate uploading to cloud or personal storage.

3. Media Journal
    - **Description:** Take and store notes about media while consuming it. Can add a show/movie/etc from an API, then attach notes to characters, episodes, et cetera. Notes can be shared and time/pagestamped.
    - **Category:** Entertainment
    - **Mobile:** Mobile functionality is essential because the ideal use case for this app is taking notes on a piece of media in the middle of consuming it.
    - **Story:** Enables organizing one's thoughts about a piece of media in the moment in a granular fashion.
    - **Market:** People who like writing reviews on sites like Letterboxd, or who might want to organize their thoughts for essays (video or otherwise) would probably get value out of being able to collect notes about said media in an organized manner.
    - **Habit:** Social functionality seems like the most likely way to incorporate habit-forming.
    - **Scope:** V1 is grabbing a movie's metadata and being able to attach notes to it/its cast. V2 includes television shows, which would be broken down into episodes that can have individual notes. V3 gives each TV episode its own cast and allows adding notes per cast entity, per episode. 

## Final Idea: Backlog Manager
