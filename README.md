<!DOCTYPE html>

<html ng-app="LunchCheck">

<head>

    <title>Lunch Check</title>

    <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.2/angular.min.js"></script>

    <script src="app.js"></script>

    <link rel="stylesheet" type="text/css" href="styles.css">

</head>

<body>

    <div ng-controller="LunchCheckController">

        <h1>Lunch Check</h1>

        <div>

            <input type="text" ng-model="lunchItems" placeholder="List comma-separated items" />

            <button ng-click="checkLunch()">Check If Too Much</button>

            <p class="message">{{ message }}</p>

        </div>

    </div>

</body>

</html>


