# regex(es)

## Phone number

> TODO: **+66** version

```regex
/^0(6|8|9)\d{8}$/
```

- The whole number must have exactly 10 digits
- The first digit must be **0**
- The following digit must be either **6, 8, 9** (06x, 08x, 09x)
- The rest must be 8 digits
