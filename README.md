# Vue Card
---
A credit card UI module made with VUE.js
Check out the [Demo](https://andy19910102.github.io/VuejsCreditCardUI/)

## Install
---
Base on [Bootstrap](http://getbootstrap.com/) and [Vue.js 2.0](https://vuejs.org/).

## Usage
---
### Change card theme
---
![](https://github.com/andy19910102/VuejsCreditCardUI/blob/master/demoGif/vueCardDemoColorThemes.gif?raw=true)
---

To change or customize the card type you want, you can just change the class name on the section tag with the class "credit-card".

There are 5 default color theme is available:

1. primary
2. oliver
3. champagne
4. silver
5. black

---
Remember to add your new theme class name inside this the array variable when cutomized new theme.
```javascript
var cardTypes = ["primary", "oliver", "champagne", "silver", "black"];
```
### Card numbers detaction
---
![](https://github.com/andy19910102/VuejsCreditCardUI/blob/master/demoGif/vueCardDemoDetactCardType.gif?raw=true)

---

Auto card type detaction with Vue.js condition statements. 

### Auto flip
---
![](https://github.com/andy19910102/VuejsCreditCardUI/blob/master/demoGif/vueCardDemoAutoFlip.gif?raw=true)
---
Pure CSS auto flip UI when input the data of CVV. 


### Binding data
---
The input text area below the credit card, each of them has a v-model attributes inside the tag, which are using to binding the data via VUE.js.

## License
---
Made by [Andy Huang](https://github.com/andy19910102) in Kyosei.ai@ 2016 :sailboat: 