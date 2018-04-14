# Database Connection Requirements
### Tables and Fields
1. Org (Id, name,createdate,active,orgmgr (username), textfield)
1. Member (Id, name, username (email addr), pw (hashed),  
1. Unit (Id, title,name,UnitMgr (username),  
1. UnitMembers (link, unitid, memberid)
1. Meeting (id unitId date time format location)  
1. Question (id, meetingid,qtext,opentime, closetime, status)
1. Vote (id, questionid, memberid, vote, timestamp, valid,

### Modules
1. Admin- crud Orgs
2. OrgMgt- crud org's units, members
3. UnitMgt- crud member-unit links, unit's meetings.
4. MeetingMgt- 
    1. assemble agenda (set of questions), 
    2. crud non-agenda questions, 
    3. open/close questions for voting, 
    4. report all meeting action.  
