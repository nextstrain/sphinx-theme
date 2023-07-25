=========
Changelog
=========

2023.1 (16 February 2023)
=========================

Update the team member list in the footer to match nextstrain.org's new footer.
(`#37 <https://github.com/nextstrain/sphinx-theme/pull/37>`_)

Fix the footer formatting when sphinx-rtd-theme 1.2.0 (or newer) is used.
(`#36 <https://github.com/nextstrain/sphinx-theme/pull/36>`_)

Document in the README how to develop the theme locally.
(`#34 <https://github.com/nextstrain/sphinx-theme/pull/34>`_)


2022.9 (25 July 2022)
=====================

Revert workaround for ``markdown`` and ``sphinx-markdown-tables`` from previous
release.
(`#31 <https://github.com/nextstrain/sphinx-theme/pull/31>`_)


2022.8 (18 July 2022)
=====================

A dependency on the Python distribution ``markdown <3.4.0`` was added to help
resolve a compatibility issue with the ``sphinx-markdown-tables`` distribution,
which we use in several of our projects.  Hopefully upstream will fix the issue
with a new release and then this dependency can be removed.
(`#29 <https://github.com/nextstrain/sphinx-theme/pull/29>`_)


2022.7 (12 July 2022)
=====================

The top-of-sidebar block containing the logo, project name, version, and search
box is now pinned to the top of the sidebar when it scrolls.  This helps
maintain the page's visual structure even if the sidebar navigation is long and
requires scrolling.


2022.6 (11 July 2022)
=====================

The scroll-into-view behaviour for the current page's entry in the navigation
sidebar is now a bit less jumpy.  Scrolling will be (mostly) avoided if the
link is already in view, rather than always trying to scroll it to the top of
the viewport. (`#27 <https://github.com/nextstrain/sphinx-theme/pull/27>`_)


2022.5 (27 April 2022)
======================

The ``sphinx-copybutton`` extension is installed to this package with some
default configurations. For it to work properly, this package must be used as
an extension in addition to usage as a theme (`#26 <https://github.com/nextstrain/sphinx-theme/pull/26>`_).

Demo doc includes example usage.

2022.4 (5 April 2022)
=====================

Navigation links which are at the second-level or deeper now use the normal
font weight instead of a lighter font weight.  The intent is to make them more
readable.

The mobile navigation text and menu icon are now a readable color against the
grey background, instead of white.

Demo doc now includes pages nested in sub toctrees.


2022.3 (24 March 2022)
======================
The version of the base theme, ``sphinx_rtd_theme``, has been updated to 1.0.0
to support latest styling (`#19 <https://github.com/nextstrain/sphinx-theme/pull/19>`_).

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
