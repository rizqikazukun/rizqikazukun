const Greeting = {
	name: 'Rizqi Pratama',
	role: ['Backend', 'Fullstack'],
	hello: function () {
		console.log(`
		Hello, I Am ${this.name}, 
		I Am a ${this.role[Math.floor(Math.random() * this.role.length)]} Developer`)
	}
}

Greeting.hello()

// Expected output:
// Hello, I Am Rizqi Pratama, I Am a Backend Developer 
// or
// Hello, I Am Rizqi Pratama, I Am a Fullstack Developer 

