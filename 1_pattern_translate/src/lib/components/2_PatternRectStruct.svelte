<!-- 
  - HTML und Svelte Code zeigen + Funktionsaufrufe
  - Zeige wie das erste kleine Pattern beginnt (außerhalb der Schleife)

  - 2 Rechtecke in der Schleife und entsprechend der Indizes x, y, width und height anpassen
  - Funktionen müssen sie schreiben 
  - Kleiner Tipp mit data-x um zu sehen welche Indizes die Rects haben
-->

<script>
	const squareCount = 20;
	const squareSize = 1000 / squareCount;

	function calculateSizeCords1(xi, yi) {

	}

	function calculateSizeCords2(xi, yi) {

	}
</script>

<div class="svg-container">
	<svg viewBox="0 0 1000 1000" class="svg-canvas">
	
		<rect transform="translate(0 0)" width={squareSize} height={squareSize / 2} fill="hotpink" />

		<rect
			transform="translate(0 {squareSize / 2})"
			width={squareSize}
			height={squareSize / 2}
			fill="khaki"
		/>

		<rect
			transform="translate({squareSize} 0)"
			width={squareSize / 2}
			height={squareSize}
			fill="hotpink"
		/>
		<rect
			transform="translate({squareSize + squareSize / 2} 0)"
			width={squareSize / 2}
			height={squareSize}
			fill="khaki"
		/>
	</svg>
</div>
