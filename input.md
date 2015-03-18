# E-mail field
>Disable auto-correct and disable auto-capitalization. Invoke special @ keyboard.

```
<input type="email" autocapitalize="off" autocorrect="off">
```

# Phone field
>Invoke special phone keyboard. (Note: iOS doesn't allow input of special characters such as parenthesis and dash with the phone keyboard. Thus, never require phone numbers to be formatted with such characters.)


```
<input type="tel">
```

# Address line field
> Disable auto-correct.

```
<input type="text" autocorrect="off">
```

# ZIP code field
> Set input pattern to numeric input. (Note: Argentina, Canada, Netherlands, and UK, may use letters in their postal code. To support these, dynamically change the input pattern depending on selected country.)

```
<input type="text" pattern="\d*" novalidate>
```

# Credit card number field
>Numeric keyboard.

```
<input type="text" pattern="\d*" novalidate autocorrect="off">
```

# Quantity field
> Semantic numeric keyboard.

```
<input type="number">
```

# Date field
> Date picker keyboard. (Note: You may want to implement an actual calendar date picker; see suggestion #7 in this Smashing Magazine article on m-commerce design.)

```
<input type="date">
```

