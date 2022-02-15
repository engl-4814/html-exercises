# Accessibility: Defining Landmarks for your favorite things!

**Goal**: Create another website about your favorite things. But, this time create it with more robust content and accessibility landmarks!

But, if you want to create a page about something else of your choosing, go for it!

## Objectives

Create a page with at least 3 different topics with an occassional sub-topic related to your topic. Try to create a page that uses `h1`-`h3` headings at the very least.

Be sure that your page practices the following A11Y skills:

### 1. Skip links

Create a *skip link* to the main content landmark region of the page

### 2. Landmark regions

Define landmark regions on the page by using the following HTML5 elements (for reference, revisit the [landmark demo](https://engl-4814.github.io/demos/aria-landmark/index.html)):

- `nav`
- `header`
- `main`
- `section` or `article` (based on your context)
- `aside` 
- `footer`

### 3. Role and aria label attributes

For the landmarks, define their roles with the `role`, as well as `aria-label` and/or `aria-labelledby` attributes. 

Don't forget about our readings for your reference. In particular for region roles, see TPGi's ['Comparison of ARIA landmark roles and HTML5 structural elements'](https://www.tpgi.com/using-wai-aria-landmarks-2013/#table1).

### 4. Headings

Based on the document's structure, use the appropriate leveled headings (`h1`, `h2`, `h3`, etc.). 

And, make sure your headings are meaningful and provide context for the content below it.

### 5. Typical, but semantically appropriate, HTML for content

Within each landmark area, use any other appropriate elements:

- `p`
- Lists (`ol` and `ul`) 
- `img`: At least one `img` with an `alt` attribute description

Feel free to use placeholder text in paragraphs, such as Lorem Ipsum, to pad your site to look more robust.
