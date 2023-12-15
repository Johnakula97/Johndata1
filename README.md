%dw 2.0
var a = [ {
    "Name" : "John",
    "Location" : "Hyderabad",
    "salary" : "30000"
}
]
output application/json
---
a map {
    "salary" : $.salary
}
