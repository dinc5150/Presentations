# Fast-Tracking<br/>your<br/>Umbraco Development

---

@snap[north span-75]
# The Problem?
@snapend

@ul[east span-50](false)

- Each project took time to setup
- Repetative layouts
- Need to compete with themed based CMS's
- Consistency for each project
- Encourage Best Practices

@ulend

@ul[west span-50 ](false)

- Difficult to add self developed features
- Complex setups for contractors
- Documentation
- Maintaining sites: *Upgrades / bug fixes*

@ulend

---

## The Solution?

@ul

- Develop a core solution
- Componentise
- Use git for syncing code
- Use Tools: *uSync / Chauffeur / Less / Client Dependency*

@ulend

---

## The Benefits?

@ul

- Shared code / Upgrades
- Faster implementation
- Bug Fixes
- Quick to get started on basic sites
- Example code, baked into the site as a springboard
- Documentation

@ulend
---
@snap[north span-75]
## Some Examples of components
@snapend


@ul[west span-50 text-06]
- Image resizing @note[auto resize to max width / height]
- Disable preview button
- layout options @note[e.g. Options for different menu layouts]
- Accessibility
- Carousels, galleries etc.
- Image color @note[Calculate main image colour]
- Forms
- Footer links
@ulend


@ul[east span-50 text-06]
- Search
- News / Blog / Events
- Fluid type @note[Reponsive type]
- SEO / social share
- Default configs / transorms
- .EditorConfig, .YAML builds
- Sitemap.xml @note[Auto Generated]
- 404 Handler

@ulend

---

## Git it together!

@ul
- Release Branch
- Feature Branches
    - Forking
    - Upstream Remote
- Add
- Pull / merge
    - Scripts
- Add Upstream Remote
- Pull in changes from Release
@ulend

---

## Get up and running

@ul
- Chauffeur 
- uSync
- These make it easy for others to get on board
@ulend

---

## Keep it Clean

@ul

- Create each feature as its own component
- Keep it as general as possible, but still useful
- CSS Defaults: Less includes
- JavaScript components
- CSS/JS Included with client dependency
    - Browser Sync
    - Concatination
- Concatination
- Razor Partials
- Handling Occasional Modules
    - Exclude from project
    - MyGet / Umbraco Packages
    - Feature Branches

@ulend

---

## Common Headaches

- Merging included files into .csproj. Sometimes duplicate files
- Merging Content / uSync
- Developing new features for a project can be a little cumbersome
    - Needs to be re-usable
    - Needs planning
    - Lots of commits / tests / pulling into projects

---

## Add Some Slide Candy

![](assets/img/presentation.png)

---
@title[Customize Slide Layout]

@snap[west span-50]
## Customize Slide Content Layout
@snapend

@snap[east span-50]
![](assets/img/presentation.png)
@snapend

---?color=#E58537
@title[Add A Little Imagination]

@snap[north-west]
#### Add a splash of @color[cyan](**color**) and you are ready to start presenting...
@snapend

@snap[west span-55]
@ul[spaced text-white]
- You will be amazed
- What you can achieve
- *With a little imagination...*
- And **GitPitch Markdown**
@ulend
@snapend

@snap[east span-45]
@img[shadow](assets/img/conference.png)
@snapend

---?image=assets/img/presenter.jpg

@snap[north span-100 headline]
## Now It's Your Turn
@snapend

@snap[south span-100 text-06]
[Click here to jump straight into the interactive feature guides in the GitPitch Docs @fa[external-link]](https://gitpitch.com/docs/getting-started/tutorial/)
@snapend
