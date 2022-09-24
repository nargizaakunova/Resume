# Nargiza Akunova

#### Contacts

- **Mobile:** +48-883-178-954
- **E-mail:** [nargizaakun@gmail.com](mailto:nargizaakun@gmail.com)
- **Telegram:** [nargizaakunova](https://t.me/nargizaakunova)
- **Discord:** @Nargiza Akunova#8502

#### Summary

> I am an aspiring Junior JavaScript Front-End Developer with a load of determination and strong eager to learn. I am a self-learner at home and have only taken online courses. I gain the most satisfaction from work and experience when I am able to develop and meet organization's goals and customers' expectations. I enjoy exploring solutions and writing quality software, preferably leveraging modern programming languages, agile development practices, and mastering skills.

#### Skills

Good knowledge of **HTML**, **CSS**, **JavaScript**, and **Git** & **GitHub**, acquaintance with **SASS**, **React**, and **TypeScript**. Currently mastering **React** and **TypeScript**.

#### Code Examples

```JS
const restaurant = {
  names: 'Classico Italiano',
  location: 'Via Angelo Tavanti 23, Firenze, Italy',
  categories: ['Italian', 'Pizzeria', 'Vegetarian', 'Organic'],
  starterMenu: ['Focaccia', 'Bruschetta', 'Garlic Bread', 'Caprese Salad'],
  mainMenu: ['Pizza', 'Pasta', 'Risotto'],

  openingHours: {
    thu: {
      open: 12,
      close: 22,
    },
    fri: {
      open: 11,
      close: 23,
    },
    sat: {
      open: 0, // Open 24 hours
      close: 24,
    },
  },
  order: function (starterIndex, mainIndex) {
    return [this.starterMenu[starterIndex], this.mainMenu[mainIndex]]; // Returns an array
  },
  orderDelivery: function ({
    starterIndex = 1,
    mainIndex = 0,
    time = '20:00',
    address,
  }) {
    console.log(
      `Order received! ${this.starterMenu[starterIndex]} and ${this.mainMenu[mainIndex]} will be delivered to ${address} at ${time}!`
    );
  },
  orderPasta: function (ing1, ing2, ing3) {
    console.log(`Here is your delicious pasta with ${ing1}, ${ing2}, ${ing3}.`);
  },
  orderPizza: function (mainIngredient, ...otherIngredients) {
    console.log(
      `You have a pizza with the main ingredient of ${mainIngredient}, and the other components to it are ${otherIngredients.join(
        ', '
      )}. Enjoy your food!`
    );
  },
};
```

#### Experience

A little bit of practicing in self-made projects based on courses I have taken, primarily front-end and projects at Epam's Rolling Scopes Online School.

##### _Examples of my works:_

- [RS School - Shelter - Responsive Website](https://nargizaakunova.github.io/shelter/pages/main/index.html)
- [RS School - Bookshop - JS](https://nargizaakunova.github.io/bookshop/)
- [CV](https://nargizaakunova.github.io/CSS-My-Site/)
- [TinDog website](https://nargizaakunova.github.io/tindog-website/)

#### Education

**Programming Courses:**
`In process` React - The Complete Guide (incl Hooks, React Router, Redux) _by Maximilian Schwarzmüller_

`2022` Rolling Scopes School JS FE (Stage 0 and 1 completed + 1 technical interview)

`2022` The Complete JavaScript Course 2021: From Zero to Expert! _by Jonas Schmedtmann_

`2022` Build Responsive Real-World Websites with HTML and CSS _by Jonas Schmedtmann_

`2022` The Git & Github Bootcamp _by Colt Steele_

**Previous Education:**

`2018-20`
**European University of Lefke** International Relations MA, Cyprus

`2011-18`
**Kyrgyz National Conservatory** Diploma in Performing Arts, Violin, and Orchestra

#### English

C1, IELTS test (July 27, 2018)

**_Other Languages_**: Russian (proficient), Kyrgyz (native), Turkish(B1).
