# Gradow-button

**It's library of custom buttons with cool shadow-effect**

## Getting Started
  
**Npm module**

```sh
  >npm i gradow-btn 
```

- **Manual download** ( [`Github`](https://github.com/DanyaShemet/Gradow-components.git) )

```html
<link rel="stylesheet" href="<PATH>/graddow-btn/graddow-btn.min.css"/>
```
`<PATH>` is where the library is downloaded.

Add `pretty-checkbox.min.css` in your html

 **CDN** 
```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradow-btn@1.0.3/gradow-btn.min.css"/>
```
## Features


### Usage

Gradow button comes with many styles,

| Class name      | Description                             |
| :----------     | :-----------------------                |
| `s-btn`         | Basic style                             |
| `b-primary`     | Add primary-styles(blue) for button     |
| `b-accept`      | Add primary-styles(green) for button    |
| `b-danger`      | Add primary-styles(red) for button      |
| `b-info`        | Add primary-styles(yellow) for button   |
| `b-secondary`   | Add primary-styles(grey) for button     |
| `b-light`       | Add primary-styles(light) for button    |
| `b-dark`        | Add primary-styles(dark) for button     |
| `r-{number}`    | Sets the radius of the button           |
| `w-{number}`    | Sets the width of the button            |
| `h-{number}`    | Sets the height of the button           |


**Example**

  - Primary button

```html
  <div class="">
     <button class="s-btn b-primary-simple">Send</button>
  </div>
```

Buttons has extra classes for stylization size `r-30` `w-200` `h50`
You can combine them.

```html
  <div class="">
     <button class="s-btn b-primary-simple r-30 w-180 h-40">Send</button>
  </div>
```


## Authors

**Shemet Daniil** - [DanyaShemet](https://github.com/DanyaShemet)
