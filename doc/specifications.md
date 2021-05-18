# Specifications for DevPack_Manager_Client

- PbD: Probable to be Deleted
- uC: under Consideration

## 《Requirements》

### General

- [ ] Launching Notifications reliably
- [ ] Making Groups by Users(Members)
  - Positions, Departments, Sub-orgs, and Registered Projects are default Groups
    - Sub-orgs are each of Affiliated, Middle, Member, and Registered Orgs.
- [ ] (uC)As group of Massages, the App has Section.
  - Section is constructs by Area and Room.
  - One or more Rooms/Areas are belong to some Org/Area, and one or more Rooms are belong to some Area.
  - "Independent" Area is Default, for "Direct" Massages
  - Each of Group makes Area or Room, in Default.
  - The system of Section: Org - (Area)\* - Room? - Thread
- [ ] Always showing Presence Information(Status)
- [ ] Request for to Registration, and Management Projects

### Massages

- [ ] Mention by using Groups, that can Set operation
- [ ] All Massages are Hidden from Outsiders
  - The Author of the Message that Originated the Thread Chooses the Scope of Publication, like the Privacy Level on Mastodon Toots
    - The Range of Scope of Publication that can be specified for a Section/Thread in a Section is limited to the Range specified for the Section.
    - (uC)Scopes of Publication are bellow
      - "Public" Scope is can be seen by All Members of the Organization(All in the Orgs in Common,that includes all Sub-orgs of DevPack)
      - "UnderOrg" Scope is can be seen by All Members of the Organization(Some Orgs that includes all Sub-orgs of each Orgs that Specified by Author of the Message that Originated the Thread)
      - "ThisOrg" Scope is can be seen by All Members of the Organization(only Orgs that Specified by Author of the Message that Originated the Thread, excludes Sub-orgs)
      - (PbD) "Unlisted" Scope is can be seen by All Members of the Organization, but not notified to out of talkers and Mentionee of the Thread, and unlisted to Timeline(really going to make a Timeline?)
    - "Groups" Scope allows to see to only Groups Members that Specified by Author of the Message that Originated the Thread
    - "Direct" Scope is direct messaging among independent users for Secret Information such as Private Information
- [ ] Make Sharing of logs Ease
  - Copying Message Links
- [ ] Each Message and its Replies make a Thread
- [ ] Giving Tags to Messages ( Alternative of Pin Feature on Discord )
- [ ] Basic Text Decoration
  - Markdown(with Source Code & Math Expr) to Text
- [ ] Read Notification Information(Who(and which Positions, Departments, Projects) are already read, with number what already read)
- [ ] Quotation and Cancellation of Messages
- [ ] Giving Basic Reactions to Messages
- [ ] Sending Message with Images, and Previewing Them.

### Documents/Proposals

- [ ] Writing, reading, and managing Documents, including Regulations
- [ ] Proposal and Assignment of Agendas

### Task/Schedule

- [ ] Making To Do Task List, that can nesting
  - Structured Graph of Dependency Relationship among Tasks
- [ ] Schedule Calendar & Notifier
  - Linked to To Do Task List and Messages

### Authentication

- [ ] Authentication of Discord account, and signing up by using Discord account
- [ ] Authentication of GitHub, Twitter and etc. accounts
