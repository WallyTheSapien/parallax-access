PARALLAX ACCESS — SEPARATED FILES
=================================

Open index.html to launch the site locally.

PAGE STRUCTURE
- index.html                 Home / landing page
- projects/index.html        Project registry
- projects/*.html            Individual project detail pages
- developers/index.html      Developer directory
- developers/developer-*.html Individual developer profiles
- tools/index.html           Tools storefront

CSS
- css/base.css              Original storefront styles preserved
- css/navigation.css        Shared header/footer/navigation
- css/home.css              Home layout
- css/projects.css          Project registry cards
- css/project-detail.css    Project documentation detail layout
- css/developers.css        Developer directory/profile layout
- css/tools.css             Tools storefront layout

EDITING TIPS
1. Use a text editor such as VS Code.
2. Page content lives in its own HTML file.
3. Shared site colors and most original storefront styling are in css/base.css.
4. Change detail page structure in its specific HTML file, and its spacing/layout in the matching CSS file.
5. The profile gallery filter buttons are functional on each developer profile.
6. Project system accordions use native HTML <details>/<summary> controls.

NOTE
These files are an editable static front-end organization of the storefront and the requested detail-page visual direction. Demo profile/project data is authored into the individual pages. The original admin/editor scripts are not wired into these standalone static pages.
