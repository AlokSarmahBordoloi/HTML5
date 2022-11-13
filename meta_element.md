# HTML Meta Tag:
Example:
```ruby
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

#### usage:
- The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.
- <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
- Metadata will not be displayed on the page, but is machine parsable.
- Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

  
## Explain :
  
  ### Define keywords for search engines:
  ```ruby
  <meta name="keywords" content="HTML, markup language, HyperText Markup Language">
  ```
  ### Define a description of your web page:
  ```ruby
  <meta name="description" content="Learn HTML. HTML is the most basic building block of the web.">
  ```
  
  ### Define the author of a page:
  ```ruby
  <meta name="author" content="Alok">
  ```
  
  ### Refresh document every 30 seconds:
  ```ruby
  <meta http-equiv="refresh" content="30">
  ```
  
  ### Setting the viewport to make your website look good on all devices:
  ```ruby
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
  
  ## Setting the Viewport:
  The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.
  ```ruby
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```
  - The ```ruby width=device-width ``` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).
  - The ```ruby initial-scale=1.0 ``` part sets the initial zoom level when the page is first loaded by the browser.
  
