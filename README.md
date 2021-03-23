# LinkUp!
QlikSense extension which enables the user to generate a link based on current selections. The user who creates the link has the ability to automatically route users to a different application and make selections OR use the copied link for distribution.

This extension is a remix of the 'Dashboard-Link-Generator' extension built by [fadyheiba](https://github.com/fadyheiba/Dashboard-Link-Generator) and includes a bunch more style and useability features.

## Installation

1. Move LinkUp to the default extension folder in Qlik Sense
2. Open Qlik Sense and add the 'LinkUp!' extension to a sheet
3. Configure properties	
	
## Usage

### Button Settings
![Screenshot](https://raw.githubusercontent.com/balexbyrd/LinkUp/main/img/buttonSettings.PNG)

#### Open New Tab
This will take your current selections and automatically open a new tab in your browser > open the app & sheet > apply the selections. This feature is useful when you have the same fields in two apps with different focuses or data volumes and assumes you're going to input an Alternate App ID and Alternate Sheet ID.

#### Copy To Clipboard
This Output Method does just that and lets the user know the link was copied. This is useful when you want to paste the link into a chat session or share during a presentation.

#### Create New Email
This will open your default email provider and prepopulate fields with the link.

Button Style
![Screenshot](https://raw.githubusercontent.com/balexbyrd/LinkUp/main/img/buttonStyle.PNG)

These settings are self explanetory using normal CSS inputs. For icons, I'm leveraging the icons already being brought into the dashboard from Qlik's [Leonardo UI](https://qlik-oss.github.io/leonardo-ui/icons.html)

## License

MIT