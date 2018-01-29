# 8clok
Octal (base-8) wall clock time

Version: 0.1

Datetime: 2018-01-29T12:00:00Z

## Explanation

Each day consists of two halfs of 8 hours each, each hour is divided in 64 minutes, each minute is divided in 64 seconds. The figure of 64 is 8 times 8, so all minutes and seconds get evenly divided in groups of 8 over the hours. This means that one hour on the octal clock equals 1.5 hours on the regular clock.

![Image of octal clock](https://cdn.shopify.com/s/files/1/0358/9733/products/Art_a5a2374d-adb5-476b-b071-5e80dc4d1842_grande.png?v=1487108992)

To indicate full octal clock time, concatenate hours, minutes and seconds using the format hh:mm:ss:: this means two digits for each hour, minute and second this is specified. There are only 8 hours on the octal clock, therefore first h is always zero, but it is still there because it denotes the octal base, and it regularizes the way clock divisions are indicated. To indicate the minutes and seconds, you need to start at 1 (not at 0 like in regular clock time), and use two digits. E.g, 8 minutes becomes 08, 64 minutes becomes 88 (since this is in octal notation and not decimal notation like regular clock time). The same goes for seconds.

To give two examples:
- The earliest possible clock time is 01:01:01.
- The latest possible clock time is 08:88:88.

Instead of the numbers 1 through 8, which might be easily confused with the first 8 digits of the usual clock numbers 1 through 12, you could also use below 8 characters as octal digits, derived from the reordered ligatures in the [Shavian](https://en.wikipedia.org/wiki/Shavian_alphabet#Letters) character set:

Octal digit | Shavian digit
------------ | -------------
1 | 𐑹
2 | 𐑼
3 | 𐑸
4 | 𐑾
5 | 𐑺
6 | 𐑽
7 | 𐑻
8 | 𐑿
