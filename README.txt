Krṣiveda corrected project files

Open sundaram.html in a browser. Keep style.css in the same folder. The HTML currently contains its own inline APP_DATA and application logic; app.js and data.js are provided as separate source files but are not loaded by sundaram.html to avoid duplicate global declarations.

Corrections made: supplied the missing style.css filename expected by the HTML, added the Leaflet stylesheet required for map display, and guarded optional theme/role UI elements against null references. JavaScript syntax checks passed for app.js, data.js, and all inline scripts in sundaram.html.
