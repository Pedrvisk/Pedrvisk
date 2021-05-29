# <a href="https://github.com/Pedrvisk"><img width="25px" src="https://simpleicons.org/icons/github.svg" alt="Github"/></a>  Welcome to my Github! <img src="https://komarev.com/ghpvc/?username=Pedrvisk" alt="Pedrovisk" />

<img align="right" alt="Snownan" height="200px" src="https://acegif.com/wp-content/gifs/snowman-6.gif" />

```js
function Learn({
    Start = Boolean
}) {
    let Learn = {
        languages: {
            learning: [Javascript, Html, Css],
            interests: [Java, Lua, Python, C++]
        },
        databases: {
            learning: [Firebase, Sqlite3],
            interests: [DynamoDB, PostgreSQL, MongoDB]
        },
        ide: [Visual Studio Code]
    }

    if (Start && Learn) {
        let Dev = new Developer('Pedrvisk');
        if (Dev.OpenIde()) {
            Dev.StartLearn();
        };
    }
}

setTimeout(async () => await Learn({ Start: true }), ∞)
```

---
