# ecs154a-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [ECS154A-Homework 4 Solved](https://mantutor.com/product/ecs154a-homework-4-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top kksr-disabled" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;74760&quot;,&quot;readonly&quot;:&quot;1&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECS154A-Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h1>Logisim</h1>
<ol>
<li>Use the <a href="https://drive.google.com/file/d/14uDb89VUd5yopoxduOR2lzd34VD3auQH/view?usp=sharing">version from the class Google Drive of Logisim Evolution</a>. Other versions may not work correctly.</li>
<li>Do not rename the files you receive. If you do so you will automatically fail the tester when you submit.</li>
<li>Put your solution for each problem into implementation subcircuit</li>
<li>Do not rename the implementation subcircuit anything else. If you do so you will automatically fail the tester when you submit.</li>
<li>Do not change the appearance of the implementation subcircuit from what it is set as. Doing so will cause you to automatically fail the tester when you submit.
<ol>
<li>That is this field right here</li>
</ol>
</li>
<li>Do not move the pins inside of the implementation subcircuit as that affects the appearance of the circuit on the outside as you saw in discussion. Doing so will cause you to automatically fail the tester when you submit.
<ol>
<li>If you want to “move the pins” instead connect tunnels to the pins and move the tunnels around.</li>
</ol>
</li>
<li>Do not name any of the subcirucits in your solution main. Doing so will cause you to automatically fail the tester when you submit.</li>
<li>You <strong>can </strong>create as many other subcircuits as you want in your solution. Just make sure your solution ends up in the implementation subcircuit</li>
</ol>
<h1>Restrictions</h1>
For all problems in this homework, you may only use

<ul>
<li>All of the components under Wiring</li>
<li>All of the components under Gates <strong>EXCEPT</strong> for Controlled Buffer, Controlled Inverter, PLA</li>
<li>All of the components under Plexers</li>
<li>All of the components under Arithmetic</li>
<li>All of the components under Memory <strong>EXCEPT</strong> for <strong>RAM, ROM, </strong>and <strong>Random</strong> Generator</li>
</ul>
Unless a problem specifies otherwise.

You have been provided a Register File circuit in the starting circuit. The <strong>only outputs</strong> of the register file that you are allowed to use are A_Out and B_Out. The rest are for testing purposes and <strong>should not be used.</strong> Using them will result in a 50% penalty in your grade.

<h1>Problem 1: CPU.circ</h1>
Build a 4-bit single cycle CPU that can implement the given instructions.

<h2>Instruction Format</h2>
Our CPU will be using fixed length instructions. Our CPU will also have two types of instruction formats: R-type and I-type. In R-type instructions both operands come from registers. In I-type instructions, the first operand comes from a register and the second will be contained within the instruction.

