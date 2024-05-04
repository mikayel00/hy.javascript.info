# The Modern JavaScript Tutorial in Armenian

This repository hosts the Armenian translation of the Modern JavaScript Tutorial, published in [https://javascript.info](https://javascript.info).


**That's how you can contribute:**

- See the [Armenian Translate Progress](https://github.com/javascript-tutorial/am.javascript.info/issues/1) issue.
- Choose an unchecked article you'd like to translate.
- Add a comment with the article title to the issue, e.g. `An Introduction to JavaScript`.
    - Our bot will mark it in the issue, for everyone to know that you're translating it.
    - Your comment should contain only the title.
- Fork the repository, translate and send a PR when done.
    - PR title should match article title, the bot will write it's number into the issue.

Please kindly allow maintainers to review and merge or request changes in your translation.
   
If maintainers do not respond, or if you'd like to become a maintainer, write us at the [main repo](https://github.com/javascript-tutorial/en.javascript.info/issues/new).
    
**Let others know what you're translating, in message boards or chats in your language. Invite them to join!**

🎉 Thank you!

Something's wrong? A topic is missing? Explain it to people, add it as PR 👏

**You can edit the text in any editor.** The tutorial uses an enhanced "markdown" format, easy to grasp. And if you want to see how it looks on-site, there's a server to run the tutorial locally at <https://github.com/javascript-tutorial/server>.

The list of contributors is available at <https://javascript.info/about#contributors>.

## Structure

Every chapter, article, or task has its folder.

The folder is named like `N-url`, where `N` is a number for the sorting purposes and `URL` is the URL part with the title of the material.

The translated text is in `images.yml` file in the tutorial root.

The file format is YAML:
```yaml
image.svg:        # image file
  "hello world":  # English phrase
    text: "Hola mundo"  # translation
    position: "centre"  # "center" or "right", if needed to center or right-align the translation
```

## Running locally

You can run the tutorial server locally to see how the translation looks.

The server and install instructions are at <https://github.com/javascript-tutorial/server>. 
