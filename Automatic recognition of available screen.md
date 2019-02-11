Physically, there are multiple screens of various sizes (resolutions).

1. Autodetect the characteristics of the connected screen and set its resolution in a variable for re-use in the code
2. Provide a way to override this detected resolution and choose a lower one by setting a value in the configuration file. Throw a log error if the set resolution is higher than what the screen can handle, and restrain to the screen's resolution.
