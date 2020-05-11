# Drupal site - User Guide (Manual)
> A simple skeleton to create a (printed) User Guide (manual) for Drupal Site Administrators (non-developers, non User 1). 

## About
Have you ever created a Drupal site and need to provide a **written (printed)** documentation for the site Admins, Managers or Authors? This project is for you. "*How to add a new Page*", "*How to Promote a Node on Front Page*" etc are some of the questions that need answer in a User Guide. 

A lot of administrative tasks in Drupal may have the same UI and similar options. For example when you create a Node by default you see on the form fields like `Title`, `URL Alias`, `Promoted to front page` etc. The documentation for these fields can be generic for every site.

Of course, there is the core module [Tour](https://www.drupal.org/docs/8/core/modules/tour) that can help users with inline popups but this will not work for printed manuals.

---

## Requirements
- Use markdown files as sources.
- Organize User Guide pages in folder structure
- Use a static generator to build the Guide (hugo, gatsby, grav etc).
- Allow reader to download each User User Guide page or the whole document as pdf, html, odt.

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

## Templates
- [Page Template](/templates/page.md)
- [Entity Metadata Template](/templates/entity_metadata.md)

---

## TOC
An example of Table of Contents for a Drupal site User Guide.

1. Introduction
  1. Table of Content
  1. Cover, Date created, Owner, Logos and legal notices
  1. Requirements and prior knowledge to use these Guides
2. General
  1. Login
  1. Reset Password
3. Content: Nodes
  1. Manage Nodes (Views page explanation)
  1. Node options (Actions explanation)
  1. Node form visual guide (View-Mode VS Form 1-1 visual mapping)
  1. Paragraph TypeA Fields (View-Mode VS Form 1-1 visual mapping)
4. Content: Media/MyEntity etc
  1. Manage (see above)
  1. Options (see above)
5. Content: Taxonomy
  1. Manage (see above)
  1. Options (see above)
6. Content: Blocks
  1. (Same as above)
7. Forms
  1. FormA
    1. View FormA Results table
    1. Download FormA results
    1. Purge (Clean) FormA results
    1. Each Result of FormA Actions
8. Menus
  1. MenuA
    1. Add menu link
    1. Edit menu link
    1. Delete menu link
    1. Change weight of a menu link
    1. Disable/Enable a menu link
    1. Expand a menu link
9. Settings
  1. Clear Caches
  1. Performance Settings
  1. Google Analytics
  1. Global metatags
  1. URL Aliases
  1. URL Redirects
  1. Site Settings
  1. System Users
    1. Add User
    1. Edit User
    1. Delete User
10. Appendix
  1. Using the CKEditor
  1. Styleguide: Basic CSS styles (Headings, a links, buttons, lists, blockquote, image)
  1. Styleguide: CKEditor custom styles (with visual mapping)
  1. Styleguide: Dynamic Views from real Drupal Entity in several view modes
  1. All data Fields by usage in Entities
  1. Node Anatomy
  1. Paragraph Anatomy
  1. Paragraph View-Mode VS Form 1-1 visual mapping (for every type)
  1. What is Drupal CMS
  1. (Drupal) Terminology/Glossary (eg What are Nodes, Fields, Taxonomy, Blocks, Users, Paragraphs, View Modes, Caches, CKEditor, Accessibility, HTML)
  1. Drupal.org documentation links etc

---

## Tips
- Do not change the official Drupal terminology. Eg use the word "Node" for content pages.
- Try to use the default Drupal 8.x admin theme (Seven). It seems that Seven has the best (UX & UI) support for all the contributed modules.
- Screenshots should contain only the Main Content region (not sidebars etc) except if you use these regions on the Node Forms.
- Screenshots should not contain the Admin Toolbar or other non related UI elements.
- Screenshots should use a small - medium device width (eg up to 1200px screen).
- Screenshots of Forms with too many fields or Admin Pages with too many tasks Tasks should split to additional Guide Pages.
- Take individual Screenshots of each element form to create a more detailed Guide.
