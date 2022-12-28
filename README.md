
1. Pseudo Selectors : after and before
2. Flex design
3. Flex direction : Row and Column

### How to make a backgound and set it's opacity

```css
header::before{
            background: url('https://source.unsplash.com/collection/190727/1600x900') no-repeat center center/cover;
            content: "";
            position: absolute;
            top:0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.3;
        }
```

### Navbar flex direction for dextop

```css
    .navigation {
            display: flex;
            flex-direction: row; 
        }
```

### Navbar flex direction for mobile

```css
    .navigation {
            display: flex;
            flex-direction: column; 
        }
```