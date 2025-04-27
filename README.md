# cs4225-assignment-1--introduction-and-hadoop-solved
**TO GET THIS SOLUTION VISIT:** [CS4225 Assignment 1- Introduction and Hadoop Solved](https://www.ankitcodinghub.com/product/cs4225-cs5425-big-data-systems-for-data-science-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122194&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4225 Assignment 1- Introduction and Hadoop Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment 1: Introduction and Hadoop

Outline

¢ Description of Tasks 0&amp;1

¢ Submission requirements

Task Overview

¢ Motivation

l Text and documents are big data. Text and document processing is fundamental for many Web applications.

¢ The assignment consists of an example program (Task 0: to help you test your setup and give you an example of a working program, no need to submit it) and the actual task to submit (Task 1):

l Task 0: A simple word count program for testing your setup. Task 1: Given two textual files, count the number of words that are common.

Task 0

¢ This is a simple test program to test your setup and get accustomed to logging in and working with the cluster

¢ The code is already given to you and will not be graded. You can use it as an example of what a working MapReduce program looks like.

¢ To submit this, follow the instructions in the Student Guide sections 3-5. If the test passes and you can successfully submit, it means everything has been set up correctly.

Task 1

Motivation

We choose CommonWords as our task because it is representative, and it is based on WordCount.

Task 1

¢ Problem definition

l Given TWO textual files, for each common word between the two files, find the smaller number of times that it appears between the two files. Output the top 20 common words with highest such frequency (For words with the same frequency, there’s no special requirement for the output order). Example: if the word “John” appears 5 times in the 1st file and 3 times in the 2nd file, the smaller number of times is 3

¢ Requirements

l Split the input text with “(space) ”. Any other tokens like “,.:`” will be regarded as a part of the words

l Remove stop-words as given in Stopwords.txt, such as “a”, “the”, “that”, “of”, … (case sensitive) Sort the common words in descending order of the smaller number of occurrences in the two files. In general, words with different case or different non-whitespace punctuation are considered different words

A Running Example

• Stopwords

– as, had

• File 1

– he put some sugar into his coffee, as he always did.

• File 2

– he had sugar in his coffee, though he is diabetic and he suffer.

• Output:

Sorted frequencies of Common words common words

7

Task 1

¢ TopkCommonWords &lt;input1&gt; &lt;input2&gt; &lt;input3&gt; &lt;output&gt;

¢ Input data are provided the following two source files: • Task1-input1.txt as &lt;input1&gt;

• Task1-input2.txt as &lt;input2&gt; the stop-word file:

• Stopwords.txt as &lt;input3&gt;

¢ Output

l Output directory is specified in &lt;output&gt; Top-20 output of the result using the data files listed above (you only need to extract these 20 output from the sorted output), with each line:

• Freq word , where is tab and creates a new line. An example command can be:

l hadoop jar cm.jar TopkCommonWords commonwords/input/task1-input1.txt commonwords/input/task1-input2.txt commonwords/input/stopwords.txt commonwords/cm_output/

l Note that the ./compile_run script already contains this command. So you can simply test your code using ./compile_run (on the SoC cluster)

¢ You can directly parse the parameters to get the path, and load the file from the path in your codes. In local debugging, you should set system path as parameters. In clusters, you only need to run “compile_run”. The script will automatically upload the files to HDFS and set HDFS path as parameters.

8

Submission Requirements

• Task 0: You can optionally run ./submit on the SoC

cluster to test your setup, but it will not be graded

• Task 1: Run ./submit on the SoC cluster to submit your codes

– When submitting, make sure you input your matriculation number (i.e. starting with capital A), not your email address

– If the ./compile_run script says that the tests passed, and the ./submit script says that you have successfully submitted, then you have completed the assignment, no need to submit anything else.

Marking

• The assignment contains a public dataset ‘data/’ and expected output ‘answer.txt’. If your codes are correct, your output should be the same as ‘answer.txt’. Different orders will also be considered as correct in marking.

• All the codes will be automatically compiled and marked by similar scripts as ‘compile_run’ on a private test dataset

– The private test dataset is very similar to the test data given to

you. If your program gives the correct output on the given test data, it is very likely to give the correct output on the private test data as well.

• So, ensure your codes can be compiled by the script in your

package.

copy others’ codes or share your codes with others.

&nbsp;
