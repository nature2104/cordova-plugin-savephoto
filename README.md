# cordova-plugin-savephoto
Save Photo To System Album

# Install
cordova plugin add https://github.com/nature2104/cordova-plugin-savephoto.git


# User 
 ```javascript
	var path = "http://xxxx/test.jpg";
    navigator.savePhoto.save(path, function (res) {
      alert(angular.toJson(res))
    }, function (error) {
      alert(angular.toJson(error))
    });
  ```