  _  _ _     _ _   _      ___           _ 
 | || (_)   (_) |_( )___ | __| _ ___ __| |
 | __ | |_  | |  _|/(_-< | _| '_/ -_) _` |
 |_||_|_( ) |_|\__| /__/ |_||_| \___\__,_|
        |/    
	

###This is me breaking into the programming world...
 


class User {
	name = "Cyril";
	currentWork = "Writing code";
	hobbies = [
		"Sport",
		"Running",
	];
	getLocation() {
		return "Rennes, France";
	}

	getAmbitions() {
		return Promise.all([
			travel(),
			learnNewLanguage()
		]);
	}
}
