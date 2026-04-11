<h1>Meet Telly!</h1>

<h2>What is it?</h2>
<i>Telly</i> is an Arduino Nano based gadget that can cycle through different preloaded images (or expressions) to an RGB screen. It is designed to be cheap, low-power and easy to set up. Telly can be mounted to any surface, not just TVs!  It's also designed to be easily modified if you're so inclined. 

<h3>Features: </h3>
<ul>
  <li><b>Emotive Expression:</b> A stylish and express your emotions!</li>
  <li><b>Fully Customizable:</b> Configurable expressions let you add your own face banks.</li>
  <li><b>Rechargeable:</b> Uses lithium batteries which are convenient and easy to use. </li>
  <!-- <li><b>123:</b> </li> -->
</ul>


<h2>How do I use it?</h2>
The expressions are changed by pressing different button combinations on a Nintendo Wii Nunchuk. The code uses simple switch-cases making it easy to modify. 

<h2>Getting Started</h2>
The full instructions are in the linked .pdf file. However, here's the broad strokes:
<ul><b>
  <li>Install code (tvhead_nunctrl.ino) and libraries</li>
  <li>Upload to Arduino</li>
  <li>Solder Arduino to parts</li>
  <li>Attach the parts to your TV Head (or whatever you're attaching this to)</li>
  <li>Make it look pretty!</li>
</b></ul>

<h2>How do I add new expressions?</h2>
I have included a spreadsheet based tool <i>NeoPixel_Bitmap_Tool_w8by16.xlsx</i> that you use to draw and converts it into a string of text that the Arduino can read. You can also check <i>Expression_Bank.txt</i> for a few premade expressions. More details are in the .pdf file! 

<h2>Libraries</h2>

Rob Eisele's Nunchuk I2C Adapter - Converts Nunchuk inputs to Arduino code

https://projecthub.arduino.cc/infusion/using-a-wii-nunchuk-with-arduino-5ec5b7

FastLED - Powers the LED images 

https://github.com/FastLED/FastLED
