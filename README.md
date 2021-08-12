# Farm Manager
## Scenario
FarmerSys is a small cooperative of farmers that is looking to hire you to create an app to help onboard new farmers and manage their farm information. The app should allow the user to view all the farmers that exist online and their farms. The app should also be able to create new farmers and farms and send the information to their website.

## Requirements
Hint: In addition to other technical areas of interest, we are very keen on your thought process. Feel free to be creative. Make your app look as good as you can. But do not complicate your solution in a bid to impress only to find it unfinished in the stipulated period. You are allowed a maximum of 120 hours to complete. The last commit created in that time is what we take into account.

## Client requirements
- Have a home page that contains a search text field and a list of farmers
- The list of farmers on the home page should be pulled from the following API everytime the app launches and stored locally on a database on the device: https://testapi.io/api/thomasjgx/farmers
- The search field on the home page should be able to filter the list of farmers based on what you are searching for
- Have a new farmer button that allows you to create a new farmer locally with the following information: id, first_name, last_name, member_number, gender, phone_number and email. This new farmer is created on the local db without having to post them online. Add form validation where neccesary.
- Add features for editing and deleting farmers from the local db
- When you tap on a farmer from the list of farmers on the home page it should open another screen showing details about the selected farmer
- On the details page you should be able to access a list of farms that the farmer owns.
- Add a new farm button that allows you to create a new farm and store it locally with the following information: id, farm_name and farm_size.
- Add features for editing and deleting farms from the local db
- Add a sync feature that all sends all the new farmers or farms you've created to the following API as a post every 1 hour: https://testapi.io/api/thomasjgx/farmers/sync. You can define the POST fields as new_farmers, new_farms, updated_farmers, updated_farms, deleted_farmers and delete_farms. Send the entire record e.g. updated_farmers: [{"id": 1. "first_name": "James", "last_name": "Zumba".....}]
- Please note that our api (https://testapi.io/api/thomasjgx/farmers) will not show the updated information that you post. But we will log the request you send and we will review it when assessing your code.
- Your app should be able to retain all its data and functionality when you turn off the internet and restart the app

## Technical requirements
- Write unit and e2e tests
- Provide the command necessary to run your tests
- Create a private repository on GitHub and add [thomasjgx@gmail.com](mailto:thomasjgx@gmail.com) as a collaborator
- Push your code to that repoitory in as many commits as neccessary - preferably more than one.

## Languages allowed
Use any of the following programming languages:

- Flutter (Preferred)
- Koitlin (Android)
- Swift (iOS)

## Resources
- https://flutter.dev/?gclsrc=ds&gclsrc=ds
- https://developer.android.com/
- https://developer.apple.com/swift/

