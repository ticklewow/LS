app.js

(function() {
    'use strict';

    var app = angular.module('test', []);

    app.run();

})();

index.js

var app = angular.module('test');
app.controller('indexCtrl', function () {

    'use strict';
    var vm = this;

    vm.title = "First Build from Stract";

    vm.list1 = [
        { field1: 'First', field2: 'First2', field3: 'First3' },
        { field1: 'Second', field2: 'Second2', field3: 'Second3' },
        { field1: 'Third1', field2: 'Third12', field3: 'Third13' }
    ];

});

index.html

<html ng-app="test">
<head>
    <title>My Angular App</title>
    <script src="Scripts/angular.min.js"></script>
    <script src="app.js"></script>
    <script src="app/controller/index.js"></script>
</head>
<body ng-controller="indexCtrl as vm">
    <div>
        {{vm.title}}
    </div>
    <div ng-repeat="model in vm.list1">
        {{model.field1}} {{model.field3}}
    </div>
</body>
</html>
