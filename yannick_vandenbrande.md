# 👁️ Yannick Van den Brande's Portfolio 👁️

![peepoChat Image](https://cdn.7tv.app/emote/63438a743d1bc89e0ff9e400/4x.webp)

[GitHub Pages](https://nanioy.github.io/)

## Main Repository
- [GitHub Repository](https://github.com/NANIOY/DEV5-lab-portfolio)

## Projects

| **Name** | **Description**                     | **GitHub Repo**                                                                                     | **Codesandbox**                                  |
| -------- | ----------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| Lab 1    | Voice controlled music player       | [Repo](https://github.com/Nvnchi/lab1)                                                              | [Sandbox](https://l4x4v6.csb.app/)               |
| Lab 2    | Interactive random island generator | [Repo](https://github.com/NANIOY/lab2)                                                              | [Sandbox](https://jc48r3.csb.app/)               |
| Lab 3    | Weather ad with quote               | [Repo](https://github.com/NANIOY/lab3)                                                              | [Vercel](https://lab3-eosin-iota.vercel.app/)    |
| Lab 4    | Messages API                        | [Repo](https://github.com/NANIOY/lab4)                                                              | [CodePen](https://codepen.io/NanioY/pen/mdvEzEN) |
| Lab 5    | TikTok chat app                     | [Repo](https://github.com/NANIOY/lab5)                                                              | [Vercel](https://lab5-ten.vercel.app/)           |
| Lab 6    | Scoreboard WebSocket                | [Front-end](https://github.com/NANIOY/lab6-FRONT) / [Back-end](https://github.com/NANIOY/lab6-BACK) | [Vercel](https://lab6-front.vercel.app/)         |

![lab6](https://github.com/NANIOY/DEV5-lab-portfolio/blob/main/lab6-gif.gif?raw=true)

## An interesting new feature of ES2018
Object Spread is a feature that simplifies working with objects. It allows you to create new objects by spreading the properties and values of an existing object. This enables you to clone objects, create variations with modified properties, or merge multiple objects together effortlessly.

With Object Spread:
- You can duplicate an object's properties and values into a new object, effectively creating a shallow copy.
- You can easily add new properties or override existing ones within the new object.
- It provides a concise and clear syntax for object manipulation, enhancing code readability.

Object Spread is useful for scenarios where you need to manage and transform objects while preserving the integrity of the original data. It's also useful for maintaining clean and maintainable code.

### [An example of this is from JavaScript Tutorial](https://www.javascripttutorial.net/es-next/javascript-object-spread/)

    let rgb = [ 'red', 'green', 'blue' ];
    let cmyk = ['cyan', 'magenta', 'yellow', 'black'];
    let merge = [...rgb, ...cmyk];
    console.log(merge);
#### Output
    [ 'red', 'green', 'blue', 'cyan', 'magenta', 'yellow', 'black' ]

### [An example of this is from W3 Schools](https://www.w3schools.com/react/react_es6_spread.asp)

    const myVehicle = {
    brand: 'Ford',
    model: 'Mustang',
    color: 'red'
    }

    const updateMyVehicle = {
    type: 'car',
    year: 2021, 
    color: 'yellow'
    }

    const myUpdatedVehicle = {...myVehicle, ...updateMyVehicle}
#### Output
    { brand: "Ford", model: "Mustang", color: "yellow", type: "car", year: 2021 }


![peepoChat Image](https://cdn.7tv.app/emote/62ec1cfdd2e11183867d8c3b/4x.webp)
