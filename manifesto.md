# "Docs as Code" Manifesto

The "Docs as Code" Manifesto, just like the [Agile Manifesto](https://agilemanifesto.org/), has been carefully worded to capture the essence of "Docs as Code" methodology in minimum words. The eight principles reads as below:

* `Humans first, machines second`
* `Keep track of changes - like everyone else`
* `Push iff you can diff`
* `Write docs once`
* `Writer is in the team`
* `Don't write, if you can't publish`
* `Write for usability`
* `Living docs over comprehensive docs`
  

# Humans first, machines second

Documents shall be written in human-readable formats like Markdown, reStructuredText, JSON etc. and not as binary formats or other machine-readable formats like XML.
This keeps the documents as close as possible to humans, who shall maintain it.


# Keep track of changes - like everyone else

Documents shall be stored in popular version control systems like Git, rather than in custom, closed databases.
This keeps the documents open for anyone to collaborate using state-of-the-art branching and versioning techniques.

  
# Push iff you can diff

Documents shall be pushed into a version control system like Git, *if and only if* it can be easily diff-ed by others, for the changes done.


# Write docs once

Single-sourcing and DRY ("[Don't Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)") principle to write documents once, but publish several times in different formats like PDF, HTML etc. shall be followed. Even programming principles like "[The Principle of Least Knowledge](https://en.wikipedia.org/wiki/Law_of_Demeter)" and "[The Single Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)" can be applied to writing documents as well.


# Writer is in the team

 Documents shall not be created by someone and passed on, but rather created collaboratively with the team.
 Going away from the "silo" culture helps everyone learn from each other, integrates document author more into the team and helps establish the "Docs as Code" methodology.


# Don't write, if you can't publish

Documents shall be written only if it can be published and read by others.
If the document cannot be read by the ones it is ended for, consider whether it is necessary at all!


# Write for usability

Useability shall be a primary concern while writing documents. Consistency, logical structuring, minimalism, all add to usability.


# Living docs over comprehensive docs

A living document which is collaboratively edited, kept up-to-date, always online, tagged and searchable, stored as close as possible to the source code makes more sense than a extensive document which is kept "somewhere" and never updated.