How to run this app:
1. Install Firebase CLI
2. Navigate to the project folder and type "firebase serve"
3. Open browser and type localhost:5000
4. Open browser's console to see the result.

Check the file "firebase.json" if the error is "CANNOT GET /". In the file "firebase.json", sepecify the hosting with the folder name and location that contain the html/css/js file as similar to the code below.

  "hosting" : {
    "public": "./public"
  },
