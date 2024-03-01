# Prompt Updates From Google Play Console to the Users
How to Prompt Updates to users from Google Play Console

Google Play Console offers a feature called “Recovery tools” that allows you to prompt users running specific app versions to update to the latest version when they restart the app (Cold Start). Here’s how to use it:

## 1. Access Recovery Tools:

* Open the Google Play Console and navigate to Releases > App Bundle Explorer.
* Or, access it from Releases > Releases overview.
* Under “Latest releases,” click the arrow next to the release you want users to update from. This opens the Release details page.


## 2. Start Recovery:

* Click on Recovery tools in the top-right corner.
* Select Prompt users to update from the dropdown menu.


## 3. Choose App Bundle(s):

* In the Choose a Bundle section, select the app bundle(s) containing the versions you want users to update from and click next.


## 4. Refine Targeting:

* It's not mandatory, but you can refine your targeting by:

* **Country**: Select specific countries where users will see the prompt.
* **Android** version: Target users using specific Android versions.

## 5. Review and Start:

* Review the summary of your selections in the Review section.
Once reviewed, click Start Recovery to initiate the prompt for users.

## 6. Monitoring Progress and Cancellation:

Google Play Console offers functionalities within the “Recovery tools” section to monitor the progress of your prompt and cancel it if needed:

* **Monitoring Progress:** Once you initiate the prompt, you can track its progress under the Recovery tab for the specific release. This tab displays the number of users who have successfully updated the app and who have not.
* **Canceling the Prompt:** If needed, you can cancel the prompt anytime by clicking the Cancel Recovery button within the Recovery tab. This will prevent further users from seeing the prompt.

# Limitations:

* This feature only works with app bundles, not APKs.
* You can’t target specific users; the prompt appears to all users running the selected app versions.
* Users can still have the option to ignore the prompt and continue using the outdated version.

