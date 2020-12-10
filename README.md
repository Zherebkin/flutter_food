
## Configuration Steps
1. Cloning the repository:

```
$ git clone git@github.com:Zherebkin/flutter_food.git
```

2. Open the project and install dependencies (using terminal):

```
$ cd Foodspace
$ flutter pub get
```
This installs all the required dependencies like cloud_firestore, firebase_auth, shared_preferences, flutter_map, etc...

3. Foodspace/lib/shared/constants.dart

Sign up for the Zomato API key and set the value of the String 'YOUR_ZOMATO_API_KEY' to the key that you recieved.

`const String YOUR_ZOMATO_API_KEY = '';`

and save it.

4. Make an android project on your firebase account, follow the mentioned steps and you're good to go.

5. Now run the app on your connected device (using terminal):

`$ flutter run`
