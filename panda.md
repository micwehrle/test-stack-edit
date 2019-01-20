
```mermaid
sequenceDiagram
	user->>falcon:script
	falcon->>panda:script
	panda->>hippo: vehicle/dealer
	hippo-->>panda: vehicle/dealer
	panda->>mongo: create consumerSession
	panda-->>user: script & session
```


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMwNDE0NDY5Ml19
-->