<h3>R-Type</h3>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="150">Name</td>
<td width="209">Bits</td>
<td width="265">Description</td>
</tr>
<tr>
<td width="150">OpCode</td>
<td width="209">15 – 12</td>
<td width="265">Determines what operation should be performed</td>
</tr>
<tr>
<td width="150">C</td>
<td width="209">11 – 8</td>
<td width="265">The destination register. The C in Reg<sub>C</sub> = Reg<sub>A</sub> OP Reg<sub>B</sub></td>
</tr>
<tr>
<td width="150">A</td>
<td width="209">7 – 4</td>
<td width="265">The first source register. The A in Reg<sub>C</sub> = Reg<sub>A</sub> OP Reg<sub>B</sub></td>
</tr>
<tr>
<td width="150">B</td>
<td width="209">3 – 0</td>
<td width="265">The second source register. The B in Reg<sub>C</sub> = Reg<sub>A</sub> OP Reg<sub>B</sub></td>
</tr>
</tbody>
</table>
<h3>I-Type</h3>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="150">Name</td>
<td width="209">Bits</td>
<td width="265">Description</td>
</tr>
<tr>
<td width="150">OpCode</td>
<td width="209">15 – 12</td>
<td width="265">Determines what operation should be performed</td>
</tr>
<tr>
<td width="150">C</td>
<td width="209">11 – 8</td>
<td width="265">The destination register. The C in Reg<sub>C</sub> = Reg<sub>A</sub> OP Imm</td>
</tr>
<tr>
<td width="150">A</td>
<td width="209">7 – 4</td>
<td width="265">The first source register. The A in Reg<sub>C</sub> = Reg<sub>A</sub> OP Imm</td>
</tr>
<tr>
<td width="150">Immediate</td>
<td width="209">3 – 0</td>
<td width="265">The second source register. The Imm in Reg<sub>C</sub> = Reg<sub>A</sub> OP Imm</td>
</tr>
</tbody>
</table>
<h2>Instructions</h2>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="208">Operation</td>
<td width="208">Encoding (The value in the OpCodeField)</td>
<td width="208">Description</td>
</tr>
<tr>
<td width="208">STOP</td>
<td width="208">0000</td>
<td width="208">The CPU ceases execution</td>
</tr>
<tr>
<td width="208">NOP</td>
<td width="208">0001</td>
<td width="208">Do nothing</td>
</tr>
<tr>
<td width="208">LOAD</td>
<td width="208">0010</td>
<td width="208">Reg<sub>C</sub> = Immediate</td>
</tr>
<tr>
<td width="208">MOVE</td>
<td width="208">0011</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub></td>
</tr>
<tr>
<td width="208">ANDR</td>
<td width="208">0100</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> AND Reg<sub>B</sub></td>
</tr>
<tr>
<td width="208">ANDI</td>
<td width="208">0101</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> AND Immediate</td>
</tr>
<tr>
<td width="208">ORR</td>
<td width="208">0110</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> OR Reg<sub>B</sub></td>
</tr>
<tr>
<td width="208">ORI</td>
<td width="208">0111</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> OR Immediate</td>
</tr>
<tr>
<td width="208">XORR</td>
<td width="208">1000</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> XOR Reg<sub>B</sub></td>
</tr>
<tr>
<td width="208">XORI</td>
<td width="208">1001</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> XOR Immediate</td>
</tr>
<tr>
<td width="208">NOT</td>
<td width="208">1010</td>
<td width="208">Reg<sub>C</sub> = NOT Reg<sub>A</sub></td>
</tr>
<tr>
<td width="208">NEGATE</td>
<td width="208">1011</td>
<td width="208">Reg<sub>C</sub> = -Reg<sub>A</sub></td>
</tr>
<tr>
<td width="208">ADDR</td>
<td width="208">1100</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> + Reg<sub>B</sub></td>
</tr>
<tr>
<td width="208">ADDI</td>
<td width="208">1101</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> +Immediate</td>
</tr>
<tr>
<td width="208">SUBR</td>
<td width="208">1110</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> – Reg<sub>B</sub></td>
</tr>
<tr>
<td width="208">SUBI</td>
<td width="208">1111</td>
<td width="208">Reg<sub>C</sub> = Reg<sub>A</sub> – Immediate</td>
</tr>
</tbody>
</table>
<h2>Inputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">Instruction</td>
<td width="208">16</td>
<td width="208">The instruction located at Instruction_Address</td>
</tr>
<tr>
<td width="208">ClkIn</td>
<td width="208">1</td>
<td width="208">The Clock. Connect this to the clock ports of your registers/flip-flops. Do nothing else with this.</td>
</tr>
</tbody>
</table>
<h2>Outputs</h2>
<table width="624">
<tbody>
<tr>
<td width="208">Pin</td>
<td width="208">Size (in bits)</td>
<td width="208">Explanation</td>
</tr>
<tr>
<td width="208">Instruction_Address_Out</td>
<td width="208">5</td>
<td width="208">The address of the instruction you want to execute</td>
</tr>
<tr>
<td width="208">Reg0-15</td>
<td width="208">4</td>
<td width="208">The values in the register file. This has already been connected for you</td>
</tr>
</tbody>
</table>
<h2>CPU Components</h2>
Your CPU should have

<ul>
<li>A Program Counter (PC)
<ul>
<li>This stores and keeps track of what instruction you are on</li>
</ul>
</li>
<li>Instruction Decoder
<ul>
<li>This is a bunch of combinational logic that sets the control signals inside of your CPU</li>
</ul>
</li>
<li>Register File
<ul>
<li>A bunch of registers as well as ways to specify which ones you want. This has already been created for you.</li>
</ul>
</li>
</ul>
&nbsp;

