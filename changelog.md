 ChartStudio v3 [Major Update]

 Architecture & Core Features

  -  Multi-Page Workspace & Page Manager: Replaced the single-view limit with a
    robust multi-page system. Includes a dedicated Pages Menu Modal with
    auto-generated image thumbnails to quickly create, duplicate, reorder, and
    clear pages.
  -  Advanced View Modes: Introduced new rendering modes (Combined, Split Grid,
    Single) and chunk controls to automatically distribute large datasets across
    multiple charts.
  -  Interactive HTML Table Chart: Added a brand-new Table chart type supporting
    Multi-Cell Color Editing. Click and drag to select cells, then assign custom
    background colors for visual data highlighting.
  -  Drag-and-Drop Layout Editor: A new "Move Mode" turns the export frame into
    a modular grid, allowing you to physically drag and reorder the Title, Chart
    Area, and Legend blocks for custom exports.

 Data Analysis & Import Upgrades

  -  Smart Origin Tracking & Parsers: The importer automatically detects
    specialized JSON origins (e.g., RedTracker app data, Instagram Chat exports)
    and processes raw logs into structured metrics. Displays an origin badge in
    the sidebar.
  -  Average Groups: Added the ability to create Avg Groups (AVG_GROUP) to
    calculate and plot the mean average of selected datasets, rather than
    standard sum groupings.
  -  Spawn Selected Modal: A new rapid-workflow tool to bulk-add available
    metrics to your current page via a click-based menu, bypassing the need to
    drag-and-drop items individually.

 Visuals & Customization

  -  Custom Title Icons: Integrated a FontAwesome Icon Picker to attach scalable
    vector icons directly next to the main dashboard title or individual chart
    box titles.
  -  Horizontal Bar Charts: Added a direct settings toggle to instantly flip Bar
    charts from vertical to horizontal.
  -  Universal Shared Legend: In "Split (Grid)" view, the app extracts all
    dataset labels and generates a unified, clean HTML legend at the bottom of
    the layout, keeping individual charts uncluttered.
  -  Chart Box Titles: Individual split-grid charts now feature editable,
    floating titles with independent visibility toggles.
  -  Expanded Canvas: Increased the maximum application container width to
    1750px to comfortably accommodate wider multi-chart grid layouts.

 Quality of Life Improvements

  -  Upgraded Export Engine: High-res canvas exports now scale up to 4x
    resolution with 0.5x step increments for fine-tuned quality vs. performance
    control.
  -  Save/Load Layout Upgrades: The .json layout save file now remembers your
    entire multi-page configuration, table cell colors, custom icons, view
    modes, and drag-and-drop block arrangements.
  -  Dynamic Interactive Tips: Helper tooltips now dynamically update and hide
    themselves during Move Mode or when unsupported chart types (like tables)
    are active.

 Removals & Deprecations

  -  Pyramid Chart: Removed the custom Pyramid chart type to streamline the
    codebase and focus on standard analytical chart formats.
  -  Legacy Auto-Pagination: Replaced the old sequential sidebar pagination
    entirely with the new visual Page Manager and Split-View chunk controls.
