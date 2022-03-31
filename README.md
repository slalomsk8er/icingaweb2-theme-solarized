Solarized Theme for Icinga Web 2
======================================

This restores the Solarized theme and addes the dark/light mode support.
Based on [Ethan Schoonover's Solarized](https://ethanschoonover.com/solarized/)

Requires:
* Icinga Web 2.10 or newer

Only a few things are tweaked right now:

* TODO Colors of Icinga changed to Solarized
* TODO Login background changed

![Screenshot Login](screenshots/login.png)

![Screenshot Tactical Overview](screenshots/tac.png)

In every theme, the base theme of Icinga Web 2 is applied, and modifications need to be
added incrementally.

You can find the overall theme on [GitHub](https://github.com/Icinga/icingaweb2/tree/master/public/css/icinga)
or on your local system under `/usr/share/icingaweb2/public/css/icinga`.

## How to install

Install these theme repository like any other Icinga Web 2 module at:

    /usr/share/icingaweb2/modules/solarized
    
Enable the module:

    icingacli module enable solarized
    
Then you can select the theme in the admin or user UI.

![Changing themes as admin](screenshots/admin-theme.png)

![Changing themes as user](screenshots/user-theme.png)

Tweak it to your needs, you can also change the module name or
incorporate the files into your own module.

## Contribution

Feel free to add your ideas and examples here as well. Just add or modify a theme.

## License

Unless otherwise noted the license of these examples is Public Domain.

Icinga Web related examples were created by: [Markus Frosch](mailto:markus.frosch@icinga.com)

The ACME Logo was taken from [acmelogos.com](http://acmelogos.com) by
[Mackenzie Child](https://www.youtube.com/watch?v=QxeXfUmBvPU&feature=youtu.be).
No specific license was documented there, but the purpose seems to be
intended for free-use.

Other images:

* `samson-duborg-rankin-91091` [Samson Duborg-Rankin on Unsplash](https://unsplash.com/photos/ZGjbiukp_-A)
