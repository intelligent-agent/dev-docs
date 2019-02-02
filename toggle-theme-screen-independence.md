The current theme configuration is specifying screen size & positions in pixels from screen origin (where (0,0) is bottom left).

1. Modify the theme syntax to have themes use relative positionining for a screen ratio (assume a 16:9 ratio), using percentage of resolution.
2. Modify the Toggle main configuration to add a screen resolution field.
3. Update the Toggle theme load, so that the theme is properly loaded with dynamic resolution settings (720p and 1080p) coming from the Toggle configuration.
4. Write the documentation for the new theme styling syntax & configuration changes
