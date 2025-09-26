---
tags:
  - documentation
---
# About Community Plugins

This worldbuilding vaults includes a few community-developed plugins to improve upon Obsidian's base functionality, and to add useful quality of life features.

Each community plugin included with this vault are listed below. Instructions on what they do and how to use them are also included. Finally, each plugin's repo and  [software license](https://en.wikipedia.org/wiki/Software_license) are documented.

Keep in mind that plugins are *software*. If you are experiencing bugs in Obsidian while editing, it may be due to a community plugin. I would recommend at least skimming Obsidian's documentation on [community plugins](https://help.obsidian.md/Extending+Obsidian/Community+plugins) for information on how to manage third-party plugins.

# Advanced Tables

This plugin makes it easier to edit tables within Obsidian.md. It is difficult to edit tables using Markdown formatting, even with Obsidian.md's base improvements to the process. This plugin adds a few features that make editing these tables easier.

[Advanced Tables by Tgrosinger](https://github.com/tgrosinger/advanced-tables-obsidian) *GPL 3.0*

# Admonition

This plugin expands the callout functionality within Obsidian.md. Callouts are text within a highlighted box, meant to offer alerts or information in an easily distinguished format. Here's an example of a default callout:

> [!NOTE] Default callout 
> Information within default callout

Obsidian offers several default callout options, along with a way to edit their appearances. Admonition makes it easier to create and edit callouts. These are very useful for running a TTRPG campaign, and the following have been created for this template vault:

> [!narrate]
> Narrate
> 

> [!loot]
> Loot

> [!lore]
> Lore

> [!danger] Danger!
> Danger!

You can create more within the Admonitions plugin menu. Ctrl+Shift+O has been set as the hotkey for inserting callouts within this vault.

[Admonitions by javalent](https://github.com/javalent/admonitions) *MIT License*

# Aprils Automatic Timelines

April's Automatic Timelines allow you to create timelines based off of events you've created within your notes. While complicated to begin using, it can be *extraordinarily helpful* for organizing the history of your world, especially for campaign events in a TTRPG campaign.

I strongly, strongly recommend reading the documentation for this plugin. You can find it within the repo linked below.

[Aprils Automatic Timelines by April](https://github.com/April-Gras/obsidian-auto-timelines) *MIT License*

# Calendarium

Calendarium allows you to create, import, and manage a fantasy calendar for your world. It manages lunar cycles, seasons, months, intercalary days, and much more. 

There's a lot to this plugin. If you're a stickler for fantasy dates and managing the calendar, I recommend reading the [documentation available here](https://plugins.javalent.com/calendarium) to create your own calendar. The [[Event]] template is already pre-filled with necessary metadata fields for you to set dates and event categories in, once your calendar has been created.

[Calendarium by javalent](https://github.com/javalent/calendarium) *MIT License*

# Folder Notes

By default, folders are *just folders* within Obsidian.md. The Folder Notes plugin adds support for "folder notes". These will appear as folders with linked text in the sidebar. You can click on the linked text to be brought to the folder note.

![[folder-notes-example.png]]

*Above: Folder note present within the "Templates" folder, but not the "Categories" folder.*

This is used within the template vault to allow the creation of "category pages", such as the [[Characters]] folder note. You can edit and tailor these folder notes to your individual preferences. There is also a template for folder notes that can be found [here](Folder%20Note%20Template).

By default, you can open folder notes via pressing Ctrl+Click. You can adjust this behavior within the folder note settings.

Folder notes can be created in the following ways:

- Creating a note with the same name as the folder.
- Pressing Ctrl+Click on a folder without a folder note.
- Right-clicking on a folder, navigating to  `Folder Note Commands`, and selecting the option to create a folder note.

If you want to manage the folder note settings further, the official documentation can be found [here](https://lostpaul.github.io/obsidian-folder-notes/).

[Obsidian Folder Notes by LostPaul](https://github.com/LostPaul/obsidian-folder-notes) *AGPL 3.0*

# Quick Tagger

Quick Tagger is a plugin included for a very simple reason- it adds the ability to edit tags on multiple notes at once by selecting them, and then right-clicking them within the Files pane.

![[quick-tagger-example.png]]

If you forget to tag a large number of notes, or think of a tag you want to add in later, this can help you in doing so.

[Obsidian Quick Tagger by Gorkycreator](https://github.com/Gorkycreator/obsidian-quick-tagger) *MIT License*

# Recent Files

The Recent Files plugin adds a sidebar pane that displays recently-accessed notes. This is helpful for navigating between notes, especially when creating new notes during editing of an existing one.

[Recent Files for Obsidian by TGrosinger](https://github.com/tgrosinger/recent-files-obsidian) *GPL 3.0*

# Short Internal Links to Headings

Obsidian supports linking to specific headers in a note, if you only want to show a particular section. However, the default display of these links will include the full note title, and header text. This can be a little cumbersome.

This plugin shortens the displayed text to just the header, which helps keep your notes looking neat. You can still include the title of a note using [standard markdown link formatting](https://help.obsidian.md/Linking+notes+and+files/Internal+links#Supported+formats+for+internal+links).

[Short Internal Links to Headings by Scott Willmoore](https://github.com/scottwillmoore/obsidian-short-internal-links-to-headings) *MIT License*

# Style Settings

The Style Settings plugin enables CSS snippets to be used within Obsidian. If you are not a fan of the ITS theme, or want to use a different theme, you can use this alongside the [[03- Community Plugins#ITS Callout Snippet]] to preserve functionality of the callouts present in the templates of this vault (follow the linked heading for more information).

[Obsidian Style Settings by MGMeyer](https://github.com/mgmeyers/obsidian-style-settings) *GPL 3.0*

# Tabout

The Tabout plugin is as simple as it sounds- it allows you to tab out of "markup", or basically past symbols like \*, \** , and such. If you are using a lot of markdown formatting like **bolding**, *italics*, and the like, this can help keep your writing going without having to take your hand off of the keyboard, or using arrow keys and Home/End keys.

Just press tab after you are done with formatting, and the text cursor will immediately jump out of the formatting. If you require further uses of tabout than have already been created, you can add them within the plugin settings.

[Tabout by phibr0](https://github.com/phibr0/obsidian-tabout) *AGPL 3.0*

# Tag Wrangler

The Tag Wrangler plugin allows a number of powerful options related to vault management. One of the bigger quality of life features it offers is the ability to mass edit tags, allowing you to rename, and/or merge tags as you see fit. 

Just right-click on a tag, and select the Rename option.

[Tag Wrangler by PJ Eby](https://github.com/pjeby/tag-wrangler) *No license provided*

# Waypoint

The Waypoint plugin is used within folder notes, and allows for dynamic generation and updating of the table of contents for that folder. In other words, it creates a list for every note within the folder, and keeps that list up to date.

The generated table of contents will be formatted in markdown, so it still works even if the plugin breaks or is uninstalled. Please bear in mind that if either happen, the table of contents will no longer be updated automatically.

The [[Main Category Folder Note]] and [[Subcategory Folder Note]] templates come with Waypoint almost ready to go.

![[waypoint-example.png]]
![[landmark-example.png]]
When inserting these templates, delete the space between the latter two `%` signs, and it will begin working (due to how the plugin works, Waypoint cannot be setup in full beforehand).


[Waypoint by IdreesInc](https://github.com/IdreesInc/Waypoint) *MPL 2.0*

# ITS Theme

The ITS theme is used for this vault, for a few reasons.

1. First and foremost, the theme supports a dizzying number of [custom callouts](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Callouts/Callout+-+Infoboxes). There's a truly dizzying number of creative ways these can be utilized, including support of statblocks. But the most important one for this vault are the infobox callouts, as shown below.
   ![[infobox-callout-its-pre-example.png|500]]
   The above may look like nonsense text, but will be rendered as shown below, providing a useful way to quickly skim information on a character:
   ![[infobox-callout-its-example.png|500]]
2. The ITS theme is aesthetically pleasing, and works well in both dark and light mode. The light mode support is especially handy when exporting a note for your players/reader, or when printing it out.
3. The ITS theme supports Obsidian Publish ([see here for more details](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Publish+Theme).) This means that if you wish to host a website for your worldbuilding, your readers/players will be able to view your articles with the same theming that you are writing them in.

While not technically a plugin, the ITS theme does so much that I've included it in this vault.

[Obsidian ITS theme by SIRvb](https://github.com/SlRvb/Obsidian--ITS-Theme) *GPL 2.0*

## ITS Callout Snippet

If you want the ITS theme callout functionality without using the ITS theme, you can have it via the Style Settings plugin. Just switch themes, and then enable the `its-callouts` snippet within the Appearance tab of the settings menu of Obsidian.

[ITS theme callout documentation](https://publish.obsidian.md/slrvb-docs/ITS+Theme/Callout+Adjustments)