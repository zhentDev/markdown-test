<!-- HEADINGS -->

# My Title
## My Title h2
### My Title h3
#### My Title h4
##### My Title h5
###### My Title h6

<!-- italic -->
this is an *italic* text

<!-- strong -->
this is an **strong** text

<!-- strikethrough -->
this is an ~~strikethrough~~ text

<!-- UL -->
* apple
    * subapple
* orange
    * suborange
* ect

<!-- OL -->
1. fisrt
    1. first point fisrt
2. second
.3 third

[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com, "Custom title")

> this is a quote

---
___

`console.log("Hello World")`

```javascript
const mongoose = require("mongoose");

mongoose.set("useFindAndModify", false);
mongoose.connect("mongodb://localhost/node-notes-db", {
    useCreateIndex: true,
    userNewUrlParser: true
}).
    then(db => console.log("DB is connect"))
    .catch(err => console.error(err));
```

```python
print("hello World")
```

```html
<h1>"hello World"</h1>
```

| Tables         | Are         | Cool  |
|----------------|:-----------:|------:|
| col 3 is       |right-alinged| $1600 |
| col 2 is       |centered     | $12   |
| zebre stripes  | are neat    | $1    |

![visual studio code logo](https://user-images.githubusercontent.com/410792/31419678-a45ed408-ae6f-11e7-8e06-282c9d668472.png "VSCode logo")

<!-- GITHUB MARKDOWN -->
* [X] Task 1 
* [ ] Task 2 
* [X] Task 3 
* [ ] Task 4 
* [X] Task 5 

@zhentinela-ia 😈👍
