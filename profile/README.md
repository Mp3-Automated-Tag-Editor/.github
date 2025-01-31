# Task List

If you'd like to contribute, feel free to reach us via email!

### Version 2.0 Release (As of 31.01.2025)

- Complete Edit page with session suggestions + Session Edit - Group Save or Individual Save - Custom Tag to tell which songs has been edited (Needs to contain Session info), along with highlight (Show Session Date first and foremost, with the original as well, slightly change the colour as well)
    - Fix Year issue
    - Fix edit on normal edit (Not session)
    - Review All Files - Trigger each one after the other
    - In file Edit - Save Changes & Apply Changes (At the top)
    - All files will have a yellow tint (Not saved). On save - Green tint
    - Load or Save Edit session - Save changes into edit session
    - Also on Save, add custom tag with session name. And add percentrage modified = percentage accuracy. Therefore 0's weren't scraped by the scraper.
- Music Player
    - Start work on Music Player - UI - Mainly MusiCat and Infinitunes
    - Study Spotify/YT Music and Media Player + MusiCat and Infinitunes. Then Confirm Design via Notion ss
- Backend - App
    - Race Condition? More than one thread are trying to do the operation of the
- Backend - Server
    - Deepseek API integration
    - Ollama API Integration
    - support to add Plugins (Add python code, validate that it passes data as expected), can be used along with other classifiers (To be developed)
- General
    - Settings - Move/Duplicate the current Dev settings to the settings panel in the Scraper Settings + Add the Cache setting + Add Status Checks in sidebar settings + Scrape Settings Page + From Cache Toggle
    - Setup Landing Page & Docs as soon as all this is completed
    - Code CleanUp + Optimizations
    - About Us Revamp

### Version 3.0 Release (Planned for 2026)

- Try making the FastAPI into a .exe as well, and see how that goes [Later]
- Phone App & Streaming - Down the line (Research it up tho) -  Start researching up the streaming process (From the bottom up)
- Long term - Rust wrapper for Yt-DLP
- Stats - Base it on MusiCat

---

### MP3-GUI
* Dashboard
	- [ ] - [#6](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/6) (Roadmap v1.x) - Add a recently viewed button
	- [x] - [#7](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/7) (Roadmap v1.x) - Add a stats view button

* Start
	- [ ] - [#8](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/8) (Roadmap v1.x) - Check if network is down, if server is connected, current latency and network speed (this to be done during CLI init, keep these as status calls on side bar settings)
 	- [x] - [#10](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/10) (Roadmap v1.x) - Fix settings config for start process
	- [x] - [#9](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/9) (Roadmap v1.x) - CLI Process workflow - plan and implement + animation + better colours
	- [ ] - [#11](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/11) (Roadmap v1.x) - Saving previous session instances (display as a card below start scrape) + logging of data handled - plan a workflow for the same
* Edit
 	- [ ] - [#16](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/16) (Roadmap v1.x) - Hide Comments, Track Number and Disc Number on Startup 
	- [x] - [Discuss] option to add picture (figure out how that is supposed to work.. is storage needed? etc)

* Download
	- [x] - [#12](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/12) (Roadmap v1.x) - Research up on download avenues + API for the same (Various download avenues)

* Music Playstation
	- [ ] - [Discuss] Research up on Designs for Music Players

* About Us
	- [ ] - [Discuss] Simple Format, look for inspirations

* Stats
	- [ ] - [Discuss] Plan on creating API to tract data of Songs scraped, and to store them on user side.

* Settings
	- [ ] - [#8](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/8) (Roadmap v1.x) - display if network is down, if server is connected, current latency and network speed
	- [x] - [#8](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/8) (Roadmap v1.x) - Figure out other parameters to be checked in settings
 	- [ ] - [Discuss] - Option to add custom plugins and classifiers? Let users create custom python scripts/executables that can be added and used within the app as 3rd party plugins.

* General
	- [ ] - [#2](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/2) (Roadmap v1.x) - Fix Titlebar and ScrollBar interference
	- [ ] - [Discuss] Scrollbar Colour? Experiment
	- [ ] - [Discuss] Cleaner TitleBar Implmentation
	- [ ] - [#13](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/13) (Roadmap v1.x) - Documentation - clean it up
	- [ ] - [Discuss] Auth plan - answer why we need auth, what data is to be collected, what is to be displayed, at which stages do we need login (in app, or just login page?, how to monitor data?)
 	- [ ] - [Discuss] Figure out a Subscription Plan / Business Model Plan
	- [x] - [#15](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/15) (Roadmap v1.x) - Logos for app - change
	- [ ] - [#14](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/14) (Roadmap v1.x) - Server Side Testing - implement code coverage workflow for GitHub - research the same
	- [ ] - [#3](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Gui/issues/3) (Roadmap v1.x) - Server Side Error Handling - map out potential issues + handle them

### Mp3-CLI
* General
	- [ ] - [#1](https://github.com/Mp3-Automated-Tag-Editor/Automated-Mp3-Cli/issues/1) - Documentation - clean it up

### MP3-API
* API
	- [ ] - Logging for Backend Application
	- [ ] - Dockerization of Application

### Mp3 Org
* General
	- [ ] - [Discuss] Figure out Download Site, Landing Page, etc - Use Spring baeldung Website and Rehaan website for ideas, ShadCN for implementation
	- [ ] - [Discuss] New Backend Architecture - Design, Document, Implement
	- [ ] - [Discuss] Deployment Plan for Azure
	- [ ] - [Discuss] Design Process Flow Diagram for Backend Architecture, Frontend Process Flow, Overall Architecture, Overall Process Flow Diagram for CLI and GUI
	- [ ] - [Discuss] Give Roadmap Tags for all these to-do's
 	- [ ] - [Discuss] Stream functionality - How to go about implementing this

### Mp3 Flutter App
* General
	- [ ] - Find a good base app to fork and continue development for the stream feature.
