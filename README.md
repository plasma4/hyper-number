# hyper-number
**Version 1.2.0 update: improved the performance by changing how powers of ten are obtained**

**Version 1.1.0 update: fixed numerous bugs and errors involved**

HyperNumber is a high-precision large number system capable of handling numbers up to 10^^(1e50) and beyond with customization. It uses `BigInt` to handle such features, which is a feature that is now supported by *all* major browsers (well, except Internet Explorer, but does that really count?).

Within each instance of `Hyper`, there is a property, `$`. This property contains the data of the number, in which there is an array that looks like this with four values: `[sign (1 or -1), category (non-negative number below the maximum safe integer or BigInt otherwise), digitsOfData, data]`

Create a new instance using `Hyper(string | number | bigint | Hyper)` or `new Hyper(string | number | bigint | Hyper)`. Read the source code for documentation!

**Try out formatting and see how the array works [HERE](https://plasma4.github.io/hyper-number/).** (You can set the precision to any integer from 16 to 10,000,000 when actually using the algorithm.)