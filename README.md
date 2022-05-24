## XML to JSON Converter (tanpa Structure):
### dari
`<?xml version=1.0 encoding=UTF-8 standalone=no?>`\
`<Root>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
`</Root>`\

### menjadi
`[`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`},`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`},`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`}`\
`]`

### dari
`<?xml version=1.0 encoding=UTF-8 standalone=no?>`\
`<Root>`\
	`<TagName>Z123</TagName>`\
	`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
	`<TagValue>12.45</TagValue>`\
`</Root>`\

### menjadi

`{`\
	`"TagName": "Z123",`\
	`"TagDateTime": "2019-08-06T22:10:11",`\
	`"TagValue": "12.45"`\
`}`

## JSON to XML Converter (tanpa Structure):
### dari

`{`\
	`"TagName": "Z123",`\
	`"TagDateTime": "2019-08-06T22:10:11",`\
	`"TagValue": "12.45"`\
`}`

### menjadi
`<?xml version=1.0 encoding=UTF-8 standalone=no?>`\
`<Root>`\
	`<TagName>Z123</TagName>`\
	`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
	`<TagValue>12.45</TagValue>`\
`</Root>`

### dari
`[`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`},`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`},`\
	`{`\
		`"TagName": "Z123",`\
		`"TagDateTime": "2019-08-06T22:10:11",`\
		`"TagValue": "12.45"`\
	`}`\
`]`

### menjadi
`<?xml version=1.0 encoding=UTF-8 standalone=no?>`\
`<Root>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
	`<Element>`\
		`<TagName>Z123</TagName>`\
		`<TagDateTime>2019-08-06T22:10:11</TagDateTime>`\
		`<TagValue>12.45</TagValue>`\
	`</Element>`\
`</Root>`\
