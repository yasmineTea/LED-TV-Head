<h1>LED TV Head</h1>

The <i>LED TV Head</i> is an Arduino Nano based gadget that easily cycles through different preloaded images (or expressions) to rgb screens. It is designed to be cheap, low-power and easy to set up. It's also designed to be easily modified if you're so inclined. 

<h2>How do I use it?</h2>
The expressions are changed by pressing different button combinations on a Nintendo Wii Nunchuk. The code uses simple switch-cases making it easy to modify. 

<h2>How do I set it up?</h2>
The full instructions are in the linked .pdf file. However, here's the broad strokes:
<ul>
  <li>Install code and libraries</li>
  <li>Upload to Arduino</li>
  <li>Solder Arduino to parts</li>
  <li>Attach the parts to your TV Head (or whatever you're attaching this to)</li>
  <li>Make it look pretty!</li>
</ul>

<h2>How do I add new expressions?</h2>
I have included a spreadsheet based tool <i>NeoPixel_Bitmap_Tool_w8by16.xlsx</i> that you use to draw and converts it into a string of text that the Arduino can read. You can also check <i>Expression_Bank.txt</i> for a few premade expressions. More details are in the .pdf file! 
