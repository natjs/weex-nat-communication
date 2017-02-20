# nat-communication

## Installation
```
weexpack plugin add nat-communication
```

```
npm install weex-nat --save
```

## Usage

Use in weex file (.we)

```html
<script>
import 'Nat' from 'weex-nat'

// make a phone call
Nat.call('415-736-0000')

// send short message
Nat.sms('415-736-0000')

// send e-mail
Nat.mail('hi@natjs.com')

</script>
```

See the Nat [Documentation](http://natjs.com/) for more details.
