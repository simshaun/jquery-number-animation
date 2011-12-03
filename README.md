Simple number animation plugin.
======

Usage
------

    <span class="number"></span>
    <br>
    <span class="number"></span>

    <script>
	$(function() {
        $(".number").numAnim({
            numNums: 5,
            duration: 3
        });
	});
	</script>


Parameters
------

	Param    | Default         | Description
	-----------------------------------------
    numNums  | 2               | How many numbers to animate.
    -----------------------------------------
	numClass | autogen-num     | Each number is wrapped in a span element with this class name.
	-----------------------------------------
	duration | 5               | In seconds, how long the animation will last.
	-----------------------------------------
	interval | 90              | In ms, how often the numbers are updated.