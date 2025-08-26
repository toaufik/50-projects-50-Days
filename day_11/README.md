# 🔑 Event KeyCodes

A tiny web app that shows the Key '(event.key)', Key Code '(event.keyCode)', and Code '(event.code)' for any key you press, built using **HTML**, **CSS**, and **Vanilla JavaScript**.


## 🚀 How it works
- The app starts with a welcome state: “Press any key to get the KeyCode”.
- On the first key press, the welcome message fades out.
- Three cards appear, showing:
    - Key — e.g., 'a'
    - Key Code — e.g., '65'
    - Code — e.g., 'KeyA'
- Example
    - You press 'a'
    - Welcome message disappears
    - Cards display: Key: 'a', Key Code: '65', Code: 'KeyA'

---

## 🧠 Concepts Used

- Global 'keydown' listener on 'window'
- Reads the pressed key from the event object
- Renders values into three UI cards: Key, Key Code, Code


---

## 🔗 Live Link

<a href="https://toaufik.github.io/50-projects-50-Days/day_11/index.html" target="_blank">Event KeyCodes</a>


## 📁 Project Structure

```

day_11/
├── index.html              
├── README.md               
├── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── img/           # Image assets used in panels (If any)

```

✅ **Day 11 of 50 Days 50 Projects -  HTML, CSS & JavaScript**

Inspired by the [50 Projects In 50 Days](https://www.udemy.com/course/50-projects-50-days/) challenge by Brad Traversy.
