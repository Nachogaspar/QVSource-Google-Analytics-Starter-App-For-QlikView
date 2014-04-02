## QVSource Google Analytics Starter App For QlikView
A template application showing how to get started using the [QVSource Google Analytics Connector](http://wiki.qvsource.com/Google-Analytics-Connector-For-QlikView-(v3).ashx) for QlikView. 

*Please Note:* We are working on a [replacement to this application here](https://github.com/QVSource/QVSource-Google-Analytics-Starter-App-For-QlikView-V2) with a simplified load script and data model.

If you are a QlikView + QVSource user you can simply click the ["Download ZIP"] (https://github.com/QVSource/QVSource-Google-Analytics-Starter-App-For-QlikView/archive/master.zip) button on GitHub to grab this application.

The content below is copied from the change log in the first tab of the load script.

### Change Log
#### 1.0.0.6 - 10/02/14
* Moved badge.
* Recreated repository.

#### 1.0.0.5 - 04/12/13
* Added badge.

#### 1.0.1.0 - 12/11/13
* Upgraded to use V3 of the Google Analytics Connector (including moving to QVX format for requests which is now the default for the connector).
* IMPORTANT: You now need V3 of this Connector to using this application ([click here](https://github.com/QVSource/QVSource-Google-Analytics-Starter-App-For-QlikView/releases/tag/1.0.0.4) for the final release for use with V2 of the Connector).
* Added a appId parameter to all requests (this is useful for logging, for example if you are running multiple apps on the same server - you can use this to identify them in the logs.

#### 1.0.0.4 - 10/09/13
* Fixed issue with referencing the wrong config file.

#### 1.0.0.3 - 12/07/13
* Renamed config file config.txt.
* Moved to GitHub.

#### 1.0.0.2 - 24/06/13
* Ooops - forgot to actually include the last fix (Fixed bug: let profileChanged = 'ga:'&$(profile); => let profileChanged = 'ga:$(profile)';)

#### 1.0.0.1 - 24/06/13
* Fixed bug: let profileChanged = 'ga:'&$(profile); => let profileChanged = 'ga:$(profile)';
* Improved config file so start date always goes back a fixed number of days from today.

#### 1.0.0.0 - 09/08/12
* First version of Google Analytics Application