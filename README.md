```javascript
const Greeting = {
	name: 'Rizqi Pratama',
	role: ['Backend', 'Fullstack'],
	hello: function () {
		let message = ''
		message += `Hello, I Am ${this.name} `
		message += `I Am a ${this.role[Math.floor(Math.random() * this.role.length)]} Developer`
		console.log(message)
	}
}

Greeting.hello()

// Expected output:
// Hello, I Am Rizqi Pratama, I Am a Backend Developer 
// or
// Hello, I Am Rizqi Pratama, I Am a Fullstack Developer 
```
