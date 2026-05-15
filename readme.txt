DayZ Boosting / Increasing Number Of Vehicle Spawns At Events XML Mod Changelog & Terms Of Use

These XML files will increase the number of vehicles that spawn at events.

You can use all or any of the files, depending on the needs of your players.

This is part of scalespeeder gamings modular loot / CLE modding system, which is designed to be update independant, simple to install  and highly customizable.

Limited Testing on PC Chernarus Local Server DAYZ  Version 1.29 May 2026.

Designed to work with PC, PlayStation & Xbox DayZ Community Servers, for all maps that use these vehicles.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

-----------------------

PLEASE READ THE INSTRUCTIONS ON HOW TO INSTALL THESE FILES

To download the files from Github click the green "code" button, then "download zip" then extract the files to your local PC.

-----------------------

Stop your server.

On console you already have a "custom" folder inside the mission folder on your server. ON PC YOU MUST MAKE ONE, eg: mpmissions\dayzOffline.chernarusplus\custom

Now upload the file(s) you want to use:

veh-more-VehicleBoat-events.xml  (NOT ENOCH/LIVONIA)

veh-more-VehicleCivilianSedan-events.xml

veh-more-VehicleHatchback02-events.xml

veh-more-VehicleMilitaryBoat-events.xml (SAKHAL ONLY)

veh-more-VehicleOffroad02-events.xml (NOT SAKHAL)

veh-more-VehicleOffroadHatchback-events.xml

veh-more-VehicleSedan02-events.xml

veh-more-VehicleTruck01-events.xml

into your custom folder.

Next open up your vanilla cfgeconomycore.xml, and near the bottom, above the closing

</economycore>

tag, 

On a Chernarus Server to boost all vehicles, paste this, or delete the lines of the vehicles you don't want to boost:

	<ce folder="custom">
	<file name="veh-more-VehicleBoat-events.xml" type="events" />
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroad02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	
	</ce>
	
	On a Livonia Server paste this, or delete the lines of the vehicles you don't want to boost:

	<ce folder="custom">
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroad02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	
	</ce>
	
	On a Sakhal Server paste this, or delete the lines of the vehicles you don't want to boost:

	<ce folder="custom">
	<file name="veh-more-VehicleBoat-events.xml" type="events" />
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleMilitaryBoat-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	
	</ce>


If you are already using files to append your vanilla mission files, it should look something like this:

<ce folder="custom">
	<file name="some-other-types-file.xml" type="types" />
	<file name="some-other-events.xml" type="events" />
	<file name="some-other-spawnabletypes.xml" type="spawnabletypes" />
	<file name="some-other-messages.xml" type="messages" />
	<file name="some-other-globals.xml" type="globals" />
	<file name="veh-more-VehicleBoat-events.xml" type="events" />
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroad02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	</ce>

Save the file.

Upload where necessary.
	
Vailidate your edited files to check you haven't made any mistakes with https://www.xmlvalidation.com/

Restart your server & changes should start to take effect. How quickly will depend on the population of your server, as the new events start to spawn.

----------

Dominus vobiscum! scalespeeder

GOOD LUCK!