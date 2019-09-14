## Mikhail Shcheglakov

#### My contacts

- Phone: +7-910-123-45-67-89
- E-mail: m.shcheglakov@gmail.com
- [GitHub](https://github.com/madmike85)

### About me

I am not so young, but inspired self-taught developer. Who decided to switch from chemical industry to web developmet at hte age of 34.

### My skils

- **C#**
- **Javascript (includes ES6)**
- **HTML**
- **CSS**
- **Git**
- **LESS**
- **WordPress**
- **Angular**

### Code examples

- Javascript

```javaspript
const clock = document.querySelector('#clock');
const hexColor = document.querySelector('#hex-color');

function hexClock() {
    const time = new Date();
    let hours = time.getHours().toString();
    let minutes = time.getMinutes().toString();
    let seconds = time.getSeconds().toString();

    if (hours.length < 2) {
        hours = '0' + hours;
    }

    if (minutes.length < 2) {
        minutes = '0' + minutes;
    }

    if (seconds.length < 2) {
        seconds = '0' + seconds;
    }

    let clockStr = hours + ':' + minutes + ':' + seconds;
    let hexColorStr = '#' + hours + minutes + seconds;

    clock.textContent = clockStr;
    hexColor.textContent = hexColorStr;

    document.body.style.backgroundColor = hexColorStr;
}

hexClock();
setInterval(hexClock, 1000);
```

- CSS

```css
.nav {
  z-index: 1;
  position: fixed;
  width: 100%;
  height: 60px;
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
}

.nav.scrolled {
  background-color: #fff !important;
  transition: background-color 300ms linear;
}

.menu-open {
  position: absolute;
  line-height: 60px;
  left: 1.4em;
  cursor: pointer;
}

.brand span a {
  position: absolute;
  line-height: 60px;
  left: 50%;
  transform: translateX(-50%);
  text-transform: uppercase;
  font-size: 14px;
  font-weight: 300;
  letter-spacing: 4px;
}

.brand a:hover {
  text-decoration: none;
}

.cart {
  position: absolute;
  line-height: 60px;
  right: 1.4em;
  font-weight: 300;
  cursor: pointer;
}
```

### My Experience

I start freelancing half a year ago. Currently I am working on the website for a University in Uganda.

You could also take a look at my other project in my [GitHub](https://github.com/madmike85) account.

### Education

I am a salf-tought developer. For my education I use following resources:

- YouTube
- Udemy
- FreecodeCamp
- Udacity

### English

Fluent. I have a interpreter diploma.
