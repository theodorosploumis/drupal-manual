# Drupal site - User Guide (Manual)
> A simple skeleton to create a (printed) User Guide (manual) for Drupal Site Administrators (non-developers, non User 1). 

## About
Have you ever created a Drupal site and need to provide a **written (printed)** documentation for the site Admins, Managers or Authors? This project is for you. "*How to add a new Page*", "*How to Promote a Node on Front Page*" etc are some of the questions that need answer in a User Guide. 

A lot of administrative tasks in Drupal may have the same UI and similar options. For example when you create a Node by default you see on the form fields like `Title`, `URL Alias`, `Promoted to front page` etc. The documentation for these fields can be generic for every site.

Of course, there is the core module [Tour](https://www.drupal.org/docs/8/core/modules/tour) that can help users with inline popups but this will not work for printed manuals.

---

## Options and Fields

### Node Options

(Create a a common doc file for these options which are usually the same for every Drupal site. Most of the options appear from contributed modules. The same options may appear for **Media or other custom Content entities**).

- View
- Edit
- Delete
- Create (Add new)
- Publish/Unpublish
- Preview
- Replicate
- Create Revision
- View Revisions
- Revert Revisions
- Compare Revisions

---

### Paragraphs Options
(Create a a common doc file for these options which are usually the same for every Drupal site. Most of the options appear from contributed modules.)

- View
- Edit
- Delete (Remove)
- Create (Add new)
- Preview
- Move up/down (change weight)
- Duplicate
- Collapse
- Add Above

---

### Webform Options
(Create a a common doc file for these options which are usually the same for every Drupal site. These options appear from the webform module.)

- View
- Submit
- Edit
- Delete
- Resend (submit with the existing values)
- Test
- Notes (add administrative notes)

---

### Menu Options
(Create a a common doc file for these options which are usually the same for every Drupal site. These options appear from the core menu module.)

- View menu links
- Add new menu link
- Change weight of menu links
- Edit a menu link
- Delete a menu link
- Enable/Disable a menu link
- Show as expanded
- (Alternative way to alter a menu link)

---

### Node Form Fields

(Create a a common doc file for these options which are usually the same for every Drupal site. Some of the fields appear from contributed modules.)

- Title
- Create Revision
- Menu Settings
- Metatags
- URL Alias
- URL Redirects
- Simple XML Sitemap
- Authored by (author)
- Authored on (created date)
- Promoted to front page
- Sticky at top of lists
- Published
- **CUSTOM FIELDS (eg Paragraph fields, images etc...)**

---

## TOC
An example of a TOC for the User Guide.

- Introduction
  - What is Drupal CMS
  - (Drupal) Terminology/Glossary (eg What are Nodes, Fields, Taxonomy, Blocks, Users, Paragraphs, View Modes, Caches, CKEditor)
  - Requirements and prior knowledge to use these Guides
- General
  - Login
  - Reset Password
- Content: Nodes
  - Manage Nodes (Views page explanation)
  - Node options (Actions explanation)
  - Node form visual guide (View-Mode VS Form 1-1 visual mapping)
  - Paragraph TypeA Fields (View-Mode VS Form 1-1 visual mapping)
- Content: Media/MyEntity etc
  - Manage (see above)
  - Options (see above)
- Content: Taxonomy
  - Manage (see above)
  - Options (see above)
- Content: Blocks
  - (Same as above)
- Forms
  - FormA
    - View FormA Results table
    - Download FormA results
    - Purge (Clean) FormA results
    - Each Result of FormA Actions
- Menus
  - MenuA
    - Add menu link
    - Edit menu link
    - Delete menu link
    - Change weight of a menu link
    - Disable/Enable a menu link
    - Expand a menu link
- Settings
  - Clear Caches
  - Performance Settings
  - Google Analytics
  - Global metatags
  - URL Aliases
  - URL Redirects
  - Site Settings
  - System Users
    - Add User
    - Edit User
    - Delete User
- Appendix
  - Using the CKEditor
  - Styleguide: Basic CSS styles (Headings, a links, buttons, lists, blockquote, image)
  - Styleguide: CKEditor custom styles (with visual mapping)
  - Styleguide: Dynamic Views from real Drupal Entity in several view modes
  - All data Fields by usage in Entities
  - Node Anatomy
  - Paragraph Anatomy
  - Paragraph View-Mode VS Form 1-1 visual mapping (for every type)
  - Drupal.org documentation links etc
