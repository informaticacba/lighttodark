# Light to Dark 🌓

A lightweight extension to simplify your work in a single tap. We also help you to organise your shared styles in better order. 

## How does it help you?

1. Create a dark mode in a single tap
2. You will get the organised shared styles for both Light and Dark mode
3. Easy to use and lightweight
4. We also help you to set up the project by **Boilerplate** option

[light to dark branding_.mp4](Light%20to%20Dark%20%F0%9F%8C%93%20bb52b16ff11c4a93a0cb37062f8f4513/light_to_dark_branding_.mp4)

## Getting Started

To build the dark mode without any error, you need to follow the following guidelines.

**Step 1:**

Create a new document

**Step 2:** 

Create a page named "**`Light`**" (case sensitive). 

All the screens from the page **`Light`** will be ****generated to dark mode.

**Step 3:** 

Create the shared style for both **`light`** and **`dark`** (note: shared style naming must be prefixed with **`dark/{your style}`** or **`light/{your style}`**). Check the example for shared style naming

![Screenshot 2021-11-09 at 10.32.07 AM.png](Light%20to%20Dark%20%F0%9F%8C%93%20bb52b16ff11c4a93a0cb37062f8f4513/Screenshot_2021-11-09_at_10.32.07_AM.png)

<aside>
💡 **The** s**hared style should need to follow below**

Light:
`light/primary/border`

Dark:
`dark/primary/border`

If you are creating a style for the light you also need to define dark mode otherwise it will throw an error:
`light/{ YOUR - STYLE - GOES - HERE }
 dark/{ YOUR - STYLE - GOES - HERE }`

</aside>

**Step 4:**

Apply every layer with the shared style. 

<aside>
💡 On the page Light, you need to apply the style for the `light/{YOUR STYLE}` otherwise it will throw an error.

</aside>

**Step 5:** 

Run `Plugins > Light to Dark 🌓 > Convert to Dark mode`   or 

simply press `ctrl + shift + c`

---

## Using Boilerplate

We made your work simpler by using boilerplate

1. We will create a page with the name **Light**
2. We will also create a few shared styles for both light and dark modes. You can customise any time

---

## FAQ?

- **Error: You have applied Dark shared style in the light version**
    
    This alert will be thrown, if you are using any of the **dark styles inside** the **page Light**
    
- **Error: No Dark style found for this shared style**
    
    This alert will be thrown, when you have not created the dark style for the light
    
    For example: if you have the layer style **`light/primary/background`**  and not in the dark style
