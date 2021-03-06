| [Custom Range Slider](https://github.com/lana-20/50Projects50Days/tree/main/CustomRangeSlider) | [Live Demo](https://lana-20.github.io/custom-range-slider/) |
 |----|----|
 
I am building a custom range slider. In HTML5, there is an input type of range, but you can't really style it.
You have to tell the browser you don't want it to show, and style the track and the thumb on your own.
There is quite a bit of CSS. I have to pay attention to which browser it's being shown on, because it's different in every browser.
I have a -webkit prefix for Chrome and Safari, -moz - for Mozilla Firefox, -ms - for Miscrosoft IE*.
Then I am adding JavaScript for this label, so that it will show whatever the value is from 0 to 100.
The input label is positioned absolute, so it's going to calculate the left value to move along with the thumb.
It is a nice little widget you can use in your applications and your UIs.

*Microsoft announced deprecation of IE11 support in Microsoft 365 apps and services, with the removal date set for August 17, 2021
https://docs.microsoft.com/en-us/lifecycle/announcements/m365-ie11-microsoft-edge-legacy.
