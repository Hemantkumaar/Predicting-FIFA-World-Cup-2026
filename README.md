# Predicting-FIFA-World-Cup-2026
Predicting FIFA World Cup 2026 match outcomes using historical football data, SQL database integration, and machine learning in Python. Combines team performance, rankings, player statistics, and weather conditions to model match probabilities and analyze how contextual factors influence tournament results.

## Soundtrack (Waka Waka)

The web simulation includes a continuous audio track that plays from the
first page through the final. It looks for a file named `champion.mp3` in
the `Simulation/` directory (and `site/Simulation/` for the preview copy).
To use *"Waka Waka (This Time for Africa)" by Shakira* as requested:

1. Download or obtain the MP3 legally and place it in `Simulation/`:
	```sh
	cd Simulation
	# rename or copy your file
	cp /path/to/waka-waka.mp3 champion.mp3
	```

2. Optionally do the same in `site/Simulation/` if you're testing the
	static preview server.

The audio will begin on the first user interaction and continue across
page navigations thanks to localStorage state. You can replace the file
with any other track by updating the filename or the `src` attributes in
the HTML.

