<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/xima-media/.github/raw/main/profile/assets/banner-dark.svg">
  <img alt="Open source for TYPO3. Extensions and tooling from XIMA in Dresden." src="https://github.com/xima-media/.github/raw/main/profile/assets/banner-light.svg" width="100%">
</picture>

<br>

Most of the websites we build for the public sector run on TYPO3. When a project needs something the core does not ship, we try to build it once, properly, and publish it. Over the years that has added up to more than 35 extensions, downloaded close to a million times from Packagist.

This page is the index.

[Showcase](#showcase) · [Every extension](#every-extension) · [Deployment](#deployment-and-infrastructure) · [xima.de](https://www.xima.de/)

## Showcase

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/xima-media/xima-typo3-frontend-edit"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/frontend-edit.gif" alt="Frontend Edit toolbar on a content element"></a>
<br><br>
<b><a href="https://github.com/xima-media/xima-typo3-frontend-edit">Frontend Edit</a></b><br>
Editors hover a content element on the live page and get an edit menu right there. No hunting through the page tree.
</td>
<td width="50%" valign="top">
<a href="https://github.com/maikschneider/bw_focuspoint_images"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/focuspoint-images.jpg" alt="Focuspoint editor in the TYPO3 backend"></a>
<br><br>
<b><a href="https://github.com/maikschneider/bw_focuspoint_images">Focuspoint Images</a></b><br>
Responsive image maps. Draw areas on an image in the backend and attach text, links and your own fields to each one.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/xima-media/xima-typo3-content-planner"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/content-planner.jpg" alt="Page with a Content Planner status in the TYPO3 backend"></a>
<br><br>
<b><a href="https://github.com/xima-media/xima-typo3-content-planner">Content Planner</a></b><br>
Statuses, assignees and comments on pages and records. Built for relaunches where hundreds of pages move at once.
</td>
<td width="50%" valign="top">
<a href="https://github.com/maikschneider/tca-api"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/tca-api.jpg" alt="TCA API configuration in the TYPO3 backend"></a>
<br><br>
<b><a href="https://github.com/maikschneider/tca-api">TCA API</a></b><br>
A REST API from a PHP array. Name a table and get filtering, pagination, access control and an OpenAPI spec, without writing a controller.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/maikschneider/bw_captcha"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/captcha.jpg" alt="Captcha field with audio button in a TYPO3 form"></a>
<br><br>
<b><a href="https://github.com/maikschneider/bw_captcha">Captcha</a></b><br>
A captcha element for the form framework, with audio output and no third-party requests. Our most installed extension.
</td>
<td width="50%" valign="top">
<a href="https://github.com/xima-media/xima-typo3-recordlist"><img src="https://github.com/xima-media/.github/raw/main/profile/assets/showcase/recordlist.jpg" alt="Custom record list backend module"></a>
<br><br>
<b><a href="https://github.com/xima-media/xima-typo3-recordlist">Recordlist</a></b><br>
Backend modules for large record sets in a few lines of PHP. Filters, sorting, inline editing and workspace approvals included.
</td>
</tr>
</table>

## Every extension

Grouped by who uses them. Downloads are Packagist totals as of October 2026.

### For editors

| Extension | What it does | TYPO3 | Downloads |
|:--|:--|:--|--:|
| [Frontend Edit](https://github.com/xima-media/xima-typo3-frontend-edit) | Edit menu for content elements and pages, inside the frontend | 13 · 14 | 20.7k |
| [Content Planner](https://github.com/xima-media/xima-typo3-content-planner) | Page and record statuses for planning content work and migrations | 13 · 14 | 19.9k |
| [Editor Manual](https://github.com/xima-media/xima-typo3-manual) | Write the editor manual as a page tree, right in the backend | 12 · 13 | 23.8k |
| [Internal News](https://github.com/xima-media/xima-typo3-internal-news) | Backend news with access rules and notifications for editorial teams | 13 · 14 | 2.4k |
| [Dashboard News](https://github.com/xima-media/xima-typo3-dashboard-news) | Announcements for editors as a dashboard widget | 12 – 14 | 7.1k |
| [Recent Updates](https://github.com/xima-media/xima-typo3-recent-updates) | Dashboard widget listing recently changed records | 11 – 13 | 5.7k |
| [Calendar](https://github.com/xima-media/xima-typo3-calendar) | Events and appointments with an editorial workflow and iCal feed | 13 | new |

### Images, forms and content elements

| Extension | What it does | TYPO3 | Downloads |
|:--|:--|:--|--:|
| [Captcha](https://github.com/maikschneider/bw_captcha) | Captcha for the form framework, with audio, without Google | 12 – 14 | 357k |
| [Focuspoint Images](https://github.com/maikschneider/bw_focuspoint_images) | Image editor for responsive image maps | 13 · 14 | 127k |
| [Icons](https://github.com/maikschneider/bw_icons) | Icon picker for TCA fields and the rich text editor | 13 · 14 | 111k |
| [JSON Editor](https://github.com/maikschneider/bw_jsoneditor) | JSON editor as a TCA field type | 12 – 14 | 78.4k |
| [Static Template](https://github.com/maikschneider/bw_static_template) | Content element that renders a Fluid template with JSON data | 13 · 14 | 42.6k |
| [Formcycle](https://github.com/xima-media/xm_formcycle) | Embed Formcycle forms in TYPO3 pages | 13 | 10.3k |

### APIs and authentication

| Extension | What it does | TYPO3 | Downloads |
|:--|:--|:--|--:|
| [TCA API](https://github.com/maikschneider/tca-api) | REST API derived from TCA, served as Hydra JSON-LD | 13 · 14 | 3.3k |
| [API Key](https://github.com/maikschneider/api-key) | Stateless API key authentication | 13 · 14 | new |
| [OAuth2 Extended](https://github.com/xima-media/xima-oauth2-extended) | Extra OAuth2 providers with on-the-fly user creation | 12 · 13 | 37.7k |
| [t3api Cache](https://github.com/xima-media/t3api_cache) | Response cache for t3api endpoints | — | 9.7k |
| [Twitter/X Client](https://github.com/xima-media/xima-typo3-twitter-client) | Fetch and display posts from X accounts | 13 · 14 | 6.4k |

### For integrators and developers

| Extension | What it does | TYPO3 | Downloads |
|:--|:--|:--|--:|
| [Mailcatcher](https://github.com/xima-media/xima-typo3-mailcatcher) | Read every sent mail in a backend module | 11 – 14 | 31.2k |
| [Recordlist](https://github.com/xima-media/xima-typo3-recordlist) | Build advanced record list modules quickly | 13 · 14 | 17.8k |
| [Scheduler as Code](https://github.com/maikschneider/scheduler-as-code) | Scheduler tasks as YAML files under version control | 13 · 14 | new |
| [Solr Shield](https://github.com/maikschneider/solr-shield) | Keeps bots and junk traffic away from Solr | 13 · 14 | new |
| [Category Tree](https://github.com/maikschneider/category-tree) | Reusable category tree navigation for backend modules | 13 · 14 | 1.0k |
| [Login Color Scheme](https://github.com/maikschneider/login-color-scheme) | Dark mode variant for the backend login image | 13 · 14 | 0.6k |
| [Metadata Fixer](https://github.com/xima-media/xima-typo3-metadata-fixer) | Repairs missing or broken `sys_file_metadata` records | 12 · 13 | 5.8k |

## Deployment and infrastructure

The tooling every one of our TYPO3 projects ships with.

| Project | What it does | Downloads |
|:--|:--|--:|
| [Deployer Extended TYPO3](https://github.com/xima-media/xima-deployer-extended-typo3) | Shared Deployer configuration for TYPO3 projects | 37.8k |
| [GitLab Templates](https://github.com/xima-media/gitlab-templates) | Reusable GitLab CI jobs for building, testing and deploying | — |
| [TYPO3 Docker](https://github.com/xima-media/typo3-docker) | PHP and Composer images with pinned versions | — |
| [ddep](https://github.com/xima-media/ddep) | Pull databases and media from remote Docker environments over SSH | — |

<details>
<summary><b>Older and archived work</b></summary>
<br>

| Project | What it does |
|:--|:--|
| [Content Audit](https://github.com/xima-media/xima-typo3-content-audit) | Dashboard widget that surfaces outdated content |
| [Page Subscription](https://github.com/xima-media/xima-typo3-page-subscription) | Frontend users subscribe to changes on a page |
| [Toolbox](https://github.com/xima-media/xima-typo3-toolbox) | Version, context and update hints in backend and frontend |
| [GoAccess](https://github.com/xima-media/xm-goaccess) | goaccess.io traffic metrics on the dashboard |
| [Guild](https://github.com/maikschneider/bw_guild) | Frontend user management with profiles and offers |
| [Email](https://github.com/maikschneider/bw_email) | Send any record as a responsive email |
| [Booking Manager](https://github.com/maikschneider/bw_bookingmanager) | Generic booking calendar for TYPO3 |
| [Cache URI](https://github.com/maikschneider/bw_cache_uri) | Load and post-process remote content in a cached element |
| [xm_tools](https://github.com/xima-media/xm_tools) | Framework extension for building other extensions |
| [iCal Bundle](https://github.com/xima-media/ical-bundle) | Symfony wrapper for `eluceo/ical` |
| [Steganography](https://github.com/maikschneider/steganography) | Hide a message inside an image, in plain PHP |

</details>

---

<sub>XIMA MEDIA GmbH · Dresden, Germany · [xima.de](https://www.xima.de/) · [Imprint](https://www.xima.de/impressum)</sub>
