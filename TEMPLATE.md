Feel free to copy/paste everything below the marker into your own markdown file and complete as much as you can. It would be great if you could keep a link to the TURTLES repository so others can read more about this checklisk, but keeping the link is not required. 

----

## This project is now archived. Here is the [TURTLES checklist :turtle:](https://github.com/jamesread/TURTLES) 

A "TURTLES" checklist serves as a helpful reminder for those finding the project later, as a reminder for why it was archived. You can read more about [the TURTLES checklist](https://github.com/jamesread/TURTLES) :turtle: 

**T — Technologists**:  Did enough people contribute to maintaining this project? Developers, Architects, Security, Operations?
- **Developers:** Alice and Bob were the main developers, and several other people from Ops contributed some patches. 
- **Testers**: Charles and the finance testing team owned the integration and acceptance testing. 
- **Interesting?:** This was a "need to have" project in 2013, but since then Alice and Bob have moved on to other projects and this project is now badly maintained. 
- **More/Less?:** 2 key developers was enogh to keep up with the issues list, but more testers would have been nice. 

**U — Users**: Did this project have enough active users?
- **Who?:** This was only used internally, by everyone who had admin access to our production website. 
- **How many?:** Approx 150 people
- **Advertisement:** No use to anyone outside the company, didn't need to advertise it to anyone

**R — Requirements**: Did this project still doing what we set out for it to do?
- **Original requirements met?:** Yep, it acted as an admin tool that we needed for our production website. 
- **Scope creep?:** Yes - we never thought we'd have to add user management to the admin tool, which had a pretty big impact on the project. 
- **Roadmap:** News management (issue #8123) and media management (#9533) were two major roadmap items that we never had time for. 

**T — Technology**: Are there any unsustainable technologies behind this project?
- **Sustainability:** This project was written in Visual Basic 6, which is old, unmaintained, and doens't work different platforms. The project would need so many updates to get to VB.net that porting isn't realistic
- **Changes?:** Nowadays, most admin tools like this a web based, not desktop based. 
- **Dependencies frozen?:** Included current version of major dependencies - vb6.dll in the lib/ folder. 
- **Outdated dependencies?:** This project uses libFoo which is well maintained still, but libBar looks abandoned now. 
- **Building & Toolchain**: See HOW_TO_COMPILE.md

**L — Learning**: Is anything being learned by maintaining this project?
- **Developers:** Nothing too much, the UI was frequently described as "easy to use". 
- **Operators:** It was a real pain to release updates, as they needed to be downloaded by each user from a central fileserver.
- **Project managers:** Often underestimated how long it would take to test a release. 
- **Budget/Finance:** The project wasn't big enough to need it's own budget.
- **Business:** Althouh the app was business critical, it wasn't big enough to be seen by the exec leadership of the company. 

**E — Ecosystem**: Are there an alternative to writing this project?
- **Alternative approach?:** Should have been a webapp.
- **Alternative tech/Open Source?**: Realistically, we should have switched the main website to Wordpress, then we would not have had to write this admin tool in the first place. 
- **Duplication?**: No other tool could do what this tool did!

**S — Salvage**: Can anything useful be salvaged from this project?
- **Reuseable code?**: It's a very small project, nothing reusable it seems.
- **Reusable non-tech?**: N/A
- **Forkable?**: Not really, it's very tied into our production website and specifically built as an admin tool for internal use. 
