=========
Changelog
=========

2022.2 (16 March 2022)
======================

The styling of wide tables is now much improved.  Tables will expand to use the
available viewport width instead of staying confined within the main content
column.  They remain horizontally scrollable when the viewport is not wide
enough to fully accommodate them.

Demo documentation from the base theme, ``sphinx_rtd_theme``, is included in
this theme's own documentation now, to provide comprehensive previews of
changes.

An appropriate LICENSE file is now included.  (The MIT licensing was previously
only declared in Python distribution metadata.)

2022.1 (4 February 2022)
========================

Breadcrumbs now start with the main Nextstrain doc home page and don't include
current page title, along with a couple other small changes for clarity.

The logo now links to https://docs.nextstrain.org by default instead of
https://nextstrain.org, which feels more "right" to several members of the
team.  A new option, ``logo_link``, allows control of the URL used for the
logo's link if necessary (though this is unexpected for Nextstrain docs).

The "Click here to return …" message is gone from subproject sidebars in favor
of the improved breadcrumbs at the top of the page and the change to the logo'
link.

The clarity and precision of the currently displayed project version is
improved.  "Stable" now shows the precise version (when available) and "latest"
is described as the "development" version with the precise commit shown.

The documentation versions panel added by Read the Docs now stays docked to the
bottom of the sidebar when expanded instead of becoming unmoored and floating
over the bottom right corner of the page.

2021.4 (3 November 2021)
=========================

The titles of sidebar directives (not the navigation sidebar) now use our theme
font (Lato) too.

Updated funding sources in the footer to reflect current funding for the Basel
team.

2021.3 (2 September 2021)
=========================

The page footer was updated with the latest team members from nextstrain.org
and a more accurate description of our software licenses.  Alt text was added
to logos and other small tweaks were also made.

External links in the TOC tree sidebar are now marked with a trailing icon.

This theme now has its own documentation build, including demos of
theme-specific styling, and previews will be built for PRs.

2021.2 (17 August 2021)
=======================

Defaults favicon to Nextstrain logo.

2021.1 (19 May 2021)
=======================

Fixes a link under the Open Science Prize logo.

2020.6 (23 November 2020)
============================

Restores monospace font for inline literals.

2020.5 (03 November 2020)
============================

Includes sidebar improvements with links to nextstrain.org and the main docs.nextstrain.org; see `#4 <https://github.com/nextstrain/sphinx-theme/pull/4>`__.

2020.4 (23 October 2020)
===========================

Includes styling changes in `#1 <https://github.com/nextstrain/sphinx-theme/pull/1>`__ and a footer in `#2 <https://github.com/nextstrain/sphinx-theme/pull/2>`__.
