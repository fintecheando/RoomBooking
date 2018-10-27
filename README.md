# Install


1. Download Lucee Application Server
```console
wget https://cdn.lucee.org/lucee-4.5.5.015-express.zip
```

2. Create a folder for Lucee
```console
mkdir lucee
```

3. Move and Unzip the Lucee file
```console
mv lucee-4.5.5.015-express.zip lucee/
cd lucee/
unzip lucee-4.5.5.015-express.zip
```

4. Move the ROOT folder located in the webapps folder
```console
mv ROOT ../
mkdir ROOT
```

5. Clone the repository
```console
cd ROOT
git clone https://github.com/fintecheando/RoomBooking.git
```

6. Start the application server
```console
./startup.sh
```

7. Create a Datasource in the Admin Server view
```console
http://localhost:8888/lucee/admin/server.cfm
```

8. Install the Application and make sure that everything is in green
```console
http://localhost:8888/install/
```

9. Verify the Room Booking System
```console
http://localhost:8888/
```

# OxAlto Room Booking System

This is an open source application for booking rooms via a web based calendar, using cfWheels, Bootstrap3, jQuery, FullCalendar.js, and other bits.

Author: Tom King - http://www.oxalto.co.uk / https://github.com/Neokoenig / @neokoenig

## Demo

You can find a demo at [roombooking.oxalto.co.uk](http://roombooking.oxalto.co.uk)

## Version

Current version is 1.2 [release notes](http://roombooking.readme.io/v1.2/docs/12)

## Documentation

All documentation now lives at [roombooking.readme.io](http://roombooking.readme.io)

## Installation & Upgrading

Please see the [roombooking.readme.io](http://roombooking.readme.io) for all documentation including installation and upgrade notes.

## Notes

 This application uses the following plugins and 3rd party code:

 - [ColdFusion on Wheels][3]
 - [jQuery][4]
 - [Bootstrap3] [5]
 - [FullCalendar][6]
 - [MomentJS][7]

## License

Room Booking System is released under the Apache License Version 2.0.

[3]: http://cfwheels.org/
[4]: http://jquery.com/
[5]: http://getbootstrap.com/
[6]: http://fullcalendar.io/
[7]: http://momentjs.com/