<h1>Testing</h1>
Testing for this problem is different than for previous assignments but is more similar to sequential circuits than combinational circuits. After you finish building your circuit and are ready to test it

<ol>
<li>Open the associated grader circuit</li>
<li>Scroll down on the left and side until you find your circuit. Right-click on it and select Reload Library</li>
<li>Use cntrl+t to tick the clock and check that the outputs of the registers are what they are supposed to be as based on the test program below.</li>
<li></li>
<li>The Test Program</li>
</ol>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="208">Instruction</td>
<td width="208">Meaning</td>
<td width="208">Result</td>
</tr>
<tr>
<td width="208">LOAD REG<sub>0</sub>, 3</td>
<td width="208">Reg<sub>0</sub> = 3</td>
<td width="208">Reg<sub>0</sub> = <strong>3</strong></td>
</tr>
<tr>
<td width="208">LOAD REG<sub>1</sub>,6</td>
<td width="208">Reg<sub>1</sub> = 6</td>
<td width="208">Reg<sub>1</sub> = <strong>6</strong></td>
</tr>
<tr>
<td width="208">NOP</td>
<td width="208">Do Nothing</td>
<td width="208">No Change</td>
</tr>
<tr>
<td width="208">MOVE REG<sub>2</sub>, Reg1</td>
<td width="208">Reg<sub>2</sub> = Reg<sub>1</sub></td>
<td width="208">&nbsp;Reg<sub>2</sub> = <strong>6</strong></td>
</tr>
<tr>
<td width="208">ANDR REG<sub>3</sub>, REG<sub>0</sub>, REG<sub>1</sub></td>
<td width="208">REG<sub>3 </sub>= REG<sub>0</sub> AND REG<sub>1</sub></td>
<td width="208">REG<sub>3</sub> = 3 &amp; 6 =<strong> 2</strong></td>
</tr>
<tr>
<td width="208">ANDI REG<sub>4</sub>, REG<sub>3</sub>,3</td>
<td width="208">REG<sub>4 </sub>= REG<sub>3</sub> AND 3</td>
<td width="208">REG<sub>4 </sub>= 2 &amp; 3= <strong>2</strong></td>
</tr>
<tr>
<td width="208">ORR REG<sub>5</sub>, Reg<sub>2</sub>, REG<sub>0</sub></td>
<td width="208">REG<sub>5</sub> = Reg<sub>2</sub> OR REG<sub>0</sub></td>
<td width="208">REG<sub>5</sub> = 6 |3 = <strong>7</strong></td>
</tr>
<tr>
<td width="208">ORI REG<sub>6</sub>, Reg<sub>3</sub>, 12</td>
<td width="208">REG<sub>6</sub> = Reg<sub>3</sub> OR&nbsp; 12</td>
<td width="208">REG<sub>6</sub> = 2 OR&nbsp; 12 = <strong>14</strong></td>
</tr>
<tr>
<td width="208">XORR REG<sub>7</sub>, Reg<sub>2</sub>, REG<sub>0</sub></td>
<td width="208">REG<sub>7</sub> = Reg<sub>2</sub> XOR REG<sub>0</sub></td>
<td width="208">REG<sub>7</sub> = 6 ^ 3 = <strong>5</strong></td>
</tr>
<tr>
<td width="208">XORI REG<sub>8</sub>, Reg<sub>6</sub>, 15</td>
<td width="208">REG<sub>8</sub> = Reg<sub>6</sub> XOR 15</td>
<td width="208">REG<sub>8</sub> =14 ^15 = <strong>1</strong></td>
</tr>
<tr>
<td width="208">NEG REG<sub>9</sub>, REG<sub>3</sub></td>
<td width="208">REG<sub>9</sub> = -REG<sub>3</sub></td>
<td width="208">REG<sub>9</sub> = <strong>-2</strong></td>
</tr>
<tr>
<td width="208">ADDR REG<sub>10</sub>, Reg<sub>7</sub>, REG<sub>7</sub></td>
<td width="208">REG<sub>10</sub> = Reg<sub>7</sub> + REG<sub>7</sub></td>
<td width="208">REG<sub>10</sub> = 5 + 5 = <strong>10</strong></td>
</tr>
<tr>
<td width="208">ADDI REG<sub>11</sub>, Reg<sub>1</sub>, 3</td>
<td width="208">REG<sub>11</sub> = Reg<sub>1</sub> + 3</td>
<td width="208">REG<sub>11</sub> = 6 + 3 = <strong>9</strong></td>
</tr>
<tr>
<td width="208">SUBR REG<sub>12</sub>, Reg<sub>6</sub>, REG<sub>2</sub></td>
<td width="208">REG<sub>12 </sub>= Reg<sub>6</sub> – REG<sub>2</sub></td>
<td width="208">REG<sub>12 </sub>= 14 – 6 =<strong> 8</strong></td>
</tr>
<tr>
<td width="208">SUBI REG<sub>13</sub>, Reg<sub>8</sub>, 5</td>
<td width="208">REG<sub>13</sub> = Reg<sub>8</sub> – 5</td>
<td width="208">REG<sub>13</sub> = 1 – 5 = <strong>-4</strong></td>
</tr>
<tr>
<td width="208">NOT REG<sub>15</sub>, REG<sub>8</sub></td>
<td width="208">REG<sub>15</sub> = NOT REG<sub>8</sub></td>
<td width="208">REG<sub>15</sub> = ~1 = <strong>14</strong></td>
</tr>
<tr>
<td width="208">ANDR REG<sub>1</sub>, REG<sub>12</sub>, REG<sub>13</sub></td>
<td width="208">REG<sub>1</sub> = REG<sub>12</sub> AND REG<sub>13</sub></td>
<td width="208">REG<sub>1</sub> = 8 &amp; 12 = <strong>8</strong></td>
</tr>
<tr>
<td width="208">NEG REG<sub>5</sub>, REG<sub>5</sub></td>
<td width="208">REG<sub>5</sub> = -REG<sub>5</sub></td>
<td width="208">REG<sub>5</sub> = <strong>-7</strong></td>
</tr>
<tr>
<td width="208">NOP</td>
<td width="208">Do Nothing</td>
<td width="208">No Change</td>
</tr>
<tr>
<td width="208">ADDR REG<sub>14</sub>, REG<sub>5</sub>, REG<sub>2</sub></td>
<td width="208">REG<sub>14</sub> = Reg<sub>5</sub> + REG<sub>2</sub></td>
<td width="208">REG<sub>14 </sub>= -7 + 6 = <strong>-1</strong></td>
</tr>
<tr>
<td width="208">XORR REG<sub>7</sub>, REG<sub>7</sub>, REG<sub>14</sub></td>
<td width="208">REG<sub>7</sub> =&nbsp; Reg<sub>7</sub> ^ REG<sub>14</sub></td>
<td width="208">REG<sub>7</sub> = 5 ^ -1 = <strong>10</strong></td>
</tr>
<tr>
<td width="208">ORI REG<sub>2</sub>, REG<sub>2</sub>, 3</td>
<td width="208">REG<sub>2</sub> = Reg<sub>2</sub> | 3</td>
<td width="208">REG<sub>2</sub> = 6 | 3 = <strong>7</strong></td>
</tr>
<tr>
<td width="208">SUBI REG<sub>13</sub>, REG<sub>13</sub>, 12</td>
<td width="208">REG<sub>13</sub> = REG<sub>13</sub> – 12</td>
<td width="208">REG<sub>13</sub> = 12 – 12 = <strong>0</strong></td>
</tr>
<tr>
<td width="208">STOP</td>
<td width="208">CPU should cease execution</td>
<td width="208">CPU should cease execution</td>
</tr>
<tr>
<td width="208">LOAD REG<sub>15</sub>, 13</td>
<td width="208">This line should not be executed because the CPU should have STOPped already</td>
<td width="208">This line should not be executed because the CPU should have STOPped already</td>
</tr>
</tbody>
</table>
&nbsp;

The test program is just an <strong>example program.</strong> Your CPU should function on <strong>any program</strong> given to it.

&nbsp;

<h1>Making Fixes to Your Solution</h1>
After you make changes to your solution you will need to reload your circuit in the grader circuit. If you don’t it won’t see the updates. To reload your circuit, select your circuit in the grader, right-click it and select Reload Library.
