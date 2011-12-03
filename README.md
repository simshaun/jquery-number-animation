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


Miscellaneous
------

This was originally done to help somebody @
http://stackoverflow.com/questions/8363916/random-number-effect-in-jquery/8364194

You will find a slightly different version I posted at that link, which allows you to specify which number to end on.