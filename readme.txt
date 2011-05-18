htmLawed Drupal 7.x module
==========================

  Copyright Santosh Patnaik, MD, PhD
  Copyright Federico Jaramillo Martínez
  Initiated May 2008


About htmLawed
==========================
  PHP code to purify & filter HTML

   * make HTML markup in text secure and standard-compliant
   * process text for use in HTML, XHTML or XML documents
   * restrict HTML elements, attributes or URL protocols using black- or white-lists
   * balance tags, check element nesting, transform deprecated attributes and tags, make relative URLs absolute, etc.
   * fast, highly customizable, well-documented
   * single, 47 kb file
   * simple HTML Tidy alternative
   * free and licensed under LGPL
   * use to filter, secure & sanitize HTML in blog comments or forum posts, generate XML-compatible feed items from web-page excerpts, convert HTML to XHTML, pretty-print HTML, scrape web-pages, reduce spam, remove XSS code, etc.


About htmLawed
==========================

  htmLawed is a highly customizable single-file PHP script to make text secure, and standard- and admin policy-compliant for use in the body of HTML 4, XHTML 1 or 1.1, or generic XML documents. It is thus a configurable input (X)HTML filter, processor, purifier, sanitizer, beautifier, etc., and an alternative to the HTMLTidy application.

  The lawing in of input text is needed to ensure that HTML code in the text is standard-compliant, does not introduce security vulnerabilities, and does not break the aesthetics, design or layout of web-pages. htmLawed tries to do this by, for example, making HTML well-formed with balanced and properly nested tags, neutralizing code that may be used for cross-site scripting (XSS) attacks, and allowing only specified HTML elements/tags and attributes.


Module installation
==========================

Follow normal installations instructions
http://drupal.org/documentation/install/modules-themes/modules-7


Notes
==========================

1. Check for conflicts with any third-party filter modules in use.

2. You can replace files inside 'htmLawed/htmLawed/' with the latest versions from http://www.bioinformatics.org/phplabware/internal_utilities/htmlawed/index.php.

3. Disabling the module will not delete any htmLawed setting.