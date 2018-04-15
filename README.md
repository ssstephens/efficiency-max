# Efficiency-max
This project is designed to maximize the effficiency of organizations that use committees or workgroups to get work done without physical meetings. It is useful for handling votes during conference calls and in-person meetings if every member has a device with interent access. 

### The hierarchical model:

(1) *organizations* (org) consisting of 

(2) *members.* Each org has 

(3) *committees* (unit), a set of member ids.  Each committee has 

(4) *meetings* (event), and each meeting has 

(5) *questions* (question) that are put to vote. The finest level of detail kept is 

(6) each  member's *vote* on a specified question. 

### User Roles

0. Master admin- create/delete orgs

1. Org admin- crud committee-member links and profiles, meetings, questions, and vote open/close 

2. Member- login, access app for voting, vote while question is open. Enter comments. Access reports. 

### Use Case Summary

0. Creating an Organization (master admin) 

0.1 Maintaining membership, add/delete/edit.

1. Creating Committees

1.1 Attaching members to committees

2.  Creating Meetings

2.1 scheduling meetings

2.2 Preparing agenda

2.3 notifying members

3.0 Conducting meetings

3.1 Display agenda 

3.2 Open a question for voting

3.3 Members record votes (member)

3.4 Display votes near real-time

3.5 Close votes and record results

4. Post-meeting report 
