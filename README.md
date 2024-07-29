# hyper-number
**Version 1.2.0 update: improved the performance by changing how powers of ten are obtained**
**Version 1.1.0 update: fixed numerous bugs and errors involved**

HyperNumber is a high-precision large number system capable of handling numbers up to 10^^(1e50) and beyond with customization. It uses `BigInt` to handle such features.
The base four-term array looks like this: `[sign (1 or -1), category (non-negative number below the maximum safe integer or BigInt otherwise), digitsOfData, data]`

Create a new instance using `Hyper(string | number | bigint | Hyper)`. Read the source code for documentation!

**Try it out [HERE](https://plasma4.github.io/hyper-number/)!** (You can set the precision to any integer from 16 to 10,000,000.)