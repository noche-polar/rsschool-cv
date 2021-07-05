# Kastsiuchyk Alena
📍 Minsk, Belarus

Tel.: + 375 29 141 17 51  
E-mail: kastiuchik.elena@gmail.com

#### 🤓 About me:  
I haven't had the experience in commercial developing yet, but I'm always strive to discover and learn new things in front-end development. That's why I would like to attend the Rolling Scopes School courses.

#### 🔧 Skills:  
* HTML
* CSS
* JS (basic)
* Gulp
* Sass

#### 💻 How I code:

```html
<section class="pump-composit">
  <h2 class="pump-composit__h2">
    Из чего состоит инсулиновая помпа?
  </h2>
  <img class="pump-composit__pump-scheme" src="../img/pump_composit.png" alt="Схема инсулиновой помпы" height="350px">
  <ul class="pump-composit__list">
    <li class="pump-composit__list-item pump-composit__list-item--col-left">
      <span class="pump-composit__list-item-title">
        1. Инсулиновая помпа
      </span>
      Небольшое электронное устройство с ЖК-экраном, кнопками для программирования и отсеком для батарейки
    </li>
    <li class="pump-composit__list-item pump-composit__list-item--col-left">
      <span class="pump-composit__list-item-title">
        2. Резервуар
      </span>
      Пластиковый картридж для инсулина, который вводится в специальный отсек инсулиновой помпы.
    </li>
    <li class="pump-composit__list-item pump-composit__list-item--col-right">
      <span class="pump-composit__list-item-title">
        3. Инфузионный набор
      </span>
      Состоит из тонкой трубочки и инфузионного катетера.
      Из резервуара инсулин по трубке поступает в катетер (канюлю), расположенную под кожей. Трубочку можно отсоединять от катетера по мере необходимости (например, во время плавания, душа или занятий спортом).
    </li>
    <li class="pump-composit__list-item pump-composit__list-item--col-right">
      <span class="pump-composit__list-item-title">
        4. Трансмиттер
      </span>
      Дополнительное устройство для использования функции непрерывного мониторинга глюкозы (НМГ)
    </li>
  </ul>
</section>
```

```css
.pump-composit {
    position: relative;

    background-color: #1C85C7;

    padding: 41px 15px 36px 16px;
}

.pump-composit__h2 {
    color: #ffffff;

    font-size: 25px;
    line-height: 30px;
    text-transform: uppercase;
    text-align: center;

    margin-bottom: 45px;
}

.pump-composit__pump-scheme {
    display: block;
    margin: 0 auto 28px;
}

.pump-composit__list {
    text-align: center;
}

.pump-composit__list-item {
    color: #ffffff;

    font-size: 14px;
    line-height: 20px;
}

.pump-composit__list-item:not(:last-child) {
    margin-bottom: 31px;
}

.pump-composit__list-item-title {
    display: block;
    color: #F7A800;

    font-family: 'Montserrat';
    font-size: 20px;
    line-height: 24px;
    font-weight: 700;

    margin-bottom: 10px;
}

@media (min-width: 1400px) {
    .pump-composit {
        padding: 63px 45px 82px;
    }

    .pump-composit__h2 {
        font-size: 32px;
        line-height: 38px;

        margin-bottom: 75px;
    }

    .pump-composit__pump-scheme {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -38%);

        height: 375px;
        margin-bottom: 0;
    }

    .pump-composit__list {
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        height: 375px;
        justify-content: space-around;
    }

    .pump-composit__list-item--col-left {
        align-self: flex-start;
        text-align: right;
    }

    .pump-composit__list-item--col-right {
        align-self: flex-end;
        text-align: left;
    }
    
    .pump-composit__list-item-title {
        font-size: 24px;
        line-height: 29px;
    }

    .pump-composit__list-item {
        max-width: 370px;
        font-size: 18px;
        line-height: 25px;
    }

    .pump-composit__list-item:not(:last-child) {
        margin-bottom: 0;
    }
}
```
  
```js
function distinct(a) {
  if (a.length == 1) {return a};
  
  for (let i = a.length - 1; i >= 0; i--) {
    let num = a[i]; 
    a.splice(i, 1); 
    
    let count = 0;
    for (let j = a.length - 1; j >= 0; j--) {
      if (a.includes(num)) {count++;}
    }
    if (count == 0) {a.push(num);}
  }
  
  return a.reverse();
}
```

#### 📚 Experience & education:  
HTML Academy courses and self-education

#### 🇬🇧 🇺🇸 English:  
B1-B2 (self-education, I worked as a guide in museum with excursions in English as an option)
