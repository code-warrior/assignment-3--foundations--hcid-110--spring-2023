# Spring 2023 Foundations of Web Design and Development — Assignment 3 (HTML, CSS, and Beginner Sass)

* **Read these instructions repeatedly until you understand, then begin your project. If something is not clear, ask.**

## ❖・Before You Begin・❖

1. Log in to GitHub.
2. Fork this repo(sitory). See [this video](http://code-warrior.github.io/tutorials/git/github/forking-and-cloning-at-the-github-web-site/) on how to carry out this step and step `3`.
3. Clone your fork, using either the web site or the GitHub Desktop client.
4. Checkout your personalized branch, the one with your name and GitHub handle.

---

## ❖・Introduction・❖

This assignment is designed to get you to _a_) practice advanced HTML, _b_) author more advanced CSS, and _c_) to start working with Sass. You’ll do so by implementing a web page — pixel-by-pixel — of the follow mockup, which you’ll find in `comps/focus.jpg`.

![Image of focus.jpg](comps/focus.jpg)

---

## ❖・Preflight・❖

1. Like assignment 2, ensure _editorconfig_, _Stylelint_, and _HTMLHint_ are installed as CLI tools via Node and as plugins in VS code.
2. You’ll also need to install `stylelint-config-sass-guidelines`. Do so via the following command:

```bash
npm i -D stylelint postcss stylelint-config-sass-guidelines
```

**Note**: Ignore any errors in VS Code akin to _“The value of the href attribute ... must be relative.”_

---

## ❖・Assets・❖

All the image-related assets you’ll need are in the `img` folder. All the fonts are in the `fonts` folder.

### Fonts

The PSD comp in `comps/focus.psd` uses three typefaces: Pacifico, Raleway, and Helvetica Neue. The regular weight of Pacifico and the regular, light, and semibold versions of Raleway are include in the `fonts` directory. Helvetica Neue, however, isn’t included, because it isn’t open source. Employ Helvetica Neue in the `font-family` property and fall back to Helvetica.

* Pacifico Regular (normal): `fonts/Pacifico/Q_Z9mv4hySLTMoMjnk_rCXYhjbSpvc47ee6xR_80Hnw.woff2`
* Raleway Regular (normal): `fonts/Raleway/QAUlVt1jXOgQavlW5wEfxQLUuEpTyoUstqEm5AMlJo4.woff2`
* Raleway Light: `fonts/Raleway/-_Ctzj9b56b8RgXW8FAriQzyDMXhdD8sAj6OAJTFsBI.woff2`
* Raleway SemiBold: `fonts/Raleway/xkvoNo9fC8O2RDydKj12bwzyDMXhdD8sAj6OAJTFsBI.woff2`
* **Pacifico**: [`https://www.google.com/fonts/specimen/Pacifico`](https://www.google.com/fonts/specimen/Pacifico)
* **Raleway**: [`https://www.google.com/fonts/specimen/Raleway`](https://www.google.com/fonts/specimen/Raleway)

---

## ❖・Directions・❖

* Do **not** add any more files — of any type — to this project. Everything you need is included already.
* Do **not** alter any of the images in the `img` folder.
* Do **not** alter any of fonts in the `fonts` folder.
* You may **not** use any third-party HTML, CSS, or Sass libraries for this project. **All the code you include in this project _must_ be your own.**
* **Note** that the `style.css` file and the `css` folder you’ll need to create for this project will be ignored by default. This is fine, since I’ll build your CSS from the Sass code you submit.
* **No embedded or inline CSS is allowed.**
* Your HTML must be valid.
* Your Sass must also be valid.

---

## ❖・Grading・❖

| Item                                                     | Points |
|----------------------------------------------------------|:------:|
| _Project implements pixel-perfect translation of mockup_ | `25`   |
| _HTML is valid_                                          | `25`   |
| _CSS is valid_                                           | `25`   |
| _Code is neat and professional_                          | `25`   |

---

## ❖・Due・❖

Monday, 10 April 2023, by 9:45 AM.

---

## ❖・Submission・❖

You will need to issue a pull request back into the original repo, the one from which your fork was created for this project. See the **Issuing Pull Requests** section of [this site](http://code-warrior.github.io/tutorials/git/github/index.html) for help on how to submit your assignment.

**Note**: This assignment may *only* be submitted via GitHub. **No other form of submission will be accepted**.
