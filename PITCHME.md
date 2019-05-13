# Fast-Tracking<br/>your<br/>Umbraco Development

---

@snap[north span-75]
## The Problem?
@snapend

@ul[west span-50](false)

- Setup Time
- Repetative layouts
- Need to compete with themed based CMS's
- Consistency for each project
- Encourage Best Practices

@ulend

@ul[east span-50 ](false)

- Difficult to add features @note[Self developed features / functionality]
- Complex setups for contractors
- Documentation
- Site Maintanance @note[Upgrade CMS/ Bug Fixes]

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
### Some Examples of components
@snapend


@ul[west span-50 text-09]
- Image resizing @note[auto resize to max width / height]
- Disable preview button
- layout options @note[e.g. Options for different menu layouts]
- Accessibility
- Carousels, galleries etc.
- Image color @note[Calculate main image colour]
- Forms
- Footer links
@ulend


@ul[east span-50 text-09]
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
    - Browser Sync / Concatination
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