<h1 align="center">bootstrap-select</h1>

<p align="center">
	<strong>The jQuery plugin that brings select elements into the 21st century with intuitive multiselection, searching, and much more. Now with Bootstrap 4 support.</strong>
</p>

<p align="center">
	<a href="https://github.com/snapappointments/bootstrap-select/releases/latest" target="_blank">
		<img src="https://img.shields.io/github/release/snapappointments/bootstrap-select.svg" alt="Latest release">
	</a>
	<a href="https://www.npmjs.com/package/bootstrap-select" target="_blank">
		<img src="https://img.shields.io/npm/v/bootstrap-select.svg" alt="npm">
	</a>
	<a href="https://www.nuget.org/packages/bootstrap-select" target="_blank">
		<img src="https://img.shields.io/nuget/v/bootstrap-select.svg" alt="NuGet">
	</a>
	<a href="https://cdnjs.com/libraries/bootstrap-select" target="_blank">
		<img src="https://img.shields.io/cdnjs/v/bootstrap-select.svg" alt="CDNJS">
	</a>
	<a href="https://www.jsdelivr.com/package/npm/bootstrap-select" target="_blank">
		<img src="https://data.jsdelivr.com/v1/package/npm/bootstrap-select/badge?style=rounded" alt="jsDelivr">
	</a>
	<br>
	<a href="https://github.com/snapappointments/bootstrap-select/blob/master/LICENSE" target="_blank">
		<img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="License">
	</a>
	<a href="https://david-dm.org/snapappointments/bootstrap-select?type=peer" target="_blank">
		<img src="https://img.shields.io/david/peer/snapappointments/bootstrap-select.svg" alt="peerDependencies Status">
	</a>
	<a href="https://david-dm.org/snapappointments/bootstrap-select#info=devDependencies" target="_blank">
		<img src="https://david-dm.org/snapappointments/bootstrap-select/dev-status.svg" alt="devDependency Status">
	</a>
</p>

<p align="center">
	<a href="https://developer.snapappointments.com/bootstrap-select"><img src="https://user-images.githubusercontent.com/2874325/38997831-97e12bbe-43ab-11e8-85f5-b8c05d91c7b1.gif" width="289" height="396" alt="bootstrap-select demo"></a>
</p>

## Just "A" fork

This Is a for of the original [bootstap-select](https://developer.snapappointments.com/bootstrap-select/), which works with Bootstrap 4.

## Changes

- Uses _SCSS_ instead on _LESS_ in _gruntfile.js_
- Added _Submit Box_ below live search and action box.

## Usage

- set `submitBox=true` to enable the feature
- you can set `submitBoxButton.ok` string for the confirmation button (which performs a trigger on _Native Change_ action)
- you can set `submitBoxButton.cancel` string for the cancel button (which performs a _Deselect All_ action)
- you can use custom classes on Buttons by calling `submitBoxClass`, if none provided, DEFAULT will be used.
