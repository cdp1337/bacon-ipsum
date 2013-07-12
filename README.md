A *modified* repository for the baconipsum.com code 

## What's in here?

gga-BaconIpsumGenerator.php - Contains the BaconIpsumGenerator class for generating meaty filler text.  For example:

	require_once 'gga-BaconIpsumGenerator.php';
	$bacon_ipsum_generator = new BaconIpsumGenerator();
	$meaty_filler = $bacon_ipsum_generator->Make_Some_Meaty_Filler('meat-and-filler', 3, true);


gga-bacon-ipsum-form.php - WordPress plugin for generating the form you see on our home page as well as processing the form and outputting bacon ipsum filler.

gga-bacon-ipsum-api.php - WordPress plugin for our JSON API.

jquery-sample.html - Sample HTML/jQuery code for the jQuery plugin


## Revision History

Please see the [Complete CHANGELOG](CHANGELOG) for the revision history.