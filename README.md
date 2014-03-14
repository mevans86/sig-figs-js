sig-figs-js
===========

A calculator for significant figures.

If you're like me, you hate dealing with significant figures. Let this Javascript object and accompanying calculator take
care of things for you!

This calculator takes significant digits into account and applies the rules of significant figures to calculations.
It uses an [expression parser](https://github.com/silentmatt/js-expression-eval/tree/master) developed originally by
[Silent Matt](http://www.silentmatt.com) as well as my SigFloat Javascript object (see sig-figs.js).

**Unitary functions:** sin(a), cos(a), tan(a), asin(a), acos(a), atan(a), sqrt(a), log(a), abs(a), ceil(a), floor(a), round(a), exp(a), random(a), fac(a)

**Binary functions:** pyt(a, b), pow(a, b) or a ^ b, min(a, b), max(a, b), a % b, atan2(a, b)

Note that the calculator depends on jQuery and Bootstrap, which aren't included here.
