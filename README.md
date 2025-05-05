# cse102-lab-assignment-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Lab Assignment Solved](https://www.ankitcodinghub.com/product/cse102-lab-assignment-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101312&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Lab Assignment Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Compressing/Decompressing a file using Huffman codes

In this assignment, you are to compress a file using Huffman codes and decompress a file encoded using Huffman codes. The inputs of the program are the following:

<ol>
<li>The name of the input file</li>
<li>The name of the output file</li>
<li>Mode (0/1) : 0 for compression, 1 for decompression</li>
</ol>
Compression Mode:

In compression mode, the input file is the name of the file that needs to be compressed, and the output file is the name of the file that will be created during the compression. The input file contains a sequence of 8-bit characters. The output file stores the metadata for Huffman codes followed by the encoded sequence. The program also prints the Huffman codes for each character in the file in compression mode.

Decompression mode:

In decompression mode, the input file is the file’s name that is created during the compression mode. The output file will be created during the decompression. The decompression algorithm first builds the tree containing Huffman codes using the metadata and then uses the tree to decode the encoded sequence in the input file. The decoded data is written to the output file.

Sample file.

A sample input file (in.txt) is provided for compression. Below are some sample inputs/outputs of your program.

Input

./a.out

Enter the name of the input file

in.txt

Enter the name of the output file

out.txt

Enter mode (0 for compression, 1 for decompression) 0

Output:

a -&gt; 0

c -&gt; 1 0 0

b -&gt; 1 0 1

f -&gt; 1 1 0 0 e -&gt; 1 1 0 1 d -&gt; 1 1 1

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Generating out.txt

Input:

./a.out

Enter the name of the input file

out.txt

Enter the name of the output file

res.txt

Enter mode (0 for compression, 1 for decompression) 1

Output:

Generating res.txt

Validation:

You can run the following command to verify that the decompression is successful. diff in.txt res.txt

The above command should not print anything.

Library functions:

To implement file I/O, you can look at the following library functions: fopen

fclose

fprintf

fscanf ftell etc.

What to submit:

Implement everything in one C file that you need to submit. In addition, also submit a report that answers the following questions:

<ol>
<li>Are you using min-heap in your implementation?</li>
<li>What is the size of the compressed file after compressing the sample input file provided
with the assignment? (Run “du -h out.txt” to obtain the size of the file out.txt).
</li>
<li>Describe the format of the metadata that is stored in the compressed file.</li>
</ol>
</div>
</div>
</div>
</div>
