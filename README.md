###Intro 

 Based on src encoding/json

###Feature
 
  * Nothing Change
  * Support string decoding to number.


### Example

```go

	json := `{"number":"123","number2":123}`

       parsed := make(map[string]int,0)

       err := json.Unmarshal([]byte(json),ret)

    
```


