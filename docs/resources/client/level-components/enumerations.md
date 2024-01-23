# Client Enumerations Resource

## Level Object Data
The following enumerations are used by [level objects](level-object.md) as possible values for parameters.

### Easing
The easing function used by most motion triggers (Move, Rotate, Scale, etc)

| Key | Name/Value                           
|:----|:---------------------------
| 0   | None ***(AKA: linear)***
| 1   | Ease In Out
| 2   | Ease In
| 3   | Ease Out
| 4   | Elastic In Out
| 5   | Elastic In
| 6   | Elastic Out
| 7   | Bounce In Out
| 8   | Bounce In
| 9   | Bounce Out
| 10  | Exponential In Out
| 11  | Exponential In
| 12  | Exponential Out
| 13  | Sine In Out
| 14  | Sine In
| 15  | Sine Out
| 16  | Back In Out
| 17  | Back In
| 18  | Back Out

### Pulse Mode
The color space to interpolate in

| Key | Name/Value                           
|:----|:---------------------------
| 0   | Color
| 1   | HSV

### Pulse Target Type
The method of selecting objects to pulse

| Key | Name/Value                           
|:----|:---------------------------
| 0   | Channel
| 1   | Group

### Pickup Item Mode
Sorry, no info yet :(

### Touch Toggle Mode
How the target should be toggled

| Key | Name/Value                           
|:----|:---------------------------
| 0   | Toggle
| 1   | Toggle On
| 2   | Toggle Off

### Instant Count Comparison
Which comparison to perform
| Key | Name/Value                           
|:----|:---------------------------
| 0   | Equals
| 1   | Larger
| 2   | Smaller

### Target Pos Coordinates

| Key | Name/Value                           
|:----|:---------------------------
| 0   | X and Y
| 1   | X
| 2   | Y

### Item Type
The type of item to reference

| Key | Name/Value                           
|:----|:---------------------------
| 0   | None
| 1   | Item
| 2   | Timer
| 3   | Points ***(read-only)***
| 4   | Time ***(read-only)***
| 5   | Attempts ***(read-only)***

### Item Target Type
The type of item to modify

| Key | Name/Value                           
|:----|:---------------------------
| 0   | None
| 1   | Item
| 2   | Timer
| 3   | Points ***(read-only)***
| 4   | Time ***(read-only)***
| 5   | Attempts ***(read-only)***

### Expression Operator
Which operation to perform

| Key | Name/Value                           
|:----|:---------------------------
| 0   | Equals
| 1   | Add
| 2   | Subtract
| 3   | Multiply
| 4   | Divide

### Expression Comparison
Which comparison to perform

| Key | Name/Value                           
|:----|:---------------------------
| 0   | Equal to
| 1   | Greater than
| 2   | Greater Than Or Equal To
| 3   | Less than
| 4   | Less Than Or Equal To
| 5   | Not Equal To

### Rounding Function
How the value should be rounded

| Key | Name/Value                           
|:----|:---------------------------
| 0   | None
| 1   | Round
| 2   | Floor
| 3   | Ceiling

### Sign Function
How the sign of the value should be set

| Key | Name/Value                           
|:----|:---------------------------
| 0   | None
| 1   | Absolute Value
| 2   | Force Negative
