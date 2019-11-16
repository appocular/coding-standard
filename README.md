# Appocular Coding Standard

This is the PHP coding standard used by Appocular, based on PSR12 and
[Slevomat Coding
Standard](https://github.com/slevomat/coding-standard).

It incorporates PSR12 unmodified, and most of Slevomat, disabling
Slevomat rules where they conflict with PSR12. Some other Slevomat
rules have been disabled, see [the
ruleset.xml](AppocularCodingStandard/ruleset.xml) for details.

## Installation

Add a repository to your `composer.json`:

``` yaml
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/appocular/coding-standard"
        }
    ]
```

And require the package:

``` shell
composer require --dev appocular/coding-standard
```

## Configuration

Example `.phpcs.xml`:

``` xml
<?xml version="1.0"?>
<ruleset>
    <file>./app</file>
    <file>./bootstrap</file>
    <file>./database</file>
    <file>./routes</file>
    <file>./tests</file>
    <config name="installed_paths" value="../../appocular/coding-standard"/>
    <rule ref="AppocularCodingStandard"/>
    <rule ref="SlevomatCodingStandard.Files.TypeNameMatchesFileName">
      <properties>
        <!-- Tell Slevomat the root directories of our namespaces, so
             it can check if the filepath is correct. -->
	<property name="rootNamespaces" type="array">
	  <element key="app" value="Appocular\Assessor"/>
	  <element key="tests" value="Appocular\Assessor"/>
	</property>
      </properties>
    </rule>
</ruleset>
```
