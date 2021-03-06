# Downloads

## System requirements
* Windows platform with .NET 4.6.2 framework
* 64 bits CPU

## Latest versions

| Description            | Version        | Download                                                                                                 |
|:-----------------------|----------------+----------------------------------------------------------------------------------------------------------|
| Full dsm suite         | 1.0.7323.12273 | [link](https://dsmsuite.github.io/downloads/DsmSuite_1.0.7323.12273.msi)                                 |
| DsmSuite example model | -              | [link](https://dsmsuite.github.io/downloads/DsmSuite.dsm)                                                |
| ArgoUml example model  | -              | [link](https://dsmsuite.github.io/downloads/ArgoUml.dsm)                                                 |

See [All downloads](all_downloads) for all downloads including older versions.

# Change History

## 9 March 2019 - Version 1.0.7007

* Initial release 

## 12 March 2019 - Version 1.0.7010

* Fixed DSM viewer not showing element numbers and cyclic dependencies in yellow when requested

## 19 March 2019 - Version 1.0.7017

* Visual studio analyzer
	* Added exception logging when filter file can not be parsed

## 20 March 2019 - Version 1.0.7018

* Visual studio analyzer 
	* Make tools version configurable (default is 14.0)
	* Log error instead of exception when source file in visual studio project not found  
* Log full stack trace when logging exception

## 26 March 2019 - Version 1.0.7025

* DSM viewer and builder
	* Very large performance improvements on DSM builder and viewer to support large models
	* DSM builder and viewer are now 64bits processes

## 2 April 2019 - Version 1.0.7031

* Visual studio analyzer 
	* Do not remove solution and project file extensions show they show up as separate elements in DSM
* DSM viewer and builder
	* Speedup loading DSM files by avoiding multiple xml parse runs
	
## 16 April 2019 - Version 1.0.7045

* General
    * Add metadata to dsi and dsm files and show them in overview report
	* Add setting to determine if output should be written in compressed format
	* Auto detect compressed .dsi or .dsm files during reading
* DSM viewer
    * Improved overview html report	
	* Improve visibility numbers in matrix column header
	
## 28 April 2019 - Version 1.0.7057

* DSM viewer
    * Added new html reports
	    * Consumers and providers of selected matrix cell
		* Provided and required interfaces of selected element
		
## 5 May 2019 - Version 1.0.7064
		
* DSM viewer
    * Improved html reports
* Transformer  
    * Used regex for filters
* Visual studio analyzer
    * Extended unit tests for dynamic folder property

## 14 May 2019 - Version 1.0.7073	

* Visual studio analyzer 
	* Add target extension to visual studio project file element
	
## 4 December 2019 - Version 1.0.7277.38011

* Single installer for entire DSM suite
* Minor non compatible changes in DSI and DSM model formats
* Viewer fully rewritten in WPF
    * Improved look & feel 
	* Show detail matrix for element or relation
	* Search element feature
	* Progress bar while opening or saving files
	* Open dsm file by clicking it after associating .dsm extension with DSM viewer
	
## 19 December 2019 - Version 1.0.7292.9302

* Functionality to edit models 
    * Create, edit and delete elements
    * Create, edit and delete relations    
    * Move up/ move down partition
    * Undo functionality	
	
## 23 December 2019 - Version 1.0.7296.39969

* Improved edit model features
* Saving edit actions to file

## 26 December 2019 - Version 1.0.7299.26182

* Implemented option update existing dsm model with new dsi model
* Refined look&feel

## 30 December 2019 - Version 1.0.7303.12948

* Again refined look&feel
* Metrics bar in matrix currently showing number of elements and consumers and providers
* Enable ok button if edit dialogs when data is valid
* Made element search by name case insensitive
* Fixed model not cleared when loading new model
* Improved performance matrix view for large expanded models
* Reduce font size to 11 and limit weight to max 9999 to avoid drawing out side of cell
* Fixed thats actions in data model where not cleared when clearing actions via UI
* Fixed crash when element at bottom of dsm was deleted

## 1 Januari 2020 - Version 1.0.7305.36212

* Improved metrics view including cyles
* UI themes support
* Persist viewer settings in user folder
* Make visual distinction between system and hierarchical cycle
* Indicate consumers and providers with small colored status bar upon hovering over element
* Fix actions properly cleaned
* Fixed that dependency weights were not properly calculated after moving an element

## 6 Januari 2020 - Version 1.0.7310.12684

* Add beta feature toggle
    * Added to settings dialog
    * Changed 'move element in hierarchy using drag and drop' to beta feature, because it is not fully mature
* Always log exceptions
* Fix element order always updated after any element edit action
* Several UI layout and theme changes
* Fixed cell colors when first child expanded
* Fixed issue with show cycles setting

## 14 Januari - Version DsmSuite_1.0.7318.22276

* Single toot introduced in DSM
* Fixed some defects related to change element parent
* Fixed issue with show cycles setting
* Fixed feature change element parent
* Added name to single root
* Fix enable undo buton after dragging element

## 18 Januari 2020 - Version 1.0.7322.12836

* Improved layout settings dialog
* Remove prefix single root from transformer
* Fixed create element in root
* Ensure undo command is enabled again after element is dragged
* Change name builder setting

## 19 Januari - Version 1.0.7323.12273

* Fixed transitive includes not generated by transformer due to key not converted to lower case