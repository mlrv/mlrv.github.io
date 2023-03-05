---
title: Scalable data systems
---

In order to talk about scalability, we need to have a way to describe the _load_ of a system

The load parameters of a system could be things like: _requests / second, writes / reads, active users_, etc.

Once we have a way to describe the load, we can investigate what happens when the load increases.

How is performance affected if we fix the resources of the system and increase a load parameter? A different question might be, given an increase of a load parameter, how much do I need to increase resources to keep the same performance?

Keep in mind that **an architecture that scales well for an application is built around assumptions of which operations will be common or rare, the load parameters**. If the assumptions turn out to be incorrect, the effort is wasted or counter productive.