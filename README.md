# lab5-css-foundations

## Live Demo
[View on GitHub Pages](https://tjhayes22.github.io/lab5-css-foundations/)

## Implementation Approach

The goal of this lab was to reinforce my
knowledge of semantic html and learn modern 
CSS practices.

In `index.html`:
- I had a simple strcuture where the body of the page
contained a container, `login-container`, which had two sections, one with id `login-info` and the other with id `login-form`.
- `login-info` contained the title(`h1`) and the description(`p`), which I later styled in `styles.css`.
- `login-info` had a form element where I had custom tags `form-field`, `sign-in-and-forgot-password`, and `password-recovery`. These custom tags contained the email field, password field, sign-in button and forgot password link. 

In `styles.css`:
- I structured the layout using a two-column grid with `#login-info` on the left and `#login-form` on the right.
- I used CSS variables and a simple reset for consistent spacing and colors for different sections of the page. I also changed the background color of the body so you could see the border radius around the edges of the `#login-info` and `#login-form`. 

---

## Design Decisions

- I chose a blue gradient for the login info section to create contrast with the white form. 
- I also chose a font style that was close to the font in the given example image. 
- Rounded corners and consistent spacing give the page a modern, clean look.

---

## Challenges & Solutions

One issue I faced was uneven spacing at the bottom of the layout and I also struggled to get the page to adjust to different window sizes.  
I solved it by adjusting `min-height` and using a wrapper `.login-container` to control padding and rounding.

---