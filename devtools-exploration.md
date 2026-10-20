# Website Analysis: example.com

## 1. HTML Tags Used

| Tag | Purpose |
|-----|---------|
| `<html lang="en">` | Root element |
| `<head>` | Page metadata (contains `<title>` and `<meta name="viewport">`) |
| `<body>` | Page content |
| `<style>` | Inline CSS |
| `<svg>` | Book icon |
| `<p>` (x6) | Text in English, Arabic, Chinese, French, Russian and Spanish |
| `<a>` | "Learn more" link to iana.org |
| `<script>` | Loads `/s.js` |

## 2. Page Title

Example Domain

## 3. Number of Headings

0 (no `<h1>` to `<h6>` elements on the page)

# Website 2 : [Mozila Development Network](https://developer.mozilla.org/)
### 1. Navigation menu tag

The menu is wrapped in `<nav>` elements (two, nested) inside `<header class="page-layout__header">`

### 2. Search Bar Structure
The search components contains an interactive `<button>` or an `<input type="search">` field that acts a the input box. It also contains a magnifying glass icon and a keyboard shotcuts hints styled inside a flex layot for responsiveness.

### 3. Link hover styles used 
When you hover over text links the following features are noticeable;
- Color transition: the text color shifts to an interactive accent color.
- Text decoration: : Links that aren't underlined by default often gain an underline, or existing underlines thickens to clearly signal interactivity
- Background / States: Padding around buttons or nav links subtly shifts background shades (using light/dark translucent overlays) to provide immediate tactile feedback.

# Website 3 (https://httpbin.org/forms/post)
### 1. Five different HTML elements
 
| Element | Where it appears on the page |
|---------|------------------------------|
| `<form>` | The element wraps everything; `method="post"`, submits to `/post` |
| `<label>` | It shows strings such as "Customer name:", "Telephone:", "E-mail address:" |
| `<fieldset>` / `<legend>` | The "Pizza Size" and "Pizza Toppings" groups |
| `<input>` | Text, tel, email, radio, checkbox and time fields |
| `<button>` | "Submit order" (could also be an `<input type="submit">`; *to verify*) |
 
A `<textarea>` is also likely for "Delivery instructions" (*to verify*).
 
### 2. The form element and its inputs
 
| Label on the page | `name` | `type` | Source of name and type |
|-------------------|--------|--------|-------------------------|
| Customer name: | `custname` | text | Test code for this form |
| Telephone: | `custtel` | tel | Test code and HTML spec example |
| E-mail address: | `custemail` | email | Test code and HTML spec example |
| Small / Medium / Large | `size` | radio | Test code; options visible on the page |
| Bacon / Extra Cheese / Onion / Mushroom | `topping` | checkbox | HTML spec example; *to verify* |
| Preferred delivery time: | `delivery` | time | Recollection; *to verify* |
| Delivery instructions: | `comments` | textarea | Recollection; *to verify* |
| Submit order | n/a | submit button | Visible on the page |
 <img width="1883" height="965" alt="Screenshot 2026-10-20 164307" src="https://github.com/user-attachments/assets/749d5280-3cf4-4444-96aa-ccb06a235dbe" />
