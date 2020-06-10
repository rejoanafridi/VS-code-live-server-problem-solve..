# VS-code-live-server-problem-solve..
# Server is started at 5500 but failed to open in Browser Preview. Got Browser Preview extension installed?
step 1- open vs code  go to extension (ctrl+shift+x) then search live server then go to live server manage / extension setting then + Edit in setting.json 
step 2- "liveServer.settings.useBrowserPreview": true, [ if u see that line u need to replace true to false ].  "liveServer.settings.useBrowserPreview": false, 
your problem is solved! enjoy vs code :)
