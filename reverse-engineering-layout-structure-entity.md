I am migrating a legacy AngularJS/Kendo UI application to Angular 20 with Bootstrap 5.

I need help reproducing the layout of an existing form as accurately as possible.

Important context:

* The legacy form uses custom CSS classes such as:

  * longlabel
  * mediumtext
  * mediumshorttext
  * shorttext
* There are many custom styles that are not standard Bootstrap classes.
* Required field indicators (*) are rendered as separate label elements after inputs, not as part of the field label.
* The page appears to use fixed-width labels and inputs rather than a modern responsive grid.
* The layout contains rows where multiple field groups appear on the same line, for example:

  City: [input] *   State: [dropdown] *   Country: [dropdown] *

Tasks:

1. Analyze the HTML and all referenced CSS classes.
2. Determine the actual rendered widths and positioning rules used by the legacy page.
3. Identify which CSS classes control:

   * label width
   * input width
   * spacing between controls
   * required indicator placement
   * row alignment
4. Explain the layout model being used (fixed-width inline layout, flexbox, floats, table layout, etc.).
5. Recommend the best Angular 20 + Bootstrap 5 implementation that visually matches the legacy page.
6. If custom CSS widths are required, generate equivalent Bootstrap-compatible CSS.
7. Do not redesign the page. Preserve the visual layout as closely as possible.

Please provide:

* Layout analysis
* CSS class analysis
* Recommended Angular template structure
* Recommended Bootstrap classes
* Any replacement CSS needed to match the legacy appearance
