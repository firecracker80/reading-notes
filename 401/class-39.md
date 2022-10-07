# Reading Assignment 39

## Location
>
>Your app can ask for the user's device's most recent location using the location APIs provided by the Google Play services. You are typically interested in the user's current location, which is same as the device's last known location, while optimizing their device battery power.
>
>In order to access the Google location API, your project must have Google Play services included. This can be downloaded through the SDK Manager to add the library. Make sure to request permissions for their location.
>
>In your code, be sure to create an instance for the Fused Location Provider Client within your onCreate method. This will allow you to retreive the location data. How accurate or precise, will depend on the permissions that were setup. The best way to get the last known location or the current location is through the getLastLocation or getCurrentLocation methods, respectively.

## Things I want to know more about...
>Can we set a specific area/region?