# hyper-number
A high-precision large number system capable of handling numbers up to 10^^(1e50) and beyond with customization.
The base four-term array looks like this: `[sign (1 or -1), category (non-negative number below the maximum safe integer or BigInt otherwise), digitsOfData, data]`

Create a new instance using `Hyper("string")`.

**Try it out [HERE](https://plasma4.github.io/hyper-number/)!** (You can set the precision to any integer from 16 to 10,000,000.)
