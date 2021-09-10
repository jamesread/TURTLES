Feel free to copy/paste everything below the marker into your own markdown file and complete as much as you can. It would be great if you could keep a link to the TURTLES repository so others can read more about this checklisk, but keeping the link is not required. 

----

## This project is now archived. Here is the [TURTLES checklist :turtle:](https://github.com/jamesread/TURTLES) 

A "TURTLE" checklist serves as a helpful reminder for those finding the project later, as a reminder for why it was archived. You can read more about [the TURTLES checklist](https://github.com/jamesread/TURTLES) :turtle: 

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
- **Sustainability:** Pidgin seems reasonably well maintained, with packages for all modern distros still, but perhaps has less users now-a-days. It seems g++ compiles with several warnings now.
- **Changes?:** Limited by the pidgin API
- **Dependencies frozen?:** Doesn't seem much point - see Pidgin.
- **Outdated dependencies?:** It seems Pidgin relies on some older GTK versions, but nothing major.

**L — Learning**: Is anything being learned by maintaining this project?
- **Developers:** Nothing too much, as the base code was copied from another plugin (with permission)
- **Operators:** N/A
- **Project managers:** N/A
- **Budget/Finance:** N/A
- **Business:** N/A

**E — Ecosystem**: Are there an alternative to writing this project?
- **Alternative approach?:** Nope, this project is tied to Pidgin.
- **Alternative tech/Open Source?**: N/A
- **Duplication?**: No other plugins exist that do this as far as I know.

**S — Salvage**: Can anything useful be salvaged from this project?
- **Reuseable code?**: It's a very small project, nothing reusable it seems.
- **Reusable non-tech?**: N/A
- **Forkable?**: I borrowed code from the leftify-tabs plugin, if you find something here useful, please go for it :-) 
