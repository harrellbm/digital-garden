#🌿Sapling #😁Strongly-Agree 
* * *
> `Note Planted`: 2024-06-17
> `Last Tended`: `=dateformat(this.file.mtime,"yyyy-MM-dd")` 
 >`Importance`: 90%

***The Big Idea***: 
The idea of digital gardening has really resonated with me. The basic idea that notes and concepts and ideas are things that should be grown over time from just little seeds into fully developed ones is beautiful in its simplicity and connectivity to creation. 

So much of note taking, project management and organization are all about productivity and efficiency as the highest good.  But the idea of tending a garden of thoughts, ideas and knowledge is a method that looks to curiosity, creativity and organic exploration as the goal of the tending. Fruits then naturally emerge from the growing process just like the fruits of an actual garden. 

The basic method of gardening I have found and desire to develop as a practice for myself is rather simple in its concept: 
- Things are stored in flat simple text files using markdown format. 
- Individual notes will start with a set of metadata to help me and other readers understand the notes context. 
- Internal links between notes.
This approach squares nicely with my personal experience of note taking and trying to stay organized as well as my desire for more wholistic [[Pedagogy]].
* * *
## Personal Purpose of My Garden 
The main things I want to accomplish with my garden:
- Have a place to collect and growing ideas. 
- Having a kind of incubator for personal projects or church projects that don’t need official documentation yet. 
- Have a place to collect personal or other interesting stories I can later use in sermons.
- All of the above reason are additionally driven by the reality that life is crazy and I quickly forget good ideas or where I am on a project so being able to rediscover and search for things is important.
## Current State of the Garden 
As I begin to experiment with this method I will be collecting things here as a bit of a process journal to help hammer out a more cohesive system for making the garden accessible for myself and others that may find it on the web. 

### Obsidian Notes and Zotero Library 
The two main tools I have started using for creating and tending my garden are [Obsidian](https://obsidian.md/) and [Zotero](https://www.zotero.org/)

- Obsidian is becoming the core note taking and garden networking platform for me. It hits a few important requirements for me:
	- Saves notes in plain text so they are always accessible and portable. (Something google docs, pdfs and word fail at miserably). If I am going to spend so much time curating my notes I definitely don’t want to lose them for a dumb reason like a failed editor or a locked down file type.
	- Customizable and tinker-able but also decently easy to get started with.
	- Open source and nonproprietary. So many proprietary tools hid gotchas as a way to make money.
- Zotero is becoming more of a resource catalog. I have many physical books as well as a list of books I want to read, and lists of tools and organizations, etc. keeping those in a note or document ends up being a lot of work and hard to find when you need it. Zotero is nice for this as a way to keep resources cataloged in a more orderly way than the full note garden in obsidian. It is also: 
	- Opensource.
	- Libraries are shareable via groups.

 idea I am running with right now for starting a digital garden 

- Zotero for resource capturing. Able to capture webpages, books, etc and tag them for later 
- Omnivore for newsletter and reader following also save it for later 
- Some kind of note system. Need to be easy to add to and searchable. Maybe obsidian 

These are running notes on useful things I have collected around these tools:
	[[Obsidian Note-taking]]
	[[Zotero Library]]

## Organizing a Garden

Think about how the idea of digital gardening could be applied to my library and notes 
### Beginning Note Metadata 
These are pieces of information I will attach to the beginning of each note that helps give clearer context to how I view the ideas and information contained. 
1. **Epistemic Disclosure**:
	Tag to make clear the level of work put into an idea:
	- #🌱Seed an idea that is intriguing but has had very little development. In other words, they are interesting tidbits that I may do more with in the future. 
	- #🥬Sprout an idea that has been developed and thought about, but not put into any kind of final form.
	- #🌿Sapling an idea that is the starts of a final form 
	- #🌳Tree an idea that had matured 
	- #🍋Fruit Essays, poems, projects, or other more polished forms of writing. They are independently useful products of a line of thought or initiative. 
2. **Special Note Types**:
	Tags that identify notes that function for me in special ways:
	- #🌲Evergreen A running note that is continually updated. 
	- #📊Project A note focused on completing a goal or building something. 
	- #📖Story A personal or interesting story I would like to save for personal memory and possible use in a sermon.
	- #📚Definition A note that holds a kind of dictionary style definition of a word or phrase.
	- #✒️Poem A personal or quoted poem.
1. **Note Dates**:
	Important dates to help frame the note’s life cycle:
	- Date a note was planted 
	- Date note was last tended 
4. **Idea Sentiment**: 
	My personal opinion/acceptance of the idea held within a note.
	- #🤢Strongly-Disagree
	- #😟Disagree 
	- #😐Neutral 
	- #🙂Agree
	- #😁Strongly-Agree
1. **Idea Importance**:
	I will use a sliding percentage rating to make clear how important the current note is to me. Something like:
	- **Importance**: 62%
6. **No topic tags!!!** I find them hard to manage and keep track of as well as unnecessarily condensing the content of a note. Instead I will strive to link related topics between notes using internal links only.
### End Note Metadata 
End note that is an invitation to email me about an idea. 

### Example Note Metadata 
This is an example of the current metadata I have composed to start each note. For ease of use I have created an [Obsidian Template](https://help.obsidian.md/Plugins/Templates) to insert this data pre-formatted. Otherwise I would 100% forget to start notes with it or drift with its style over time.

#🌱Seed  #🙂Agree
****
> `Note Planted`: {{date}}
> `Last Tended`: 
 >`Importance`: 10%
 
***The Big Idea***: 
A new interesting idea.

* * *
## Notes on Hosting Digital Garden
- start with setting up quartz first [getting started](https://quartz.jzhao.xyz/)
- then build and preview to make sure everything is working [build and preview](https://quartz.jzhao.xyz/build)
- Then set up a completely empty repo and follow the next step.
- then set up repo to sync with [setup github repo](https://quartz.jzhao.xyz/setting-up-your-GitHub-repository)
- then set up the hosting with github without any fancy stuff just use the test page [hosting](https://quartz.jzhao.xyz/hosting)
- then you can link enveloppe to generate cleaned markdown files
- using [obsidian-enveloppe](https://github.com/Enveloppe/obsidian-enveloppe) for converting dataview to normal markdown
- using [quatrz](https://github.com/jackyzha0/quartz) for static site generation
	- Had issues getting npx to work was able to use `node quartz/bootstrap-cli.mjs` followed by the command instead 
	- very easy to just us `-d` option to specify the envelop repo I cloned back down
- have a separate github repo that saves the raw obsidian markdown files. Use obsidian git plugin on comp to sync with it.
- node quartz/bootstrap-cli.mjs build -d H:\Envelopp\Envelopp-Repo\Enveloppe -v --serve
- Todo: write clearer speck of what I have set up
- Todo: figure out actual hosting flow
- Todo: write down all the settings I have used

## Additional Gardening Ideas

Other interesting approaches:
	[[Note-Taking Methods]]

What would it look like to have a “community garden” with individual “plots” but a general collaboration on digital gardens 

## Articles that Got me thinking about Digital Gardening

[A Brief History & Ethos of the Digital Garden](https://maggieappleton.com/garden-history)

[Networked Thought](https://jzhao.xyz/posts/networked-thought)