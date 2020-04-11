

<div style="white-space: pre; background-color:#f2f2f2" id="textArea">
// Template for blink activity
void setup() {
  // initialize digital pin 7 to be output
  pinMode(7, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
    //TODO turn the LED on
    
    delay(1000);              // wait for a second           
    //TODO turn the LED off
    
    delay(1000);              // wait for a second
}
</div>

<button onclick="myFunction('textArea')">Copy text</button>


<script>
function myFunction(elementId) {
    var range = document.createRange();
     range.selectNode(document.getElementById(elementId));
     window.getSelection().addRange(range);
     document.execCommand("copy");
}

</script>
