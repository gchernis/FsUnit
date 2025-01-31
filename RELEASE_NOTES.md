### 3.4.1 - Aug 18, 2018
* xunit (2.4.1)
* NUnit (3.12)
* MSTest.TestFramework (1.4)

### 3.4.0 - Nov 10, 2018
* Added `inRange` operator

### 3.3.0 - Nov 9, 2018
* NUnit (3.11)
* xunit (2.4.1)

### 3.2.0 - Jul 30, 2018
* xunit (2.4)
* NUnit (3.10.1)
* MSTest.TestFramework (1.3.2)
* NETStandard.Library (2.0.3)

### 3.1.0 - Feb 16, 2018
* Multi-target .NET Core 2.0 projects
* Fixed "Change shouldBeSmallerThan to fail when passed 2 equal numbers" https://github.com/fsprojects/FsUnit/pull/112
* Added slighly more meaningful messages to a few matchers https://github.com/fsprojects/FsUnit/pull/115
* NuGet package allow to reference FSharp.Core 4.3.x https://github.com/fsprojects/FsUnit/issues/116

### 3.0.0 - Aug 11, 2017
* Support NUnit 3.6
* Compiled for .NET Standard 1.6 (NUnit, xUnit, MSTest)
* Removed `choice n` combinator from `FsUnit.NUnit`

### 2.3.2 - Oct 4, 2016
* Added support of `NUnit 3.5`

### 2.3.1 - July 9, 2016
* Added support of `NUnit 3.4.1`

### 2.3.0 - June 27, 2016
* Added support of `NUnit 3.4`

### 2.2.0 - March 26, 2016
* Added support of `NUnit 3.2.1`
* Added FsUnitTyped with statically typed operators - https://github.com/fsprojects/FsUnit/pull/85
* Fixed: Structural equality fail - https://github.com/fsprojects/FsUnit/issues/78
* Fixed: Statically typed equality test - https://github.com/fsprojects/FsUnit/issues/21
* Fixed: Simplify "should throw" - https://github.com/fsprojects/FsUnit/issues/20
* Fixed: matchList can match empty obj lists - https://github.com/fsprojects/FsUnit/pull/90

### 2.1.0 - March 7, 2016
* Added support of `NUnit 3.2`
* Added pretty-print for F# value types - https://github.com/fsprojects/FsUnit/pull/89

### 2.0.0 - February 8, 2016
* Added support of `NUnit 3` - https://github.com/fsprojects/FsUnit/pull/83
* Dropped support of obsolete `not` operator

### 1.4.1.0 - 07 December 2015
* Fixed `should be null` - https://github.com/fsprojects/FsUnit/issues/52

### 1.4.0.0 - 03 November 2015
* Migration to xUnit 2.1
* FsUnit.NUnit compiled for net45
* Target FsUnit to FSharp.Core 3.1.2.5
* FsUnitDepricated module renamed to FsUnitDeprecated https://github.com/fsprojects/FsUnit/pull/46
* Enable substring checks https://github.com/fsprojects/FsUnit/pull/45
* Fixed assertion message for NUnit equal constraint - https://github.com/fsprojects/FsUnit/pull/60
* Added support of `shouldFail` operator for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/64
* Added support of `instanceOfType` operator for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/65
* Added support of `Empty` operator for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/66
* Added support of `NaN` operator for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/67
* Added support of `haveLength` and `haveCount` operators for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/68
* Added support of `unique` operator for xUnit, MsTest and MbUnit - https://github.com/fsprojects/FsUnit/pull/70

### 1.3.1.0 - 26 July 2015
* Bump NUnit version up to 2.6.4
* Bump xUnit version up to 1.9.2
* Bump MbUnit version up to 3.4.14
* Migration to Paket
* Readme and samples converted to FsUnit site

### 1.3.0.1 - June 29 2014

### 1.2.1.0 - April 28 2013
* Includes new features for generic assertions and containment check. Currently, this feature is only supported for the NUnit implementation. Thanks to jack-pappas for the contributions.

### 1.1.0.0 - April 21 2012
* Pulls in the latest versions for xUnit.NET and NUnit. Replaces the "not" keyword with "not'" and adds the FsUnitDepricated module for backward compatibility. Adds MsTest support for VS11 only.

### 1.0.1.3 - April 21 2012
* Includes new assertions for NUnit such as NaN, instanceOfType, and unique.

### 1.0.0.4 - December 25 2011
* Added support for xUnit.NET and MbUnit and a new assertion.

### 0.9.1.1 - December 03 2011
* Added several new assertions.

### 0.9.0.0 - February 12 2011
* Ray Vernagus built this version and several before it with NUnit as the targeted testing framework.