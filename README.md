# K12-Chemistry-S2_SY2223

K12 - Chemistry Lessons and Formulas

## 1: States of Matter

### 1.05  Gay-Lussac's Law

* 1802
Joseph-Louis Gay-Lussac publishes both Gay-Lussac’s law, which describes the relationship between a gas’s temperature and pressure, and Charles’s law.

```
// Pressure = constant * temperature
P = k * T
```

* Pressure (Pa)

* Temperature (K)

* Gay-Lussac's law states that at constant volume, the pressure of a fixed amount of gas is directly proportional to the temperature of the gas. Mathematically, Gay-Lussac's law can be stated like this:

```
P = k * T
```

* where P is pressure; k is constant; and T is temperature in kelvins.

* Here is a more useful representation of Gay-Lussac's law:

```
P1 / T1 = P2 / T2
```

* T1 and T2 are two temperature values, while P1 and P2 are the corresponding pressures.

---

1. You have a closed tank of air at a pressure of 203 kPa and temperature of 273 K. When the tank and the air are heated to 323 K, what is the pressure if the volume remains constant?

What are you given?

```js
let T1 = 273; // K
let T2 = 323; // K
let P1 = 203; // kPa
```

What are you looking for?

```
P2 = ?
```

Write the Gay-Lussac’s law equation:

```
P1 / T1 = P2 / T2
```

Solve for the unknown:
```
P2 = P1 * T2 / T1
```

Compute and check your answer:

```js
let T1 = 273; // K
let T2 = 323; // K
let P1 = 203; // kPa
let P2 = P1 * T2 / T1; // kPa
console.log('P2 = ', P2, 'kPa');
// P2 =  240.17948717948718 kPa
console.log('P2 = ', Math.round(P2), 'kPa');
// P2 =  240 kPa
```

---

2. A 10.0 L cylinder of nitrogen has a temperature of 298 K and a pressure of 101.5 kPa. When the pressure decreases to 50 kPa, what is the temperature if the volume remains constant?

What are you given?

```
T1 = 298 K
P1 = 101.5 kPa
P2 = 50 kPa
V = 10.0 L(Constant)
```

What are you looking for?

```
T2 = ?
```

Write the Gay-Lussac’s law equation:

```
P1 / T1 = P2 / T2
```

Solve for the unknown:

```
T2 = T1 * P2 / P1
```

Compute and check.

```js
let T1 = 298;  // K
let P1 = 101.5; // kPa
let P2 = 50; // kPa
let T2 = T1 * P2 / P1; // K
console.log('T2 = ', T2, 'K');
// T2 =  146.79802955665025 K
console.log('T2 = ', Math.round(T2), 'K');
// T2 =  147 K
```
