# check-duplicate
A simple website that calculates the SHA256 of a list of files, and counts which one are unique

Try it: https://dinoosauro.github.io/check-duplicate/
![image](https://github.com/Dinoosauro/check-duplicate/assets/80783030/80263962-94d0-4822-908d-5d35d0acbeec)

## Functionality
Click on the "Choose files" button to choose the files to check. After that, the SHA256 of them will be automatically calculated. You'll see the number of unique files, and also the SHA256 of each file in a table. You can also redownload each file to your device, or export the table in a CSV format.
## Offline use
Everything is done in your browser, and therefore you can use this tool offline. You can both install it as a Progressive Web App, or download the HTML file and use it in this way. Since it's really lightweight (the HTML file, that also contains the script, the icon and the style weights 13KB), I decided to incorporate everything in a single HTML file that can be easily moved across devices and doesn't require a local server to be used.
## Privacy
Everything is done in your browser, and none of your files are sent to an external server. The only connections made from check-duplicate are to Google Fonts to fetch the 'Work Sans' font used for the UI, but no data is shared with them.
