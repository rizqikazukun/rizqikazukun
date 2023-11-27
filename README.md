```javascript
const Greeting = {
	name: 'Rizqi Pratama',
	role: ['Backend', 'Fullstack'],
	hello: function () {
		const myRole = Math.floor(Math.random() * this.role.length)
		let message = ''
		message += `Hello, I Am ${this.name} `
		message += `I Am a ${this.role[myRole]} Developer`
		console.log(message)
	}
}

Greeting.hello()

// Expected output:
// Hello, I Am Rizqi Pratama, I Am a Backend Developer 
// or
// Hello, I Am Rizqi Pratama, I Am a Fullstack Developer 
```
