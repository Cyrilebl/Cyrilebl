<h1>This is me breaking into the programming world...</h1>

<script src="js/tmpl.min.js"></script>

 <script type="text/x-tmpl" id="tmpl-demo">
  <h3>{%=o.title%}</h3>
  <p>Released under the
  <a href="{%=o.license.url%}">{%=o.license.name%}</a>.</p>
  <h4>Features</h4>
  <ul>
  {% for (var i=0; i<o.features.length; i++) { %}
      <li>{%=o.features[i]%}</li>
  {% } %}
  </ul>
</script>

<script>class User {
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
} </script>
