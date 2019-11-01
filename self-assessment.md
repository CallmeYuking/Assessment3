# Skills 3 Self-Assessment

<!-- Enter your scores below!

For example:

### print_indices

* **Completeness:** 5
* **Correctness:** 5
* **Code style:** 5
-->


## Skills: Flask

### `/` route displays homepage with header, melon image, form

The form asks for a user's name and submits data to `action="/get-name"`

* **Completeness:** 5
* **Correctness:** 5
* **Code style:** 5

### `/get-name` route adds user's name to `session`, redirects to `/top-melons`

* **Completeness:** 3
* **Correctness:** 3
* **Code style:** 3

### Users can't go to `/top-melons` route unless their name is in `session`

If user's name is not in `session`, they are redirected to `/`.

If the user's name *is* in `session`, if they go to the homepage (`/`) they are
redirected to `/top-melons`.

* **Completeness:** 3
* **Correctness:** 3
* **Code style:** 3

### `/top-melons` route displays data from `MOST_LOVED_MELONS`

* **Completeness:** 4
* **Correctness:** 3
* **Code style:** 3

### `/top-melons` route displays user's name

* **Completeness:** 3
* **Correctness:** 3
* **Code style:** 4

### All Jinja templates inherit from `templates/base.html`

* **Completeness:** 0
* **Correctness:** 0
* **Code style:** 0

### `static/styles.css` has styles that make the page more melon-y

* Page background is a pale canteloupe color
* Headings are a sans-serif font in red
* Images have a green border
* Melon image on homepage is centered

* **Completeness:** 3
* **Correctness:** 2
* **Code style:** 4

### (Optional) Users can "love" any melon in `/top-melons` route

"Love"-ing a melon increases its `num_loves` count

* **Completeness:** 0   
* **Correctness:** 0
* **Code style:**   0

## Final Reflections

### What is one improvement you can make to your code?

Can draw diagram before writing the code.

### Did you learn something new from the solutions?

Solution definately helped me to clearify the process of the web-app building.

### Anything else?

<!-- Additional space for you to note down your thoughts, comments, etc. -->

