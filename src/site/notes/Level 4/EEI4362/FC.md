---
{"dg-publish":true,"permalink":"/level-4/eei-4362/fc/"}
---


# Notes

```aosr-deck-config
{
	"rule": {
		"conditions": {
			"all": [{
				"fact": "file",
				"path": "$.tags",
				"operator": "regexMatch",
				"value": "eei4362-n"
			}]
		},
		"event": {
			"type": "match"
		}
	}
}
```

# Quizzes
```aosr-deck-config
{
	"rule": {
		"conditions": {
			"all": [{
				"fact": "file",
				"path": "$.tags",
				"operator": "regexMatch",
				"value": "eei4362"
			}]
		},
		"event": {
			"type": "match"
		}
	}
}
```
