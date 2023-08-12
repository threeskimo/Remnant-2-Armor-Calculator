# Remnant II: Armor Calculator
A `.html` file that helps calculate the highest armor value you can achieve at a specific weight in Remnant II. Calculations are performed in javascript.

>**NOTE:** This calculator currently only contains the Armor sets that are available at launch. If I'm still playing Remnant II at the time of any additional armor sets being released, I will update the calculator.

## Why?

If you are familiar with how Remnant II's armor system works, weight is directly related to your character’s Dodge and Stamina. Each armor has a certain Weight number, and you will receive a stamina cost penalty if the total Weight value exceeds a certain threshold. Generally, you want to keep your character as light as possible without sacrificing your defense. The thresholds are as follows:

* ![#72c2dc](https://placehold.co/10x10/72c2dc/72c2dc.png) **Light:** <=25 – Fast Dodge. No Stamina Cost Penalty.
* ![#71b465](https://placehold.co/10x10/71b465/71b465.png) **Normal:** 26-50 – Normal Dodge. 25% Stamina Cost Penalty.
* ![#c9c96b](https://placehold.co/10x10/c9c96b/c9c96b.png) **Heavy:** 51-75 – Slow Dodge. 50% Stamina Cost Penalty.
* ![#f24a45](https://placehold.co/10x10/f24a45/f24a45.png) **Ultra:** >=76 – FLOP. 75% Stamina Cost Penalty.

This calculator determines the best armor pieces (head, body, legs, gloves) to use to recieve the highest armor value possible at a given weight. The calculator does not take into account armor resistances such as bleed, fire, shock, etc.

## Usage
1. Download the `remnant-armor-calculator.html` file, which you can run locally on your machine in a web browser. 
2. Enter a "Weight" target in the input field and click "Update" 
3. The tool should show sets of armors (head, body, legs, gloves) that will get you the highest armor value possible for the weight specified.

## Images
![Preview image](https://github.com/threeskimo/remnant-2-armor-weight-calculator/blob/main/preview.png?raw=true)
