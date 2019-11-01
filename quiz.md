# Knowledge Quiz

## HTML & CSS

### Given the following HTML and CSS, what would appear in a web browser?

```html
<!DOCTYPE html>
<html>
   <head>
      <link href="styles.css" rel="stylesheet">
   </head>
   <body>
      <div class="focus page-section"></div>
      <div id="summary" class="page-section"></div>
   </body>
</html>
```

```css
/* styles.css */

.focus {
  height: 300px;
}

#summary {
  height: 400px;
}

.page-section {
  background-color: blue;
  border: solid black 2px;
  margin: 4px;
}

.page-segment {
  background-color: green;
}
```

* [ ] An empty page

* [ ] Two boxes 300px tall, first one blue, second one green

* [ ] Two blue boxes side by side, first one 300px tall, second one
      400px tall

* [x] Two blue boxes on top of each other, first one 300px tall, second one
      400px tall


### Given the following HTML and CSS, what would appear in a web browser?

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    #bio {
      background-color: blue;
    }

    .small-section {
      border: solid black 2px;
      margin: 4px;
      background-color: pink;
    }
  </style>
</head>
<body>
  <span class="small-section">Lorem Ipsum</span>
  <span class="small-section" id="bio">More Lorem Ipsum</span>
</body>
</html>
```

* [ ] Two boxes, side by side, both pink background

* [ ] Two boxes, on top of each other, first one blue, second one pink

* [ ] Two boxes, on top of each other, both pink background

* [x] Two boxes, side by side, first one pink, second one blue

### Given the following HTML and CSS, what would appear in a web browser?

```html
<!DOCTYPE html>
<html>
<head>
  <link href="styles.css" rel="stylesheet">
  <style>
    .special {
      border: solid red 4px;
    }

    .small-section {
      border: solid black 4px;
      margin: 4px;
      background-color: pink;
    }
  </style>
</head>
<body>
  <p class="small-section">Lorem Ipsum</p>
  <p class="small-section special">More Lorem Ipsum</p>
</body>
</html>
```

* [ ] Two boxes, side by side, both pink background black border

* [ ] Two boxes, on top of each other, both pink background black border

* [ ] Two boxes, side by side, both pink background, first with black border
      second with red border

* [x] Two boxes, on top of each other, both pink background, first with
      black border second with red border

### Given the following HTML and CSS, what would appear in a web browser?

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    div.navigation a {
      color: orange;
    }

    a {
      color: green;
    }

    #course-link {
      color: red;
    }
  </style>
</head>
<body>
  <div class="navigation">
    <a href="http://google.com">Go To Google</a>
    <a href="http://fellowship.hackbrightacademy.com" id="course-link">
      Go To Frodo
    </a>
  </div>
</body>
</html>
```

* [ ] Two links, the first one green, the second one red

* [x] Two links, the first one green, the second one orange

* [ ] Two links, the first one orange, the second one red

* [ ] Two links, both orange

## Web Fundamentals

### Which of the following is **not** something web applications typically do?

* [ ] Handle HTTP requests

* [ ] Interface with databases

* [ ] Dynamically render HTML templates

* [x] Prevent caching

### Of the four parts of a URL, which is **not** typically displayed in a web browser?

* [ ] The hostname

* [ ] The resource

* [x] The port number

* [ ] The protocol

### What is the purpose of HTTP Headers?

* [ ] To prevent users from clearing cookies

* [x] To store structured metadata about an HTTP request or response

* [ ] To encrypt HTTP so that the request content is private

* [ ] To increase the speed of a network

### What is a cookie in the context of HTTP?

* [x] A piece of data that is typically stored in the client and can be
      accessed by the server

* [ ] A piece of data that does not travel in an HTTP request


* [ ] A piece of data that is the same for each user and can be accessed by
   the server

* [ ] A session key that allows applications to authenticate with APIs

## Flask & Jinja

### Which of the following code snippets is valid Jinja templating syntax?

* [] A
  ```
  {% for color in colors %}
    <p>{% color %}</p>
  {% endfor %}
  ```

* [ ] B
  ```
  { for color in colors }
    <p>{{ color }}</p>
  { endfor }
  ```

* [x] C
  ```
  {% for color in colors }
    <p>{{ color }}</p>
  {% endfor }
  ```

* [ ] D
  ```
  {{ for color in colors }}
    <p>{{ color }}</p>
  {{ endfor }}
  ```

### In Flask, where are key-value pairs of query strings (from a GET request) stored?

* [ ] `request.params`

* [ ] `request.get`

* [ ] `request.args`

* [x] `request.args.get`

### In Flask, where is form data (from a POST request) stored?

* [x] `request.form`

* [ ] `request.form.get`

* [ ] `request.params`

* [ ] `request.data`

## Testing

### Which of the following is *not* an example of an integration test?

* [ ] A test that checks whether requesting a user profile page redirects to the
      login page if a user is not logged in.

* [ ] A test that checks whether requesting a user profile page when a user
      is logged in successfully renders their information.

* [ ] A test that checks whether requesting the homepage of a web application
      can successfully render.

* [x] A test that checks whether the calculation for order cost is correct in
      relation to a given set of items in the shopping cart.
