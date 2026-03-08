# Development Responsibilities

---

# MAIA — Responsibilities

### Layout Structure

* Create the main HTML skeleton
* Implement the overall page layout
* Structure the main containers of the application
* Maintain the global layout consistency

### Navigation & Layout Elements

* Build the **Sidebar navigation**
* Implement the **Top Header navigation**
* Create the **Bottom Player layout**
* Implement the **Mobile Bottom Navigation**

### HTML Responsibilities

* Maintain the core layout structure in `index.html`
* Organize semantic HTML elements (aside, header, main, footer)

### SCSS Files Managed by MAIA

```text
layout/
  _page.scss
  _sidebar.scss
  _header.scss
  _player.scss
  _mobile-nav.scss
```

---

# IA — Responsibilities

### UI Components

* Create **Filter Chips row**
* Implement **Card components** (albums / playlists / mixes)
* Build reusable UI elements
* Style interactive components

### Content Sections

* Implement **Made For You section**
* Implement **Discover sections**
* Build **Search page UI**
* Build **Library page UI**
* Build **Profile page content**

### SCSS Files Managed by IA

```text
components/
  _cards.scss
  _filter-chips.scss
  _buttons.scss
  _icon-button.scss

pages/
  _home.scss
  _search.scss
  _library.scss
  _profile.scss
```

---

# Collaboration Rules

To avoid merge conflicts and maintain a clean repository:

* Each member works only on their assigned files.
* Layout files should only be modified by **MAIA**.
* Component and page files should only be modified by **IA**.
* All changes must be committed with meaningful commit messages.
* Work should be pushed to feature branches before merging into `main`.
