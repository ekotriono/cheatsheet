# Javascript ES6 Cheat Sheet

## const
```bash
const b = 'test' //cannot be re assign
```

## let
```bash
cons b = 'test'
check = true

if (check) {
    b = 'lala'
}
```

## Arrow function

```bash
const jumlah = (a+b) => a+b;
```

## Backtick Strings
```bash
const fullname = `hello my name is ${name}`
```

## Spread Operators
```bash
const a = {
    fullname: 'tim',
    username: 'timtim'
};

const b = {
    ...a,
    address: 'washington dc no 8 street'
}

console.log(b) // {fullname: 'tim', username: 'timtim', address: 'washington dc no 8 street'}
```