---
{"dg-publish":true,"permalink":"/level-4/eei-4366/fc/"}
---


```aosr-deck-config
{
	"rule": {
		"conditions": {
			"all": [{
				"fact": "file",
				"path": "$.tags",
				"operator": "regexMatch",
				"value": "eei4366"
			}]
		},
		"event": {
			"type": "match"
		}
	}
}
```

