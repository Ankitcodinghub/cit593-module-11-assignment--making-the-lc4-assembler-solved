# cit593-module-11-assignment--making-the-lc4-assembler-solved
**TO GET THIS SOLUTION VISIT:** [CIT593 Module 11 Assignment -Making the LC4 Assembler Solved](https://www.ankitcodinghub.com/product/cit593-module-11-assignment-making-the-lc4-assembler-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;133480&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIT593 Module 11 Assignment  -Making the LC4 Assembler Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

<h1>Assignment Overview</h1>
From lecture you’ve learned that C is file-oriented and that working with files represents I/O&nbsp; devices in C.

C files fall into two categories: “text” and “binary”. In this assignment you’ll&nbsp; work with both types by reading in a text file and writing out a binary file.

You will read an arbitrary .asm file (a text file intended to be read by PennSim) and write a .obj file (the same type of binary file that PennSim would write out).

Aside from reading and writing out the files, your task will be to make a mini-LC4- Assembler! An assembler is a program that reads in assembly language and generates its machine equivalent.

This assignment will require a bit more programming rigor than we’ve had thus far, but now that you’ve gained a good amount of programming skill in this class and in others, it is the&nbsp; perfect time to tackle a large programming assignment (which is why the instructions are so many pages).

&nbsp;

<h1>Learning Objectives</h1>
This assignment will cover the following topics:

<ul>
<li>Review the LC4 Object File Format</li>
<li>Read text files and process binary files</li>
<li>Assemble LC4 programs into executable object files</li>
<li>Use debugging tools such as GDB</li>
</ul>
&nbsp;

<h1>Advice</h1>
<ul>
<li>Start early</li>
<li>Ask for help early</li>
<li>Do not try to do it all in one day</li>
</ul>
&nbsp;

&nbsp;

<h1></h1>
<h1>Getting Started</h1>
<h2>Codio Setup</h2>
Open the Codio assignment via Canvas.&nbsp; This is necessary to link the two systems.

You will see many files.&nbsp; At the top-level workspace directory, the main files are&nbsp; asm_parser.h, asm_parser.c, assembler.c, and PennSim.jar.

Do not modify any of the directories or any file in any of the directories.

<h2>Starter Code</h2>
We have provided a basic framework and several function definitions that you must implement.

<table width="628">
<tbody>
<tr>
<td width="184">assembler.c</td>
<td width="444">– must contain your main function.</td>
</tr>
<tr>
<td width="184">asm_parser.c</td>
<td width="444">– must contain your asm_parser functions.</td>
</tr>
<tr>
<td width="184">asm_parser.h</td>
<td width="444">– must contain the definition for ROWS and COLS

– must contain function declarations for read_asm_file, parse_instruction, parse_reg, parse_add, parse_mul, str_to_bin, write_obj_file, and any helper function you implement in asm_parser.c
</td>
</tr>
<tr>
<td width="184">test1.asm</td>
<td width="444">– example assembly file</td>
</tr>
<tr>
<td width="184">PennSim.jar</td>
<td width="444">– a copy of PennSim to check your assembler</td>
</tr>
</tbody>
</table>
&nbsp;

<h2>Object File Format Refresher</h2>
The following is the format for the binary .obj files created by PennSim from your .asm files. It represents the contents of memory (both program and data) for your assembled LC-4 Assembly programs. In a .obj file, there are 3 basic sections indicated by 3 header “types” = Code , Data, and Symbol:

<ul>
<li>Code: 3-word header (xCADE, &lt;address&gt;, &lt;n&gt;), n-word body comprising the instructions.
<ul>
<li>This corresponds to the .CODE directive in assembly.</li>
</ul>
</li>
<li>Data: 3-word header (xDADA, &lt;address&gt;, &lt;n&gt;), n-word body comprising the initial data values.
<ul>
<li>This corresponds to the .DATA directive in assembly.</li>
</ul>
</li>
<li>Symbol: 3-word header (xC3B7, &lt;address&gt;, &lt;n&gt;), n-character body comprising the symbol string. These are generated when you create labels (such as “END”) in assembly. Each symbol is its own section.
<ul>
<li>Each character in the file is 1 byte, not 2 bytes.</li>
<li>There is no NULL</li>
</ul>
</li>
</ul>
&nbsp;

&nbsp;

<h1></h1>
<h1>Requirements</h1>
<h2>General Requirements</h2>
<ul>
<li>You <strong>MUST NOT</strong> change the filenames of any file provided to you in the starter code.</li>
<li>You <strong>MUST NOT</strong> change the function declarations of any function provided to you in the starter code.</li>
<li>You <strong>MAY</strong> create additional helper functions. If you do, you <strong>MUST</strong> correctly declare the functions in the appropriate header file and provide an implementation in the appropriate source file.</li>
<li>Your program <strong>MUST</strong> compile when running the command make.</li>
<li>You <strong>MUST NOT</strong> have any compile-time errors or warnings.</li>
<li>You <strong>MUST</strong> remove or comment out all debugging print statements before submitting.</li>
<li>You <strong>MUST NOT</strong> use externs or global variables.</li>
<li>You <strong>MAY</strong> use h, stdlib.h, and stdio.h.</li>
<li>You <strong>SHOULD</strong> comment your code since this is a programming best practice.</li>
<li>Your program <strong>MUST</strong> be able to handle .asm files that PennSim would successfully assemble. We will not be testing with invalid .asm</li>
<li>Your program <strong>MUST NOT</strong> crash/segmentation fault.</li>
<li>You <strong>MUST</strong> provide a makefile with the following targets:
<ul>
<li>assembler</li>
<li>o</li>
<li>all, clean, clobber</li>
</ul>
</li>
</ul>
&nbsp;

<h2>Assembler</h2>
<h3>assembler.c: main</h3>
<ul>
<li>You <strong>MUST</strong> not change the first four instructions already provided.</li>
<li>The main function:
<ul>
<li><strong>MUST</strong> read the arguments provided to the program.
<ul>
<li>the user will use your program like this:

./assembler test1.asm</li>
</ul>
</li>
<li><strong>MUST</strong> store the first argument into filename.</li>
<li><strong>MUST</strong> print an error1 message if the user has not provided an input filename.</li>
<li><strong>MUST</strong> call read_asm_file to populate program[][].</li>
<li><strong>MUST</strong> parse each instruction in program[][] and store the binary string equivalent into program_bin_str[][].</li>
<li><strong>MUST</strong> convert each binary string into an integer (which <strong>MUST</strong> have the correct value when formatted with “0x%X”) and store the value into program_bin[].</li>
<li><strong>MUST</strong> write out the program into a .obj object file which <strong>MUST</strong> be loadable by PennSim’s ld</li>
</ul>
</li>
</ul>
<h3>asm_parser.c: read_asm_file</h3>
This function reads the user file.

<ul>
<li>It <strong>SHOULD</strong> return an error2 message if there is any error opening or reading the file.</li>
<li>It <strong>MAY</strong> try to check if the input program is too large for the defined variables, but we will not be testing outside the provided limits.</li>
<li>It <strong>MUST</strong> read the exact contents of the file into memory, and it <strong>MUST</strong> remove any newline characters present in the file.</li>
<li>It <strong>MUST</strong> work for files that have an empty line at the end and also for files that end on an instruction (i.e. do not assume there will always be an empty line at the end of the file).</li>
<li>It <strong>MUST</strong> return 0 on success, and it <strong>MUST</strong> return a non-zero number in the case of failure (it <strong>SHOULD</strong> print a useful error message and return 2 on failure).</li>
</ul>
&nbsp;

<h3>asm_parser.c: parse_instruction</h3>
This function parses a single instruction and determines the binary string equivalent.

<ul>
<li>It <strong>SHOULD</strong> use strtok to tokenize the instruction, using spaces and commas as the delimiters.</li>
<li>It <strong>MUST</strong> determine the instruction function and call the appropriate parse_xxx helper function.</li>
<li>It <strong>MUST</strong> parse ADD, MUL, SUB, DIV, AND, OR, XOR
<ul>
<li>It <strong>MUST</strong> parse ADD IMM and AND IMM if attempting that extra credit.</li>
</ul>
</li>
<li>It <strong>MUST</strong> return 0 on success, and it <strong>MUST</strong> return a non-zero number in the case of failure (it <strong>SHOULD</strong> print a useful error message and return 3 on failure).</li>
</ul>
&nbsp;

<h3>asm_parser.c: parse_add</h3>
This function parses an ADD instruction and provides the binary string equivalent.

<ul>
<li>It <strong>MUST</strong> consider the first argument to be the full instruction.</li>
<li>It <strong>MUST</strong> correctly update the opcode, sub-opcode, and register fields following the LC4 ISA.</li>
<li>It <strong>SHOULD</strong> call a helper function parse_reg, but we will not be testing this function.</li>
<li>It <strong>MUST</strong> return 0 on success, and it <strong>MUST</strong> return a non-zero number in the case of failure (it <strong>SHOULD</strong> print a useful error message and return 4 on failure).</li>
</ul>
&nbsp;

&nbsp;

<h3></h3>
<h3>asm_parser.c: parse_xxx</h3>
You <strong>MUST</strong> create a helper function similar to parse_add for the other instruction functions required in parse_instruction.

<ul>
<li>They <strong>MUST</strong> consider the first argument to be the full instruction.</li>
<li>They <strong>MUST</strong> correctly update the opcode, sub-opcode, and register fields following the LC4 ISA.</li>
<li>They <strong>SHOULD</strong> call a helper function parse_reg, but we will not be testing this function.</li>
<li>They <strong>MUST</strong> return 0 on success, and they <strong>MUST</strong> return a non-zero number in the case of failure (it <strong>SHOULD</strong> print a useful error message and return a unique error number on failure).</li>
</ul>
&nbsp;

<h3>asm_parser.c: str_to_bin</h3>
This function converts a C string containing 1s and 0s into an unsigned short integer

<ul>
<li>It <strong>MUST</strong> correctly convert the binary string to an unsigned short int which can be verified using the “0x%X”</li>
<li>It <strong>SHOULD</strong> use strtol to do the conversion.</li>
</ul>
&nbsp;

<h3>asm_parser.c: write_obj_file</h3>
This function writes the program, in integer format, as a LC4 object file using the LC4 binary format.

<ul>
<li>It <strong>MUST</strong> output the program in the LC4 binary format described in lecture and in the <a href="#_heading=h.6bisvzex9z5c">Object File Format Refresher</a></li>
<li>It <strong>MUST</strong> create and write an empty file if the input file is empty</li>
<li>It <strong>MUST</strong> change the extension of the input file to .obj.</li>
<li>It <strong>MUST</strong> use the default starting address 0x0000 unless you are attempting the .ADDR extra credit.</li>
<li>It <strong>MUST</strong> close the file with fclose.</li>
<li>It <strong>MUST</strong> return 0 on success, and they <strong>MUST</strong> return a non-zero number in the case of failure (it <strong>SHOULD</strong> print a useful error message and return 7 on failure).</li>
<li>The generated file <strong>MUST</strong> load into PennSim (and you MUST check this before submitting), and the contents <strong>MUST</strong> match the .asm assembly program</li>
</ul>
&nbsp;

<h2></h2>
<h2>Extra Credit</h2>
You may attempt any, all, or none of these extra credit options.&nbsp; You <strong>MUST</strong> test using your own generated examples (we will not provide any).

Option 1: modify your read_asm_file function to ignore comments in .asm files.&nbsp; You <strong>MUST</strong> handle all types of comments for credit.

Option 2: modify your program to handle ADD IMM and AND IMM instructions.&nbsp; Both <strong>MUST</strong> work completely for credit.

Option 3: modify your program to handle the .CODE and .ADDR directives.

Option 4: modify your program to handle the .DATA, .ADDR, and .FILL directives.

&nbsp;

<h1>Suggested Approach</h1>
This is a <em>suggested</em> approach.&nbsp; You are not required to follow this approach as long as you follow all of the other requirements.

<h2>High Level Overview</h2>
Follow these high-level steps and debug thoroughly before moving on to the next.

<ol>
<li>Initialize all arrays to zero or ‘\0’</li>
<li>Call read_asm_file to read the entire .asm file into the array program[][].
<ol>
<li>Using test1.asm as an example, after read_asm_file returns: program[][] should then contain:</li>
</ol>
</li>
</ol>
<table width="645">
<tbody>
<tr>
<td width="45"></td>
<td width="49"><strong>0</strong></td>
<td width="41"><strong>1</strong></td>
<td width="38"><strong>2</strong></td>
<td width="38"><strong>3</strong></td>
<td width="38"><strong>4</strong></td>
<td width="38"><strong>5</strong></td>
<td width="38"><strong>6</strong></td>
<td width="38"><strong>7</strong></td>
<td width="38"><strong>8</strong></td>
<td width="38"><strong>9</strong></td>
<td width="38"><strong>10</strong></td>
<td width="38"><strong>11</strong></td>
<td width="38"><strong>12</strong></td>
<td width="44"><strong>13</strong></td>
<td width="48"><strong>14</strong></td>
</tr>
<tr>
<td width="45"><strong>0</strong></td>
<td width="49">‘A’</td>
<td width="41">‘D’</td>
<td width="38">‘D’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘0’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘1’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>1</strong></td>
<td width="49">‘M’</td>
<td width="41">‘U’</td>
<td width="38">‘L’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘1’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>2</strong></td>
<td width="49">‘S’</td>
<td width="41">‘U’</td>
<td width="38">‘B’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘1’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>3</strong></td>
<td width="49">‘D’</td>
<td width="41">‘I</td>
<td width="38">‘V’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘2’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>4</strong></td>
<td width="49">‘A’</td>
<td width="41">‘N’</td>
<td width="38">‘D’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘3’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>5</strong></td>
<td width="49">‘O’</td>
<td width="41">‘R’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="44">‘\0’</td>
<td width="48">X</td>
</tr>
<tr>
<td width="45"><strong>6</strong></td>
<td width="49">‘X’</td>
<td width="41">‘O’</td>
<td width="38">‘R’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="44">‘2’</td>
<td width="48">‘\0’</td>
</tr>
<tr>
<td width="45"><strong>7</strong></td>
<td width="49">‘\0’</td>
<td width="41">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="44">X</td>
<td width="48">X</td>
</tr>
</tbody>
</table>
&nbsp;

<ol>
<li>In a loop, for each row X in program[][]:
<ol>
<li>Call parse_instruction, passing it the current row in program[X][] as input to parse_instruction. When parse_instruction returns, program_bin_str[X][] should be updated to have the binary equivalent (in string form).</li>
<li>Call str_to_bin passing program_bin_str[X][] to it. When str_to_bin returns, program_bin[X] should be updated to have the hexadecimal equivalent of the binary string from program_bin_str[X].</li>
</ol>
</li>
</ol>
&nbsp;

<ol>
<li>Once the loop is complete program_bin_str[][] should contain program[][] equivalent:</li>
</ol>
<table width="622">
<tbody>
<tr>
<td width="34"></td>
<td width="40"><strong>0</strong></td>
<td width="30"><strong>1</strong></td>
<td width="34"><strong>2</strong></td>
<td width="34"><strong>3</strong></td>
<td width="34"><strong>4</strong></td>
<td width="34"><strong>5</strong></td>
<td width="34"><strong>6</strong></td>
<td width="34"><strong>7</strong></td>
<td width="34"><strong>8</strong></td>
<td width="34"><strong>9</strong></td>
<td width="34"><strong>10</strong></td>
<td width="34"><strong>11</strong></td>
<td width="34"><strong>12</strong></td>
<td width="34"><strong>13</strong></td>
<td width="34"><strong>14</strong></td>
<td width="34"><strong>15</strong></td>
<td width="42"><strong>16</strong></td>
</tr>
<tr>
<td width="34"><strong>0</strong></td>
<td width="40">‘0’</td>
<td width="30">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>1</strong></td>
<td width="40">‘0’</td>
<td width="30">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>2</strong></td>
<td width="40">‘0’</td>
<td width="30">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">0</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>3</strong></td>
<td width="40">‘0’</td>
<td width="30">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>4</strong></td>
<td width="40">‘0’</td>
<td width="30">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>5</strong></td>
<td width="40">‘0’</td>
<td width="30">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>6</strong></td>
<td width="40">‘0’</td>
<td width="30">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="34">‘1’</td>
<td width="34">‘0’</td>
<td width="42">‘\0’</td>
</tr>
<tr>
<td width="34"><strong>7</strong></td>
<td width="40">‘\0’</td>
<td width="30">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="34">X</td>
<td width="42">X</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<ol>
<li>Also after the loop is complete, the array program_bin[] should contain program_bin_str[][]’s equivalent in binary (formatted in hexadecimal here):</li>
</ol>
<table width="103">
<tbody>
<tr>
<td width="36"><strong>0</strong></td>
<td width="67">0x1201</td>
</tr>
<tr>
<td width="36"><strong>1</strong></td>
<td width="67">0x1449</td>
</tr>
<tr>
<td width="36"><strong>2</strong></td>
<td width="67">0x1691</td>
</tr>
<tr>
<td width="36"><strong>3</strong></td>
<td width="67">0x12DA</td>
</tr>
<tr>
<td width="36"><strong>4</strong></td>
<td width="67">0x5283</td>
</tr>
<tr>
<td width="36"><strong>5</strong></td>
<td width="67">0x52D2</td>
</tr>
<tr>
<td width="36"><strong>6</strong></td>
<td width="67">0x52DA</td>
</tr>
</tbody>
</table>
program_bin[] now represents the completely assembled program.

<ol>
<li>Write out the .obj file in binary using the <a href="#_heading=h.6bisvzex9z5c">LC4 Object File Format</a>.</li>
</ol>
&nbsp;

<h2></h2>
<h2>Great High Level Overview, but I really need a Slightly More Detailed Overview</h2>
Okay, I guess we can give some more details.

&nbsp;

<h3>Part 0: Setup the main Function to Read the Arguments</h3>
Open assembler.c from the helper files; it contains the main function for the program.&nbsp; Carefully examine the variables at the top:

char* filename = NULL ;

char program [ROWS][COLS] ;

char program_bin_str [ROWS][17] ;

unsigned short int program_bin [ROWS] ;

The first pointer variable filename is a pointer to a string that contains the text file you’ll be reading. Your program must take in as an argument the name of a .asm file. As an example, once you compile your main program, you would execute it as follows:

&nbsp;

./assembler test1.asm

&nbsp;

In the last assignment you learned how to use the arguments passed into main. So the first thing to implement is to check argc to see if the program has received any arguments.&nbsp; If it does, point filename to the argument that contains the passed in string that is the file’s name. You should return from main immediately after printing an error message if the caller doesn’t provide an input file name.&nbsp; For example, something like this:

&nbsp;

error1: usage: ./assembler &lt;assembly_file&gt;.asm

&nbsp;

Start by updating assembler.c to read in the arguments and store the filename. Compile your changes and test them before continuing.

&nbsp;

<h3>Part 1: Read the .asm File</h3>
The next thing to do is to actually read the file into memory.&nbsp; main’s next call will be

&nbsp;

int read_asm_file (char* filename, char program [ROWS][COLS] ) ;

&nbsp;

The purpose of read_asm_file is to open the .asm file, and place its contents into the 2D array program[][]. You must complete the implementation of this function in the provided helper file asm_parser.c.

&nbsp;

Notice that it takes in the pointer to the filename that you’ll open in this function. It also takes in the two dimensional array, program, that was defined back in main.

&nbsp;

You’ll also see that ROWS and COLS are two #define’d macros in asm_parser.h.&nbsp; ROWS is set to 100 and COLS is set to 255. This means that you can only read in a program that is up to 100 lines long and each line of this program can be no longer than 255.&nbsp; When the program compiles, the compiler will replace all instances of ROWS with 100 and all instances of COLS with 255.&nbsp; This means you can #define these values once to avoid <a href="https://en.wikipedia.org/wiki/Magic_number_(programming)">Magic Numbers</a> and simplify your program.

&nbsp;

You’ll want to look at the class notes (or a C reference textbook) to use fopen to open the filename that has been passed in. Then you’ll want to use a function like fgets to read each

line of the .asm file into the program[][] 2D array. Be aware that fgets will keep carriage returns (aka the newline character) and you’ll need to strip these from the input.

&nbsp;

Take a look at test1.asm file that was included in the helper file. It contains the following program:

&nbsp;

ADD R1, R0, R1

MUL R2, R1, R1

SUB R3, R2, R1

DIV R1, R3, R2

AND R1, R2, R3

OR R1, R3, R2

XOR R1, R3, R2

&nbsp;

&nbsp;

After you complete read_asm_file and run it on test1.asm, your 2D array program[][] would contain the contents of the .asm file in this order:

<table width="640">
<tbody>
<tr>
<td width="38"></td>
<td width="43"><strong>0</strong></td>
<td width="34"><strong>1</strong></td>
<td width="38"><strong>2</strong></td>
<td width="38"><strong>3</strong></td>
<td width="38"><strong>4</strong></td>
<td width="38"><strong>5</strong></td>
<td width="38"><strong>6</strong></td>
<td width="38"><strong>7</strong></td>
<td width="38"><strong>8</strong></td>
<td width="38"><strong>9</strong></td>
<td width="38"><strong>10</strong></td>
<td width="38"><strong>11</strong></td>
<td width="38"><strong>12</strong></td>
<td width="47"><strong>13</strong></td>
<td width="60"><strong>14</strong></td>
</tr>
<tr>
<td width="38"><strong>0</strong></td>
<td width="43">‘A’</td>
<td width="34">‘D’</td>
<td width="38">‘D’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘0’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘1’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>1</strong></td>
<td width="43">‘M’</td>
<td width="34">‘U’</td>
<td width="38">‘L’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘1’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>2</strong></td>
<td width="43">‘S’</td>
<td width="34">‘U’</td>
<td width="38">‘B’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘1’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>3</strong></td>
<td width="43">‘D’</td>
<td width="34">‘I</td>
<td width="38">‘V’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘2’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>4</strong></td>
<td width="43">‘A’</td>
<td width="34">‘N’</td>
<td width="38">‘D’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘3’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>5</strong></td>
<td width="43">‘O’</td>
<td width="34">‘R’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘2’</td>
<td width="47">‘\0’</td>
<td width="60">X</td>
</tr>
<tr>
<td width="38"><strong>6</strong></td>
<td width="43">‘X’</td>
<td width="34">‘O’</td>
<td width="38">‘R’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘1’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="38">‘3’</td>
<td width="38">‘,’</td>
<td width="38">‘ ‘</td>
<td width="38">‘R’</td>
<td width="47">‘2’</td>
<td width="60">‘\0’</td>
</tr>
<tr>
<td width="38"><strong>7</strong></td>
<td width="43">‘\0’</td>
<td width="34">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="38">X</td>
<td width="47">X</td>
<td width="60">X</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

Notice there are no newline characters at the end of these lines.

&nbsp;

If reading in the file is a success, return 0 from the function.&nbsp; If not, return 2 from the function and print an error to the screen:

&nbsp;

error2: read_asm_file failed

&nbsp;

Implement and test this function carefully before continuing on with the assignment.

&nbsp;

&nbsp;

<h3>Part 2: Parse an Instruction</h3>
You only need to parse the following instructions: ADD, MUL, SUB, DIV, AND, OR, XOR.&nbsp; You do not need to implement AND IMM or AND IMM unless you want to attempt the extra credit.

&nbsp;

Once read_asm_file is working properly, go back in main, and call parse_instruction, which is also located in asm_parser.c:

&nbsp;

int parse_instruction (char* instr, char* instr_bin_str) ;

&nbsp;

<h4>Purpose, Arguments, and Return Value</h4>
The purpose of this function is to take in a single row of your program[][] array and convert to its binary equivalent in text form (as a string of 1s and 0s). The argument instr must point to a row in main’s 2D array program[][]. The argument instr_bin_str must point to the corresponding row in main’s 2D array program_bin_str[][].

If there no errors are encountered the function will return a 0 and if any error occurs in this function it should print an error message such as:

&nbsp;

error3: parse_instruction failed

&nbsp;

return the number 3 immediately.

Let’s assume you’ve called parse_instruction and instr points to the first row in your program[][] array:

&nbsp;

<table width="613">
<tbody>
<tr>
<td width="87"></td>
<td width="34"><strong>0</strong></td>
<td width="34"><strong>1</strong></td>
<td width="34"><strong>2</strong></td>
<td width="34"><strong>3</strong></td>
<td width="34"><strong>4</strong></td>
<td width="34"><strong>5</strong></td>
<td width="34"><strong>6</strong></td>
<td width="34"><strong>7</strong></td>
<td width="34"><strong>8</strong></td>
<td width="34"><strong>9</strong></td>
<td width="34"><strong>10</strong></td>
<td width="34"><strong>11</strong></td>
<td width="34"><strong>12</strong></td>
<td width="34"><strong>13</strong></td>
<td width="50"><strong>14</strong></td>
</tr>
<tr>
<td width="87">*instr</td>
<td width="34">‘A’</td>
<td width="34">‘D’</td>
<td width="34">‘D’</td>
<td width="34">‘ ‘</td>
<td width="34">‘R’</td>
<td width="34">‘1’</td>
<td width="34">‘,’</td>
<td width="34">‘ ‘</td>
<td width="34">‘R’</td>
<td width="34">‘0’</td>
<td width="34">‘,’</td>
<td width="34">‘ ‘</td>
<td width="34">‘R’</td>
<td width="34">‘1’</td>
<td width="50">‘\0’</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

parse_instruction needs to examine this string and convert it into a binary equivalent. You’ll need to use the LC4 ISA to determine the binary equivalent of an instruction. When your function returns, the memory pointed to by instr_bin_str, should look like this:

&nbsp;

<table width="729">
<tbody>
<tr>
<td width="113"></td>
<td width="38"><strong>0</strong></td>
<td width="38"><strong>1</strong></td>
<td width="37"><strong>2</strong></td>
<td width="37"><strong>3</strong></td>
<td width="38"><strong>4</strong></td>
<td width="35"><strong>5</strong></td>
<td width="37"><strong>6</strong></td>
<td width="35"><strong>7</strong></td>
<td width="36"><strong>8</strong></td>
<td width="33"><strong>9</strong></td>
<td width="33"><strong>10</strong></td>
<td width="34"><strong>11</strong></td>
<td width="34"><strong>12</strong></td>
<td width="36"><strong>13</strong></td>
<td width="35"><strong>14</strong></td>
<td width="35"><strong>15</strong></td>
<td width="45"><strong>16</strong></td>
</tr>
<tr>
<td width="113">*instr_bin_str</td>
<td width="38">‘0’</td>
<td width="38">‘0’</td>
<td width="37">‘0’</td>
<td width="37">‘1’</td>
<td width="38">‘0’</td>
<td width="35">‘0’</td>
<td width="37">‘1’</td>
<td width="35">‘0’</td>
<td width="36">‘0’</td>
<td width="33">‘0’</td>
<td width="33">‘0’</td>
<td width="34">‘0’</td>
<td width="34">‘0’</td>
<td width="36">‘0’</td>
<td width="35">‘0’</td>
<td width="35">‘1’</td>
<td width="45">‘\0’</td>
</tr>
</tbody>
</table>
&nbsp;

Notice this isn’t actually binary, but it is the ADD instruction’s binary equivalent in text (C String) form. We will convert this string form of the binary instruction to an integer (hexadecimal) later.

<h4>How to implement this function</h4>
The purpose of converting the instruction to a binary string (instead of to the binary number it will eventually become), is so that you can build this string up little by little.

&nbsp;

Investigate the strtok function in the standard C string library if you haven’t already done so for the last assignment.

&nbsp;

strtok allows you to parse a string that is separated by delimiters. In this function you’ll be parsing the string pointed to by instr and you’ll be building up the string pointed to by instr_bin_str. instr will contain spaces and commas (those will be your delimiters).

&nbsp;

Your first call to strtok on the instr string should return back the instruction function: ADD, SUB, MUL, DIV, XOR, etc. The only thing common to all 26 instructions in the ISA is that the very first part of them is the instruction function (e.g. ADD). Once you determine the instruction function, you’ll call the appropriate helper function to parse the remainder of the instruction.

&nbsp;

As an example, let’s say the instruction function is ADD. Once you’ve determined the instruction function is ADD, you would call the parse_add helper function. It will take the instruction instr as an argument, but also the instr_bin_str string because parse_add will be responsible for determining the binary equivalent for the ADD instruction you are currently working on and it will update instr_bin_str.

&nbsp;

int parse_add (char* instr, char* instr_bin_str ) ;

&nbsp;

When parse_add returns, and if no errors occurred during parsing the ADD instruction, instr_bin should now be complete. At this time, you can return 0 from parse_instruction.&nbsp; If you encounter any errors in this function, you should print an error3 message and return 3.

&nbsp;

This is only the first instruction.&nbsp; main will need to do this for each row of program[][], using strtok to get the instruction function, calling the appropriate parse_xxx helper function to finish the instruction, and updating instr_bin_str appropriately.

&nbsp;

&nbsp;

&nbsp;

<h3>Part 3: Parse an ADD Instruction</h3>
This function is specific to parsing the ADD instruction, but you will need to write a similar function for each of the different instruction functions.

&nbsp;

The helper function parse_add should be called only by the parse_instruction function. It has two char* arguments: instr and instr_bin_str.

&nbsp;

int parse_add (char* instr, char* instr_bin_str ) ;

<strong>&nbsp;</strong>

Because this function will only be called when parse_instruction encounters an ADD instruction function, instr will contain an ADD instruction and instr_bin_str should be empty.

&nbsp;

Similar to the other functions, if this function encounters no errors it will return 0 and if any error occurs&nbsp; it should return 4 after printing an error4 message

&nbsp;

error4: parse_add() failed

&nbsp;

The purpose of this function is to populate instr_bin_str. Upon the function’s start, the binary opcode can be immediately copied into instr_bin_str[0:3]. Afterwards, strtok can tokenize the remaining string to separate out the registers RD, RS, and RT, from the instr string.

&nbsp;

For each register, call the parse_reg helper function:

&nbsp;

int parse_reg (char reg_num, char* instr_bin_str) ;

<strong>&nbsp;</strong>

This function must take a number in character form and populate instr_bin_str with the appropriate corresponding binary number. For example, if RD = R<strong>0</strong> for the ADD instruction, the ‘0’ character would be passed in the argument reg_num.&nbsp; parse_reg then copies the characters 000 into instr_bin_str[4:6].

&nbsp;

parse_reg should return 5 if any errors occur after printing a standard error5 message; otherwise it returns 0 upon success.

&nbsp;

To implement the parse_reg function, consider using a switch() statement:

This helper function should only parse one register at a time. Also, because it is not specific to the ADD instruction (nearly all instructions contain registers), you can call it from other functions that need their registers converted to binary. Example: parse_mul should also call parse_reg.

&nbsp;

Note that parse_add must also populate the sub-opcode field in instr_bin_str[10:12]. When parse_add returns, instr_bin_str should be complete. parse_instrunction should then return to main.

<strong>&nbsp;</strong>

You will need to create a helper function for each instruction type, use parse_add as a model. As an example, you’ll need to create parse_mul, parse_xor, etc.&nbsp; They will all be very similar functions, so perfect parse_add before you attempt the other functions.

&nbsp;

<h3>Part 4: Converting the binary string to an hexadecimal formatted integer</h3>
After parse_instruction returns successfully to main, main should call str_to_bin:

&nbsp;

unsigned short int str_to_bin (char* instr_bin_str) ;

&nbsp;

This function should be passed the recently parsed binary string from the array program_bin_str[X], where X represents the binary instruction that was just populated by the last call to parse_instruction.

&nbsp;

The purpose of this function is to take a binary string and convert it to a 16-bit binary equivalent and return it to the calling function. To implement this function, we recommend using strtol. If strtol returns 0, print an error6 message and return 6.

&nbsp;

As an example of what this function should do, if it was called with the following argument:

<table width="697">
<tbody>
<tr>
<td width="114"></td>
<td width="37"><strong>0</strong></td>
<td width="33"><strong>1</strong></td>
<td width="32"><strong>2</strong></td>
<td width="34"><strong>3</strong></td>
<td width="32"><strong>4</strong></td>
<td width="35"><strong>5</strong></td>
<td width="33"><strong>6</strong></td>
<td width="34"><strong>7</strong></td>
<td width="32"><strong>8</strong></td>
<td width="36"><strong>9</strong></td>
<td width="33"><strong>10</strong></td>
<td width="36"><strong>11</strong></td>
<td width="35"><strong>12</strong></td>
<td width="33"><strong>13</strong></td>
<td width="35"><strong>14</strong></td>
<td width="32"><strong>15</strong></td>
<td width="41"><strong>16</strong></td>
</tr>
<tr>
<td width="114">*instr_bin_str</td>
<td width="37">‘0’</td>
<td width="33">‘0’</td>
<td width="32">‘0’</td>
<td width="34">‘1’</td>
<td width="32">‘0’</td>
<td width="35">‘0’</td>
<td width="33">‘1’</td>
<td width="34">‘0’</td>
<td width="32">‘0’</td>
<td width="36">‘0’</td>
<td width="33">‘0’</td>
<td width="36">‘0’</td>
<td width="35">‘0’</td>
<td width="33">‘0’</td>
<td width="35">‘0’</td>
<td width="32">‘1’</td>
<td width="41">‘\0’</td>
</tr>
</tbody>
</table>
&nbsp;

then it should return: 0x1201, which is the hexadecimal equivalent for this binary string. You can verify and print out what it returns by using printf(“0x%X”), which will print out integers in hexadecimal format.

&nbsp;

Once str_to_bin is returned, it should be assigned to the corresponding spot in the unsigned&nbsp; short int array program_bin[X], where X matches the index from program_bin_str[X].

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h3>Part 5: Writing the .obj object file</h3>
During lecture, we learned that a .obj file is a binary file and discussed the format of the file. Recall from lecture that the .obj file’s CODE header is as follows:

3-word header (xCADE, &lt;address&gt;, &lt;n&gt;), n-word body comprising the instructions. This corresponds to the .CODE directive in assembly.

<em>&nbsp;</em>

Given this information, the last function to implement is:

&nbsp;

int write_obj_file (char* filename, unsigned short int program_bin[ROWS] ) ;

&nbsp;

The purpose of this function is to take the assembled program, represented in hexadecimal in program_bin[] and output it to a file with the extension: .obj. It must encode the file using the .obj file format specified in class. If test1.asm was pointed to by filename, your program would open up a file to write to called: test1.obj.

&nbsp;

This function should do the following:

<ol>
<li>Take the filename passed in the argument filename, change the last 3 letters to “obj”</li>
<li>Open up that file for writing and in binary format. The file you’ll create is <strong>not</strong> a text file, these are not C Strings you’re writing, they are binary numbers.</li>
<li>Write out the first word in the header: 0xCADE.</li>
<li>Write out the address your program should be loaded at.&nbsp; 0x0000 is the default.</li>
<li>Count the number of rows that contain data in program_bin[], then write out &lt;n&gt;</li>
<li>Now that the header is complete, write out the &lt;n&gt; rows of data in program_bin[]</li>
<li>Close the file using fclose.</li>
</ol>
&nbsp;

If any errors occur, print an appropriate error message and return 7. Otherwise return 0 and main should then return 0 to the caller.&nbsp; Your program is now complete.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>Testing</h1>
<h2>Validate Output with PennSim</h2>
Once you have successfully written an object file from an assembly file, examine the .obj file’s contents using the Linux utility hexdump. From the Linux terminal prompt type:

&nbsp;

hexdump test1.obj

&nbsp;

hexdump will show you the binary contents. Make certain it matches your expectations!

Depending on how you write out your files, you may encounter endianness variations. Look carefully at the file I/O lecture slides to understand endianness. Your .obj file must have the correct endianness to be loaded into PennSim.

&nbsp;

As an example, for the program described in the Suggested Approach, the expected hexdump would be:

0000000 deca 0000 0700 0112 4914 9116 da12 8352

0000010 d252 da52

0000014

Note that the first column indicates the byte index, and that hexdump prints 16 bytes per line (so the next line starts at 0000010).&nbsp; Further notice that the first byte is deca, which is cade but with the bytes swapped due to how Linux handles endianness.

<strong>&nbsp;</strong>

<strong>You must test your .obj files in PennSim before submission.&nbsp; If they fail to load, you should expect little, if any, credit for this assignment.</strong>

&nbsp;

It is your responsibility to test out files other than test1.asm. Also, you must test your .obj files by loading them into PennSim and seeing if they work! Please do this before submitting

your work. We will be testing your programs with different .asm files, so you should try out different .asm files of your own.

<h2></h2>
<h2>Files for Testing</h2>
We are only providing test1.asm for testing.&nbsp; However, you can (and should) create additional files that test different parts of the program.

For these test files, bring up PennSim, assemble it, and check the .obj file contents with hexdump.&nbsp; Then read it into your program and see if you can assemble it into the same object file. You can create a bunch of test cases very easily with PennSim.

You should test your assembler program on a variety of .asm files, not just simple examples.

<h2></h2>
&nbsp;

<h2></h2>
<h2>Unit Testing</h2>
When writing such a large program, it is a good strategy to “unit test.” This means, as you create a small bit of working code, compile it, and create a simple test for it.

<strong>DO NOT</strong> write the entire program, compile it, and then start testing it. You will never resolve all of your errors this way. You need to unit test your program as you go along or it will be impossible to debug.

&nbsp;

<h2>GDB for Debugging</h2>
Using gdb to debug your program is also highly recommended and is actually required before asking for help on ED or during office hours.&nbsp; The first thing the TAs will ask is if you have done this; if not, they will ask you to do it.&nbsp; This is a required part of the learning experience and you’ll want this skill to succeed in 595.

While it may seem easy to use print statements, they quickly clutter your program and require commenting out/deleting when you no longer need them (and inevitably uncommenting/undeleting when you need to debug again).

gdb allows you to inspect the actual contents of memory which is an advantage over print statements because print statements only print ASCII characters.&nbsp; Further, you can see the actual contents of memory of any variable at any time, while print statements only print when you call the print statement during the execution of your program.

Plus, you’ll have to use it for 595 so you may as well get some practice in now.

Reminder: you will need to add the -g flag to all intermediate compilation steps, not just the assembler target, and you will need to use the –args command to tell gdb that you have arguments to your program:

gdb -q -tui –args ./assembler test1.asm

<h1>Submission</h1>
<h2>Submission Checks</h2>
There is a single “submission check” test that runs once you upload your code to Gradescope.&nbsp; This test checks that you have submitted all four required files and also that your program compiles and any autograder code compiles successfully.&nbsp; It does not run your program or provide any input on whether it works or not.&nbsp; This check just ensures that all the required components exist.&nbsp; This test is performed after uploading to Gradescope.

Ensure that you are passing this check before closing Gradescope.&nbsp; If you are not passing this check, please reach out to TAs for troubleshooting assistance.

<h2>The Actual Submission</h2>
You will submit this assignment to Gradescope in the assignment entitled <strong>Assignment 11: File I/O, Making the LC4 Assembler</strong>.

Download all of your .c source and .h header files and your Makefile from Codio to your computer, then Upload all four of these files to the Gradescope assignment.

You should not submit any of the provided or your own .asm testing files.

You have unlimited submissions until the deadline, after which late penalties apply as noted in the syllabus.

We will only grade the last submission uploaded.

Do not mark your Codio workspace complete.&nbsp; Only the submission in Gradescope will be used for grading purposes.

There is no page matching and no academic integrity submission for autograder assignments.

<h1>Grading</h1>
We will only grade the last submission, regardless of the results of any previous submission.

We will not be providing partial credit for autograder tests.

You may ask for feedback by submitting a regrade request using the Miscellaneous Adjustments rubric item.

<h2>Assembler</h2>
We do provide one example that we will test with, so you can be sure to get those points.&nbsp; You will have to figure out the rest yourself.

This assignment is worth 200 points, normalized to 100% for gradebook purposes.

00 points: submission check.&nbsp; This is the only test visible to you until we publish scores after the deadline and manual grading.

20 points: correct makefile

30 points: general code inspection (manually graded)

10 points: handling command line arguments and writing the correct file

20 points: correctly handle endianness

60 points: correctly processing test1.asm (which we provide to you)

60 points: correctly processing our other test files (which we do not provide to you)

&nbsp;

<h2>Extra Credit</h2>
The Extra Credit is worth 11 percentage points so the highest grade on the assignment is 111%.

Your extra credit must not break functionality for the non-extra credit requirements.&nbsp; Make a backup of your finalized program before attempting the extra credit.&nbsp; If your program fails to meet the basic requirements, you will end up losing more points than the extra credit will gain.

There is no partial credit.&nbsp; It must work completely for any credit.

We will not give guidance on how to do these since they are designed to be challenge problems.

&nbsp;

2 percentage points: modify your read_asm_file function to ignore comments in .asm files.&nbsp; You must handle all types of comments for credit.

2 percentage points: modify your program to handle ADD IMM and AND IMM instructions.&nbsp; Both must work completely for credit (no partial credit for one instruction).

5 percentage points: modify your program to handle the .CODE and .ADDR directives.&nbsp; As a hint, you will need another array to hold the addresses, e.g. unsigned short int address[ROWS].

2 percentage points: modify your program to handle the .DATA directive.

&nbsp;

&nbsp;

<h2></h2>
<h2>An Important Note of Plagiarism</h2>
<ul>
<li>We will scan your assignment files for plagiarism using an automatic plagiarism detection tool.</li>
<li>If you are unaware of the plagiarism policy, make certain to check the syllabus to see the possible repercussions of submitting plagiarized work (or letting someone submit yours).</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

<h1></h1>
<h1>FAQ</h1>
<h2>Quick Hints</h2>
These are some hints provided by TAs.

<ul>
<li>You are allowed to use the switch statement, a compact way to handle long if/then blocks.</li>
<li>We won’t be testing with string literals in the unit testing.</li>
<li>You do not need a script file, but you can certainly add one to automate your own testing.</li>
<li>We will only be testing with valid .asm That is, all the test files will assemble correctly in PennSim.</li>
<li>You can raise an error if the register number for Rx is not valid (e.g. R8), but again, we will not be testing with invalid files.</li>
</ul>
<h2></h2>
<h2>Formatting</h2>
<ul>
<li>We will not test with blank lines between instructions, even though PennSim can assemble these without error.</li>
<li>We do not expect you to use a regex to check if the instruction matches a format.</li>
<li>Lines can end with trailing spaces, a newline, or just EOF (end of file) if it is the last line in the .asm</li>
<li>strtok is sufficient to break the instruction into the different parts (hint: use a delimiter of ” ,”). The Assignment 10 instructions has a link to a good resource.</li>
<li>All characters will be uppercase, except for x for hexadecimal values (which only applies to some of the extra credit challenges and they will never be X), even though PennSim can assemble these without error.</li>
</ul>
<h2></h2>
<h2>Endianness</h2>
<ul>
<li>The x86 (the processor used by Codio) has a different endianness than the LC4. When doing fread()’s of 2 byte words, swapping occurs to adjust for this. That same swapping doesn’t occur with the fgetc() or fread()’s with size 1.</li>
<li>If you read the .obj file into memory one word at a time using fread(), you will need to swap for endianness. In contrast, if you choose to read the .obj file into memory one byte at a time with fgetc(), the endianness doesn’t need to be adjusted. However, you will have to combine two bytes into a word using bitwise operators.</li>
</ul>
&nbsp;

&nbsp;

<h1></h1>
<h1>Resources</h1>
<ul>
<li>strtok reference

<a href="https://www.tutorialspoint.com/c_standard_library/c_function_strtok.htm">https://www.tutorialspoint.com/c_standard_library/c_function_strtok.htm</a></li>
<li>switch statement reference

<a href="https://www.tutorialspoint.com/cprogramming/switch_statement_in_c.htm">https://www.tutorialspoint.com/cprogramming/switch_statement_in_c.htm</a></li>
<li>strtol reference

<a href="https://www.tutorialspoint.com/c_standard_library/c_function_strtol.htm">https://www.tutorialspoint.com/c_standard_library/c_function_strtol.htm</a></li>
</ul>
&nbsp;
