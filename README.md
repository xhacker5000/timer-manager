# timer-manager
easy to create a timer in javascript with a keyname and remove it with same keyname

### Usage

* Install
```sh
npm install timer-manager --save-dev
```


* createTimer
```javascript
	
	var Timer = require('timer-manager');
	Timer.createTimer('testTimer' , 1000 , function(){

			//do something
			...

	})

```

* removeTimer
```javascript
	
	Timer.removeElement('testTimer');
	
	
```

### Tips
you do not need to worry about same timer keyname, if timer pool have a same keyname , timer-manager will remove the timer before create;

