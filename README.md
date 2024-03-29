
 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradow-btn@1.1.0/gradow-btn.min.css"/>
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
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gradow-btn@1.1.0/gradow-btn.min.css"/>
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

  **Primary** 
  
| ClassList                       | Example                                                                               |
| :----------                     | :-------------------------------------------------------------------                        |
| `b-primary-simple s-btn`        | <button class="s-btn b-primary-simple" style="color: #fff; margin: 10px;">Send</button>      |
| `b-primary-dark s-btn`          | <button class="s-btn b-primary-dark" style="color: #fff; margin: 10px;">Send</button>      |
| `b-primary-foggy s-btn`         | <button class="s-btn b-primary-foggy" style="color: #fff; margin: 10px;">Send</button>      |
| `b-primary-common s-btn`        | <button class="s-btn b-primary-common" style="color: #fff; margin: 10px;">Send</button>     |
| `b-primary-mysterious s-btn`    | <button class="s-btn b-primary-mysterious" style="color: #fff; margin: 10px;">Send</button>  |
| `b-primary-rainy s-btn`         | <button class="s-btn b-primary-rainy" style="color: #fff; margin: 10px;">Send</button>      |
| `b-primary-rainy-ver_two s-btn` | <button class="s-btn b-primary-rainy-ver_two" style="color: #fff; margin: 10px;">Send</button>|

<div align="center"><strong >---</strong></div>

  **Accept** 
  
| ClassList                        | Example                                                                               |
| :----------                      | :-------------------------------------------------------------------                        |
| `b-accept-simple s-btn`          | <button class="s-btn b-accept-simple" style="color: #fff; margin: 10px;">Confirm</button>      |
| `b-accept-dark s-btn`            | <button class="s-btn b-accept-dark " style="color: #fff; margin: 10px;">Confirm</button>      |
| `b-accept-foggy s-btn`           | <button class="s-btn b-accept-foggy" style="color: #fff;margin: 10px;">Confirm</button>      |
| `b-accept-common s-btn`          | <button class="s-btn b-accept-common " style="color: #fff; margin: 10px;">Confirm</button>     |
| `b-accept-mysterious s-btn`      | <button class="s-btn b-accept-mysterious " style="color: #fff; margin: 10px;">Confirm</button>  |
| `b-accept-smile s-btn`           | <button class="s-btn b-accept-smile " style="color: #fff; margin: 10px;">Confirm</button>      |
| `b-accept-swim s-btn`            | <button class="s-btn b-accept-swim " style="color: #fff; margin: 10px;">Confirm</button>|

<div align="center"><strong >---</strong></div>

  **Info** 
  
| ClassList                        | Example                                                                               |
| :----------                      | :-------------------------------------------------------------------                        |
| `b-info-simple s-btn`            | <button class="s-btn b-info-simple" style="color: #000; margin: 10px;">Forward</button>      |
| `b-info-dark s-btn`              | <button class="s-btn b-info-dark " style="color: #000; margin: 10px;">Forward</button>      |
| `b-info-foggy s-btn`             | <button class="s-btn b-info-foggy" style="color: #000; margin: 10px;">Forward</button>      |
| `b-info-common s-btn`            | <button class="s-btn b-info-common " style="color: #000; margin: 10px;">Forward</button>     |
| `b-info-mysterious s-btn`        | <button class="s-btn b-info-mysterious " style="color: #000; margin: 10px;">Forward</button>  |

<div align="center"><strong >---</strong></div>

  **Secondary** 
  
| ClassList                          | Example                                                                               |
| :----------                        | :-------------------------------------------------------------------                        |
| `b-second-simple s-btn`            | <button class="s-btn b-second-simple" style="color: #000; margin: 10px;">Registration</button>      |
| `b-second-dark s-btn`              | <button class="s-btn b-second-dark " style="color: #000; margin: 10px;">Registration</button>      |
| `b-second-light s-btn`             | <button class="s-btn b-second-light" style="color: #000; margin: 10px;">Registration</button>      |
| `b-second-mysterious s-btn`        | <button class="s-btn b-second-mysterious " style="color: #000; margin: 10px;">Registration</button>     |
| `b-second-smile s-btn`             | <button class="s-btn b-second-smile" style="color: #000; margin: 10px;">Registration</button>  |

<div align="center"><strong >---</strong></div>

  **Danger** 
  
| ClassList                          | Example                                                                               |
| :----------                        | :-------------------------------------------------------------------                        |
| `b-danger-brightly s-btn`          | <button class="s-btn b-danger-brightly" style="color: #000; margin: 10px;">Buy right now</button>      |
| `b-danger-cta s-btn`               | <button class="s-btn b-danger-cta " style="color: #000; margin: 10px;">Buy right now</button>      |
| `b-danger-pretty s-btn`            | <button class="s-btn b-danger-pretty" style="color: #000; margin: 10px;">Buy right now</button>      |
| `b-danger-dark s-btn`              | <button class="s-btn b-danger-dark " style="color: #000; margin: 10px;">Buy right now</button>     |
| `b-danger-smile s-btn`             | <button class="s-btn b-danger-smile" style="color: #000; margin: 10px;">Buy right now</button>  |
| `b-danger-mysterious s-btn`        | <button class="s-btn b-danger-mysterious " style="color: #000; margin: 10px;">Buy right now</button>     |
| `b-danger-light s-btn`             | <button class="s-btn b-danger-light" style="color: #000; margin: 10px;">Buy right now</button>  |

<div align="center"><strong >---</strong></div>

  **Light** 
  
| ClassList                          | Example                                                                               |
| :----------                        | :-------------------------------------------------------------------                        |
| `b-light-sun s-btn`                | <button class="s-btn b-light-sun" style="color: #000; margin: 10px;">Light text</button>      |
| `b-light-sky s-btn`                | <button class="s-btn b-light-sky " style="color: #000; margin: 10px;">Light text</button>      |
| `b-light-green s-btn`              | <button class="s-btn b-light-green" style="color: #000; margin: 10px;">Light text</button>      |
| `b-light-pinkLine s-btn`           | <button class="s-btn b-light-pinkLine " style="color: #000; margin: 10px;">Light text</button>     |

<div align="center"><strong >---</strong></div>

  **Dark** 
  
| ClassList                          | Example                                                                               |
| :----------                        | :-------------------------------------------------------------------                        |
| `b-dark-green s-btn`               | <button class="s-btn b-dark-green" style="color: #fff; margin: 10px;">Light text</button>      |
| `b-dark-purple s-btn`              | <button class="s-btn b-dark-purple " style="color: #fff; margin: 10px;">Light text</button>      |
| `b-dark-burgundy s-btn`            | <button class="s-btn b-dark-burgundy" style="color: #fff; margin: 10px;">Light text</button>      |
| `b-dark-blue s-btn`                | <button class="s-btn b-dark-blue " style="color: #fff; margin: 10px;">Light text</button>     |
| `b-dark-grey s-btn`                | <button class="s-btn b-dark-grey " style="color: #fff; margin: 10px;">Light text</button>     |



### Browser support

Works in all modern browsers.

`Chrome >= 26` `Firefox >= 16` `Safari >= 6.1` `Opera >= 15` `IE >= 9`

## Authors

**Shemet Daniil** - [DanyaShemet](https://github.com/DanyaShemet)

<div class="highlight highlight-source-shell">
<pre>
<div align="center"><strong >Wishing you great use.</strong></div>
<div align="center">I will listen to the criticism and wishes <a align="center" href="mailto:shemetwork@gmail.com">here</a></div>
</pre>
</div>
