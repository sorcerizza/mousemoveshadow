Javascript Mouse Move Shadow
======
Vanilla (**JavaScript**)-only


## Synopsis

Just a basicMouse Move Shadow that I wrote using vanilla **JavaScript** so there's not much to it.

## Code Example

```
function shadow(e) {
    const { offsetWidth: width, offsetHeight: height } = hero;
    let { offsetX: x, offsetY: y } = e;

    if (this !== e.target) {
      x = x + e.target.offsetLeft;
      y = y + e.target.offsetTop;
    }
```

## Motivation

Learning and enforcing good structural and practical **strategies** for JavaScript development.

### Directory Layout

```

│   └──style.css       # Basic CSS stylesheet
│   └── main.js          # Main app source
│── index.html           # Main entry point
└── README.md            # This file

```

## Usage

Just for fun.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

0.1.0 Finalized the example

## Tests

Basic non-automated manual browser test aka no test :P

## Contributors

Standing on the shoulders of all the giants before me.

## Contact
#### sorcererizza
* E-mail: izzaannsamax@gmail.com

