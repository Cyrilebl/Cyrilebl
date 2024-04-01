This is me breaking into the programming world...

class User {
	name = "Frédéric Voland";
	currentWork = "Writing code";
	hobbies = [
		"Photography",
		"Gym",
		"Staying up late at night"
	];

	getLocation() {
		return "Rennes, France";
	}

	getAmbitions() {
		return Promise.all([
			getAMotorcycle(),
			travel(),
			learnNewLanguage(),
			pilotAGlider(),
			...others
		]);
	}
}
