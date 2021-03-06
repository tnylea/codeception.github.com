---
layout: doc
title: Asserts Module - Codeception - Documentation
---



<div class="btn-group" role="group" style="float: right" aria-label="..."><a class="btn btn-default" href="https://github.com/Codeception/Codeception/blob/2.1/src/Codeception/Module/Asserts.php">source</a><a class="btn btn-default" href="https://github.com/Codeception/Codeception/blob/master/docs/modules/Asserts.md">master</a><a class="btn btn-default" href="https://github.com/Codeception/Codeception/blob/2.1/docs/modules/Asserts.md"><strong>2.1</strong></a><a class="btn btn-default" href="https://github.com/Codeception/Codeception/blob/2.0/docs/modules/Asserts.md">2.0</a><a class="btn btn-default" href="https://github.com/Codeception/Codeception/blob/1.8/docs/modules/Asserts.md">1.8</a></div>

# Asserts Module

**For additional reference, please review the [source](https://github.com/Codeception/Codeception/tree/2.1/src/Codeception/Module/Asserts.php)**


Special module for using asserts in your tests.



#### assertContains
 
Checks that haystack contains needle

 * `param`        $needle
 * `param`        $haystack
 * `param string` $message


#### assertEmpty
 
Checks that variable is empty.

 * `param`        $actual
 * `param string` $message


#### assertEquals
 
Checks that two variables are equal.

 * `param`        $expected
 * `param`        $actual
 * `param string` $message



#### assertFalse
 
Checks that condition is negative.

 * `param`        $condition
 * `param string` $message


#### assertFileExists
 
Checks if file exists
 
 * `param string` $filename
 * `param string` $message


#### assertFileNotExists
 
Checks if file doesn't exists
 
 * `param string` $filename
 * `param string` $message


#### assertGreaterThan
 
Checks that actual is greater than expected

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertGreaterThanOrEqual
 
Checks that actual is greater or equal than expected

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertGreaterThen
 
@deprecated


#### assertGreaterThenOrEqual
 
@deprecated


#### assertLessThan
 
Checks that actual is less than expected

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertLessThanOrEqual
 
Checks that actual is less or equal than expected

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertNotContains
 
Checks that haystack doesn't contain needle.

 * `param`        $needle
 * `param`        $haystack
 * `param string` $message


#### assertNotEmpty
 
Checks that variable is not empty.

 * `param`        $actual
 * `param string` $message


#### assertNotEquals
 
Checks that two variables are not equal

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertNotNull
 
Checks that variable is not NULL

 * `param`        $actual
 * `param string` $message


#### assertNotRegExp
 
Checks that string not match with pattern

 * `param string` $pattern
 * `param string` $string
 * `param string` $message


#### assertNotSame
 
Checks that two variables are not same

 * `param`        $expected
 * `param`        $actual
 * `param string` $message


#### assertNull
 
Checks that variable is NULL

 * `param`        $actual
 * `param string` $message


#### assertRegExp
 
Checks that string match with pattern

 * `param string` $pattern
 * `param string` $string
 * `param string` $message


#### assertSame
 
Checks that two variables are same

 * `param`        $expected
 * `param`        $actual
 * `param string` $message



#### assertTrue
 
Checks that condition is positive.

 * `param`        $condition
 * `param string` $message


#### fail
 
Fails the test with message.

 * `param` $message

<p>&nbsp;</p><div class="alert alert-warning">Module reference is taken from the source code. <a href="https://github.com/Codeception/Codeception/tree/2.1/src/Codeception/Module/Asserts.php">Help us to improve documentation. Edit module reference</a></div>
