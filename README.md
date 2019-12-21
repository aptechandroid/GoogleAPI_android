# Get an API Key


You must have at least one API key associated with your project.

To get an API key:

Visit the Google Cloud Platform Console.

Click the project drop-down and select or create the project for which you want to add an API key.

Click the menu button  and select APIs & Services > Credentials.

On the Credentials page, click Create credentials > API key.

The API key created dialog displays your newly created API key.

Click Close.

The new API key is listed on the Credentials page under API keys.
(Remember to restrict the API key before using it in production.)

# Restrict the API key

We strongly recommend that you restrict your API key. Restrictions provide added security and help ensure only authorized requests are made with your API key. There are two restrictions. You should set both:

Application restriction: Limits usage of the API key to either websites (HTTP referrers), web servers (IP addresses), or mobile apps (Android apps or iOS apps). You can select only one restriction from this category, based on the platform of the API or SDK (see GMP APIs by Platform).

Note: If you need to call web, web service, and/or mobile APIs from the same (client-side) app, create and restrict multiple keys.

API restriction: Limits usage of the API key to one or more APIs or SDKs. Requests to an API or SDK associated with the API key will be processed. Requests to an API or SDK not associated with the API key will fail. (The API or SDK must be enabled and must support the application restriction.)

To restrict an API key:

Go to the Google Cloud Platform Console.

Click the project drop-down and select the project that contains the API key you want to secure.

Click the menu button  and select APIs & Services > Credentials.

On the Credentials page, click the name of the API key that you want to secure.

On the Restrict and rename API key page, set the restrictions:

Application restrictions

Select Android apps and follow the instructions.

Click + Add package name and fingerprint.

API restrictions

Select Restrict key.

Click Select APIs and select Maps SDK for Android.
(If the Maps SDK for Android is not listed, you need to enable it.)

Click SAVE.
