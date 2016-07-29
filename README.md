# solunar
Pure JS Solunar table calculator


This is just hacked together. Please report any issues.

```javascript
var solunar = require('solunar');
var times = solunar.getTimes(new Date(2016,07,29), 43.7, -79.4);
//times is: 
{
	"action": 1,
	"moon": {
		"phase": "Waning Crescent",
		"phaseno": 0.8944546203070973,
		"transits": [{
			"time": "2016-08-29T15:11:00.000Z",
			"overhead": true
		}, {
			"time": "2016-08-30T03:37:00.000Z",
			"overhead": false
		}],
		"rise": "2016-08-29T07:50:34.745Z",
		"set": "2016-08-29T22:23:45.762Z"
	},
	"sun": {
		"solarNoon": "2016-08-28T17:20:11.970Z",
		"nadir": "2016-08-28T05:20:11.970Z",
		"sunrise": "2016-08-28T10:38:44.079Z",
		"sunset": "2016-08-29T00:01:39.862Z",
		"sunriseEnd": "2016-08-28T10:41:46.218Z",
		"sunsetStart": "2016-08-28T23:58:37.723Z",
		"dawn": "2016-08-28T10:08:53.608Z",
		"dusk": "2016-08-29T00:31:30.333Z",
		"nauticalDawn": "2016-08-28T09:32:56.332Z",
		"nauticalDusk": "2016-08-29T01:07:27.609Z",
		"nightEnd": "2016-08-28T08:54:44.880Z",
		"night": "2016-08-29T01:45:39.061Z",
		"goldenHourEnd": "2016-08-28T11:17:13.644Z",
		"goldenHour": "2016-08-28T23:23:10.297Z"
	},
	"minor": [{
		"start": "2016-08-29T07:20:34.745Z",
		"end": "2016-08-29T08:20:34.745Z"
	}, {
		"start": "2016-08-29T21:53:45.762Z",
		"end": "2016-08-29T22:53:45.762Z"
	}],
	"major": [{
		"start": "2016-08-29T14:11:00.000Z",
		"end": "2016-08-29T16:11:00.000Z",
		"overhead": true
	}, {
		"start": "2016-08-30T02:37:00.000Z",
		"end": "2016-08-30T04:37:00.000Z",
		"overhead": false
	}]
}

```
