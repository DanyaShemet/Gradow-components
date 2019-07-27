
 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradow-btn@1.0.7/gradow-btn.min.css"/>
<h1 align="center">

 <br> Gradow-components.css <br>
</h1>

<div class="highlight highlight-source-shell">
<pre>
<div align="center"><strong >Demo and documentation</strong></div>
<div align="center"><a align="center" href="https://danyashemet.github.io/Gradow-components/">https://danyashemet.github.io/Gradow-components/</a></div>
</pre>
</div>


# Gradow-button

**It's library of custom buttons with cool shadow-effect**

## Features
* Basic
  - **Border-radius**   - 
  - **Colors** - *Primary*, *Accept *, *Info*, *Secondary *, *Danger* , *Light  *, *Dark * 
  - **Animations** 
 * Responsive
 * No JavaScript
 * State - *Focus*, *Hover*
 * Supports frameworks - *Bootstrap*, *Foundation*, *Sematic UI*, *Bulma*, ...
 * Supports all modern browsers, including mobile devices
 * Print friendly

## Installation
  
**Npm module**

```sh
  >npm i gradow-btn 
```

- **Manual download** ( [`Github`](https://github.com/DanyaShemet/Gradow-components.git) )

```html
<link rel="stylesheet" href="<PATH>/graddow-btn/graddow-btn.min.css"/>
```
`<PATH>` is where the library is downloaded.

Add `graddow-btn.min.css` in your html

 **CDN** 
```html
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradow-btn@1.0.7/gradow-btn.min.css"/>
```

### Usage

Gradow button comes with many styles,

| Class name      | Description                             |
| :----------     | :-----------------------                |
| `s-btn`         | Basic style *required                   |
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
     <button class="s-btn b-primary-simple r-20 w-170 h-30">Send</button>
  </div>
```

<div align="center">
 <button class="s-btn b-primary-simple r-20 w-170 h-30" style="color: #fff">Send</button>
</div>


<div align="center"><strong >---</strong></div>

  - Accept button

```html
  <div class="">
     <button class="s-btn b-accept-simple r-10 h-30">Accept</button>
  </div>
```
<div align="center">
     <button class="s-btn b-accept-simple r-10 h-30" style="color: #fff">Accept</button>
  </div>

<div align="center"><strong >---</strong></div>

Buttons has extra classes for stylization size `r-30` `w-200` `h50`
You can combine them.

```html
  <div class="">
     <button class="s-btn b-primary-simple r-30 w-180 h-40" >Send</button>
  </div>
```
<div align="center"><strong >---</strong></div>


### List of all buttons

  
| Primary                   | Description                                                          |
| :----------               | :------------------------------------------------------------------- |
| `b-primary-simple`        | <button class="s-btn b-primary-simple r-0 custom">Send</button>      |
| `b-primary-dark`          | <button class="s-btn b-primary-dark r-5 w-180">Send</button>         |
| `b-primary-foggy`         | <button class="s-btn b-primary-foggy r-15 w-100">Send</button>       |
| `b-primary-common`        | <button class="s-btn b-primary-common r-20 w-230 h-70">Send</button> |
| `b-primary-mysterious`    | <button class="s-btn b-primary-mysterious r-25">Send</button>     |
| `b-primary-rainy`         | <button class="s-btn b-primary-rainy r-25">Send</button>             |
| `b-primary-rainy-ver_two` | <button class="s-btn b-primary-rainy-ver_two r-25">Send</button>     |


### Browser support

Works in all modern browsers.

`Chrome >= 26` `Firefox >= 16` `Safari >= 6.1` `Opera >= 15` `IE >= 9`

## Authors

**Shemet Daniil** - [DanyaShemet](https://github.com/DanyaShemet)


    

