# removeJamfProMDM
###### For use when migrating macOS devices between Jamf Pro instances to clear out the old MDM Profile.
___
This script was designed to be used when migration Jamf Pro instances where an MDM profile is installed on the systems and needs to be removed prior to the migration.

Requirements:
* Jamf Pro
* Jamf Pro API User with permission to read computer objects
* Jamf Pro API User with permission to send management commands
* Script must be executed as root (due to profiles command)


Written By: Joshua Roskos | Professional Services Engineer | Jamf

Created On: June 20th, 2017 | Updated On: July 26th, 2017
___
