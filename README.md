# thunderbird

## hello world
Creating a simple extension following https://developer.thunderbird.net/add-ons/hello-world-add-on 

Creating a manifest.json
Using a browser_action
popup.html
popup.js
popup.css

First, we create an empty hello-world project folder for our extension and navigate to it. 

Extensions require a manifest.json file that tells Thunderbird a few basic information about the add-on.

The manifest includes the definition for a browser_action. That is the button we want to add to Thunderbird's main toolbar. The reference to a browser in its name is inherited from the Firefox Browser.

HTML Note: The default content security policy disallows JavaScript placed directly in <script> tags and inline event handlers like onclick. Thus, place all Javascript code into a separate file (like popup.js in this example) and use addEventListener() instead of inline event handlers.