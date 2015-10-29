# AngularJS country select

Country select is an AngularJS directive for picking countries from a list.

It uses the same countries as the [country_select](https://github.com/stefanpenner/country_select) gem.

This directive will display the country's name in `<option>` but will bind your `ng-model` to the ISO-3166 alpha-2 code of the selected country.

How to USE
----------------------
*HTML*
  1. Add the markup ```<div country-select ng-model="selectedCountry"></div>```
  2. Add the dependency to your app's module ```angular.module('myApp', ['countrySelect']);```

*HAML*
  1. Add the markup ```%div{ country_select: true, ng_model: "selectedCountry" }```
