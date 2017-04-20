# destruct, the right way

    npm install destruct

## Usage
```javascript
import destruct from 'destruct'
const target = {
    username: 'someusername',
    person: {
        name: 'John Doe'
    }
}
const obj = destruct(target, 'username', 'person.name')
console.log(obj) // { username: 'someusername', name: 'John Doe' }
```
