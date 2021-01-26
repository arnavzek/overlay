# overlay

## Usage
```
import Overlay from "./overlay";

//Alert
Overlay.alert("Some Message")

//Form
let elements = [
    {h3:"Sign up"},
    {input:{placeholder:"Username",name:"username"}},
    {input:{placeholder:"Password",name:"password"}},
    {button:{innerHTML:"Log in",onClick:console.log}}
]
Overlay.form(elements)

//Loading
Overlay.loading()

//Kill Alert
overlay.kill("alert")


//Kill Form
overlay.kill("form")
```
