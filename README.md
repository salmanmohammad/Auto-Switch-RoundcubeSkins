Auto Switch RoundcubeSkins
======

Auto Switch RoundcubeSkins Plugin for Roundcube 1.1.5

Presentation
------------

Plugin for adding the ability of switching between desktop skin and mobile skin. There is an automatic switch with the user-agent of the browser and a manual switch with two buttons (Desktop view and Mobile view)

It will automatically detect current skin and when you open RC webmail on mobile it will use corresponding mobile skin for mobile device and desktop skin for desktop device.


Installation:

Extract zip folder in plugins directory and add "Auto_Switch_RoundcubeSkins" in the Roundcube config.inc.php file in "plugins", ex: // List of active plugins (in plugins/ directory) $config['plugins'] = array( 'Auto_Switch_RoundcubeSkins', ); 