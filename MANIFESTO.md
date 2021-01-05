# "Docs as Code" Manifesto

The "Docs as Code" Manifesto, just like the [Agile Manifesto](https://agilemanifesto.org/), has been carefully worded to capture the essence of "Docs as Code" methodology in minimum words. The eight principles read as below:

* `Humans first, machines second`
* `Keep track of changes - like everyone else`
* `Push iff you can diff`
* `Write docs once`
* `Let the writer be in the team`
* `Don't write, if you can't publish`
* `Write for usability`
* `Living docs over comprehensive docs`
  

# Humans first, machines second
![target.svg](assets/target.svg "")

Documents shall be written in human-readable formats like Markdown, reStructuredText, YAML etc. and not as binary formats or other machine-readable formats like XML.
This keeps the documents as close as possible to humans, who shall maintain it.


# Keep track of changes - like everyone else
![junction.svg](assets/junction.svg "")

Documents shall be stored in popular version control systems like Git, rather than in custom, closed databases.
This keeps the documents open for anyone to collaborate using state-of-the-art branching and versioning techniques.

  
# Push iff you can diff
![ensamble-of-circles.svg](assets/ensamble-of-circles.svg "")

Documents shall be pushed into a version control system like Git, *if and only if* it can be easily diff-ed by others, for the changes done.


# Make docs functional

If your docs _are_ code, you get the benefits of automated checks.

- Document code in a format that developer tools understand (e.g. doxygen comments that an IDE can display).
- Write imporant parts of the code such that they read like prose -- i.e. use speaking names and functions that (only) do what you expect from the name.
- Describe the usage of your code in unit/system tests (which are checked to pass by the CI and thus cannot go stale).
- Generate architecture overviews from the code, or code from architecture/human readable configuration.


# Write docs once
![content-writing.svg](assets/content-writing.svg "")

Single-sourcing and DRY ("[Don't Repeat Yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)") principle to write documents once, but publish several times in different formats like PDF, HTML etc. shall be followed. Even programming principles like "[The Principle of Least Knowledge](https://en.wikipedia.org/wiki/Law_of_Demeter)" and "[The Single Responsibility Principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)" can be applied to writing documents as well.


# Let the writer be in the team
![teamwork.svg](assets/teamwork.svg "")

Documents shall not be created by someone and passed on, but rather created collaboratively with the team.
Breaking out of silos and collaborating more thoughtfully helps everyone learn from each other, integrates document author more into the team and helps establish the "Docs as Code" methodology.


# Don't write, if you can't publish
![photo-album.svg](assets/photo-album.svg "")

Documents shall be written only if they can be published and read by others.
If the document cannot be read by the intended audience, consider whether it is necessary at all!


# Write for usability
![usability.svg](assets/usability.svg "")

Useability shall be a primary concern while writing documents. Consistency, logical structuring, minimalism, all add to usability.


# Living docs over comprehensive docs
![pulse.svg](assets/pulse.svg "")

A living document which is collaboratively edited, kept up-to-date, always online, tagged and searchable and stored as close as possible to the source code makes more sense than a extensive document which is kept "somewhere" and never updated.

>**LICENSE**

Copyright (c) Nirmal Sasidharan. All rights reserved.
Licensed under the MIT License. See [LICENSE](LICENSE).

>**ATTRIBUTION**

Icons made by [dmitri13](https://www.flaticon.com/authors/dmitri13), [pixelmeetup](https://www.flaticon.com/authors/pixelmeetup) and [freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](https://www.flaticon.com/). See [images.md](assets/images.md) for more details.

