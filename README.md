strtotime
=========
Node StrToTime function.

This code is taken from the [original project](https://github.com/blaxmas/date-util) by [blaxmas](https://github.com/blaxmas).

This is a simple fork of the original code but with the main difference that the `Date.prototype` scope is not extended.

Examples
--------

	var strtotime = require('strtotime');

	strtotime('1 week');
	strtotime('next friday');
	strtotime('2015-01-05');
	strtotime('27/02/2017');
