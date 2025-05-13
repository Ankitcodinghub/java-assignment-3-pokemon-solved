# java-assignment-3-pokemon-solved
**TO GET THIS SOLUTION VISIT:** [Java Assignment 3-Pokemon Solved](https://www.ankitcodinghub.com/product/java-assignment-3-pokemon-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92261&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Assignment 3-Pokemon Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

1. [Easy] Room Escape

You are called as the Ultimate Programmer (超高校级的程序员). Once you woke up and found that you are stuck in a mysterious room. On the walls there are many strings that you don’t know what it means.

A strange voice informs you that the password includes 3 parts of puzzles. You need to figure out all these puzzles to get out of this room! Don’t worry, as you are the best programmer, use your super coding ability to solve them!

1.1 Method getFence()

Description

On the wall there is a string which ends with a integer N. You immediately noticed that it is a Fence cipher(栅栏密码). The rule is that every N letters in this English string should be divided into a group. Then the group should be printed out in a specific order.

For example: If the input is HLEOL2 , then HLEOL will be divided into 3 groups as HL , EO and L . Then it should take the first letter of each group, then the second letter. By this rearrangement, you will get HELLO .

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicstaticStringgetFence(Stringcipher)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
to take in the cipher as input and return the decrypted

</div>
</div>
<div class="layoutArea">
<div class="column">
Please implement a method

string.

Sample

Input Parameter:

cipher: “PCSOEHGDAIO4”

Return Value: “PEACHISGOOD”

1.2 Method getCaesar()

Description

Beside the fence cipher, there are also several strings with a integer N. You noticed that it could be the Caesar Cipher(凯撒密码)! The integer N must be how many letters are shifted in alphabet between the cipher and plain.

For example: if the cipher is ALD and N is 3 , 3 means that the letter order should be shifted as A- &gt;D , L-&gt;O and D-&gt;G . At last the plain will be DOG .

Please implement a method getCaesar() to take in the cipher and N as input and return the decrypted string.

Sample

Input Parameters:

cipher: Q TJ WQTW

N: 3

Return Value: T WM ZTWZ

All the plain-texts returned should be an English string without lowercase.

1.3 Method getAnswer()

Description

You are near to victory now, ultimate programmer!

Finally, you discover a piece of paper with a table on it. You know it is definitely Vigenere Cipher(维吉尼亚密码)! Also, the paper tells you that the final passward should be decrypted by the following way:

consider the decrypted string by Caesar Cipher as the cipher of Vigenere Cipher consider the first M digits of the decrypted string by Fence Cipher as the key of Vigenere Cipher

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicstaticStringgetCaesar(Stringcipher,intN)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicstaticStringgetAnswer(StringfenceCipher,StringcaesarCipher,int caesarN, int M)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
The table below shows the decryption method using cipher, key in Vigenere Cipher.

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
getFence()

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
For example, if the cipher is C , the key is H , find where the row C and column H intersects, which is J.

If the cipher is AOPKE , the key is AB , expand the length of key by repeating the key, to the length of cipher like ABABA . Then, do the corresponding decryption as taught.

Please implement a method getAnswer() to take in the origin Fence Cipher fenceCipher , the origin Caesar Cipher caesarCipher , caesarN and the length M of the key as input and return the final answer.

Sample

Input Parameters:

fenceCipher: PCSOEHGDAIO4 caesarCipher: Q TJ WQTW caesarN: 3

M: 5

Return Value: I AM BALD

All the plain-texts should be returned without lowercase.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
1.4 Main Procedure

Now you have implemented 3 super useful ultimate decrypting methods. They will be used in main procedure to solve all the puzzles in this room:

Input Format

First line is the cipher of Fence Cipher fCipher

Second line is the cipher of Caesar Cipher cCipher

Third line only contains the shift value of Caesar Cipher cN Fourth line only contains the value M

Agreement on data range:

For Fence Cipher, we guarantee that

fCipher will be a continuous string in only English followed by an integer.

the groups value N used in this decryption is an integer in range [1, 9], no bigger than

the length of cipher-text.

For Caesar Cipher, we guarantee that

cCipher will not only contain English. Please only decrypt the English part and keep the others.

For the shift value N , we guarantee that

For M , we guarantee that .

When doing the last decryption, Please only decrypt the English part and keep the others.

When decrypting non-English part, the key will NOT go to the next digit.

Sample Sample input

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>PCSOEHGDAIO4
Q TJ WQTW
3
5
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
Sample output

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 IAMBALD

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2. [Hard] Danganronpa

Monokuma leads you to a room through a secret entrance. “This is the class trial field! It’s a special place that will decide your fates!” Monokuma says, “Don’t be afraid, the trial is not designed for you. Instead, I’d like you to use JAVA helping me solve some problems in the class trial”, says the Monokuma.

“Puhuhuhuhuhu… in order to explain my rules more clearly, please look at the brochure!” After saying that, Monokuma gives you the following message:

Hint

1. Large input data, you may need Java Fast IO in https://github.com/Penguin134/CS102A22S12 2. You are likely to encounter TLE in this question, which is quite normal. So, you need a more

efficient way to solve TYPE 3 event and the Final Task.

3. We provide a solution: hash code (Algorithm: ripemd128)

<pre>     30557199a7502078b04d8ba665a4e5c5
</pre>
Problem Description

There will be events in a class trial. All the events can be classified as 3 types. TYPE 1: A participant (excluding you) declare his/her statement (a string).

You’d better storage the statement in ArrayList&lt;&gt; stm for further uasge.

TYPE 2: You blast a Truth Bullet (a string).

At the initial state, you have a specific value of Influence Gauge. In each event of TYPE 2 you should do

the following operations:

Storage the Truth Bullet in ArrayList&lt;&gt; tb for further uasge.

Your Influence Gauge will increase by 1 .

Return and print the median (integer) of the length of the statements L .

The medium of is defined as the element of after it is sorted. For example:

If stm = [“ab”,”abcdef”,”abcd”] , then length = [2,5,4] . After sorted,

. Hence, the median L is the element of length , which is 4 .

For special cases:

Return and print 0 when no one has put forward any statement.

If your Influence Gauge I is less than L , your Influence Gauge will decrease by the number of

statements now.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 ArrayList&lt;String&gt;stm=newArrayList&lt;String&gt;();

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
<td>
<div class="layoutArea">
<div class="column">
= [2,4,5]

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
length

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
ATTENTION: You should consider ALL the statements here. These steps should be completed in sequence

TYPE 3: Question Time.

Return and print how many pairs of &lt;statement,Truth Bullet&gt; are matched. Here we define a pair of string &lt;a,b&gt; is matched if and only if a equals b and a is provided earlier than b . For example:

When 1st event happens, stm = [“Monokuma”],tb = [] there is no matched pair. When 2nd event happens, stm = [“Monokuma”],tb = [“Monokuma”] there is one matched pair.

When 3rd event happens, stm = [“Monokuma”,”Monokuma”],tb = [“Monokuma”] there is still one matched pair because the second element in stm is provided later than first element in tb .

ATTENTION: You should consider ALL the statements before the Truth Bullets here.

Final Task: After all the event happened, you should tell Monokuma whether you can win the class trial. Here is an equation for you to calculate your final score:

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public static int counterStatements(){} // Return the median length of
statements
public static void alterInfluenceGauge(int k){} // Alter the value of
Influence Gauge
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicstaticintpairMatch(){}//Returnthenumberofpairmatched

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Where :

is the return value of counterStatements() when event

is the return value of pairMatch() when event happens. will be given as the input.

Now, you should do:

</div>
<div class="column">
happens.

</div>
</div>
<div class="layoutArea">
<div class="column">
Print Qi Fei when

Print Fail when OR if your Influence Gauge (no matter the ).

</div>
</div>
<div class="layoutArea">
<div class="column">
drops below 0 in any TYPE 2 event ATTENTION: You should not change the value of Influence Gauge while calculating .

</div>
</div>
<div class="layoutArea">
<div class="column">
Input Format:

1st line contains two intergers and . 2nd line contains n intergers, indicating 3rd ~ (2+ )th line are the events:

For type 1, each line contains a number 1 and a string s. String s denotes the content of the event.

For type 2, each line contains a number 2 and a string s. String s denotes the content of the event.

For type 3, each line contains only one number 3 , denoting the type of event.

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Output Format:

For every event, you should follow this output format:

For event TYPE 1, you shouldn’t print anything.

For event TYPE 2 and TYPE 3, you should print a number in one line. And finally you should print whether you win the trial or not.

Agreement on data range:

We ensure that there won’t be any blank space in a single string.

Samples Sample input 1

Sample output 1

Explanation 1

First Line is the return value of counterStatements() , second line is the return value of pairMatch() .

Sample input 2

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
3 100

111

1 ImsureByakuyaduckedunderthetable 2 ImsureByakuyaduckedunderthetable 3

</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
32

1

Qi Fei

</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
70

2 5 -3 -1 2 1 0

1 No

1 Hemust’veseenthekillertaketheknife 1 ItwassodarkIcouldn’tseemyfood

1 Butitwassuperpitchblack

2I

2 No

3

</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Sample output 2

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
23 23 1 Fail

</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Explanation 2

</div>
</div>
<div class="layoutArea">
<div class="column">
Thus, your Influence Gauge becomes less than 0 at the 5th events. You fail the trial.

Sample input 3

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
60

114514

1 Thekillerbroughtthemtothecrimescene

1 Ifyoujustusecommonsense

1 Whatiftheglowingpaintwasthemark

1 Inactually,theknifewasfoundunderthetable 3

1 thetablewasbothmarked

</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Sample output 3

Explanation 3

It’s okay that you didn’t say anything before the end. Maybe that’s the so-called win effortlessly 😅.

Question 3-6 Pokémon

Designer: Zhou Junhong, Liu ZhiChen

Tester: Nie Qiushi, Wang Biao, Zhang Shaofeng

Description:

Máo máo and Fatherpucci are freshmen at SUSTech. When they were about to experience university life, they found that the State Press and Publication Administration had issued a “Notice on Further Strict Management to Effectively Prevent Minors from Indulging in Online Games”. Because they are under 18, they are limited to playing games for 3 hours a week. However, they just took the Java course, they plan to write a Pokémon game by themselves. The main framework has been set up. Please help them to complete the code together.

3. [Easy] Skill (5 points)

Design a class named Skill . It describes the information of a certain skill and will be used in Battle .

3.1. Attributes:

private String name : Represents skill’s name.

private int cd : Represents skill’s Cool Down Time, it will be released when the cd is 0 in the battle.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
10

2 QiFei

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
: Represents skill’s damage while releasing.

3.2. Constructors:

NOTICE:

Please check the validity of the parameters: All int type parameters should be greater than 0. If

any invalid parameter is detected, please set the attributes to default values:

The detailed cd description will be explained in the battle. 3.3. Getters:

In these getters, please just return the corresponding attributes.

Notice that we don’t need any setters as the attributes are not required to be modified by other

classes.

Submission:

For this question, submit one java file: Skill.java .

4. [Easy] Pokemon (15 points)

Design a class named Pokemon . Pokemon will fight in the battle .

4.1. Attributes:

private String name : Represents Pokémon’s name such as “Pikachu”.

private int hp : Represents Pokémon’s remaining health.

private int atk : Represents Pokémon’s normal attack damage.

private int level : Represents Pokémon’s level.

private int speed : Represents Pokémon’s agility which will determine the order of attack. private int rateAtk : Represents Pokémon’s atk increased per level.

private int rateHp : Represents Pokémon’s hp increased per level.

Skill skill : Represents Pokémon’s skill.

NOTICE:

To simplify the question, each Pokémon has only one skill.

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicSkill(Stringname,intcd,intatk)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 name=”error”;cd=51;atk=0;

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public String getSkillName()
public int getSkillCd()
public int getSkillAtk()
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>private int atk
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="section">
<div class="layoutArea">
<div class="column">
4.2. Constructors:

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicPokemon(Stringname,inthp,intatk,Skillskills,intlevel,int speed, int rateAtk, int rateHp)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
NOTICE:

You don’t need to check the data input, we guarantee the validity of the data input.

4.3 Setters:

In these setters, please just replace the corresponding attribute of the object with the input parameter.

4.4. Getters:

In these getters, please just return the corresponding attributes. 4.5. Other Methods:

4.5.1. levelUP

This method will be called to increase Pokémon’s level by input parameter up , which represents the number of levels it will increase. Meanwhile, its atk and hp will also increase by the functions below:

4.5.2. learnSkill

Pokémon will learn the skill of the input parameter skill , this will usually happened during a level up. However, you are NOT required to judge when to invoke this method because it will be called manually when we test.

NOTICE:

You are free to design other methods to help you complete this assignment, including but not limited to getters and setters.

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public void setHp(int hp)
public void setAtk(int atk)
public void setSpeed(int speed)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public int getSpeed()
public int getHp()
public int getAtk()
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicvoidlevelUP(intup)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicvoidlearnSkill(Skillskill)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 11">
<div class="section">
<div class="layoutArea">
<div class="column">
Submission

For this question, submit two java files: Pokemon.java , Skill.java .

5. [Medium] Player (15 points)

You need to write a public class named Player, which is used to create player account and store

player data (which are pokemons).

(PS: The name of all variables must strictly match the name bolded in the question) 5.1. Attributes:

You are required to write member variables account, password, mail, phoneNumber into the class.

private final String account : account number, generated by method generateAccount() described in 5.6

private String password

private Mail mail

<pre>     private PhoneNumber phoneNumber
</pre>
ArrayList&lt;Pokemon&gt; pokemons : an ArrayList to store Pokémons owned by this player. Don’t forget to create an ArrayList object with new .

You need to write two additional classes named Mail and PhoneNumber, each has a String to store mail or phone number, and a constructor. What you need to pay attention to is the all members must be private, because you need to keep your data safe. However, the member in Mail and PhoneNumber is not required to be private. Your Mail and PhoneNumber should be two classes declared in the file Player.java .

The validity of the structure of mail and phone number are not the point we check, so you don’t need to verify the validity of their structure.

5.2. Constructors:

You need to write three constructors for each of the three situations for creating an account: 1.Using mail to create an account.

2.Using phone number to create an account.

3.Using both to create an account.

5.3. Checkers:

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public Player(Mail mail, String password)
public Player(PhoneNumber phoneNumber,String password)
public Player(Mail mail, PhoneNumber phoneNumber,String password)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public boolean checkIdentity(Mail mail, String password)
public boolean checkIdentity(PhoneNumber phoneNumber, String password)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
You need to write two methods to check the identity of player when he/she logs in. Only when the data input is match the data you stored means the player passes it successfully. If succeed return true, else return false.

5.4. Setters:

You need to write two methods to set (or to change) the mail or phone number. You need to check the player’s identity first, after that you can change the data. If succeed return true, else return false.

5.5. Getters:

In these getters, please just return the corresponding attributes. 5.6. Account Generator:

You need to write a method that can generate account automatically. The account must be a random number string with length 7, and the first number of it can’t be 0.

Attention:

1. This method should be invoked when you create an account. The return value should be assigned to the attribute account .

2. Once your account is created, it can’t be changed anymore.

5.7. Change Password:

You need to write two method to change your password. You need to check the player’s identity first, after that you can change the password. If succeed return true, else return false.

5.8. Add Pokemon:

You need to write a method to add Pokémon to the ArrayList&lt;Pokemon&gt; pokemons . We ensure the input Pokémon object is valid.

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public boolean setMail(PhoneNumber phoneNumber, String password, Mail mail)
public boolean setPhoneNumber(Mail mail, String password, PhoneNumber
phoneNumber)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2 3

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public String getAccount()
public Mail getMail()
public PhoneNumber getPhoneNumber()
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicStringgenerateAccount()

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>public boolean changePassword(PhoneNumber phoneNumber, String oldPassword,
String newPassword)
public boolean changePassword(Mail mail,String oldPassword, String
newPassword)
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicvoidaddPokemon(Pokemonpokemon)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Submission:

For this question, submit three java files: , , . PS: Your Mail and PhoneNumber should be two classes declared in the file

</div>
<div class="column">
.

</div>
</div>
<div class="layoutArea">
<div class="column">
6. [Hard] Battle (20 points)

After finished the class Player and Pokemon, you finally can write a battle system. You are

required to write a class named Battle, which contains only one static method named tatakai. 6.1 tatakai:

The process of a battle is as below. I know this should be a hard time, but please read the following text carefully:

Process

The round limit is 50.

First you need to input two players p1 and p2. Then you should get the first Pokémon from the two players’ pokemon list seperately. Compare these two Pokémons’ speed, the faster one will start first (if same, then p1 start first). After these preparations, the battle starts.

Pokémons attack each other in each turn. The rule of generating damages is:

If Pokémon has skill, it will use its skill in the battle when the cd is reached. The cd starts calculating at the moment when the Pokémon get into the stage, when the cd is reached, Pokémon will replace its normal attack by skill. The skill can be used infinite times. When the skill is released, it start to count cd again.

If one Pokémon’s hp comes to 0, this round over and this Pokémon will quit the stage. The Pokémon whose hp is not 0 will stay on the stage. The player who lost his Pokémon should let his next Pokémon get into the stage, and do speed judge again to decide which side starts first, and repeat the battle above, until one player loses all his Pokémons, or the round has reach the limit, the game is over.

When the game is over, the one who still have Pokémon is the winner, you should return this player. If the round has reach the limit (at the end of round 50) and no one lose, the game ends in a draw, and you should return null instead of player.

Also, before return statement, the hp of all the Pokémons should be refilled to its initial value. NOTICE:

The round you record over the upper limit of the number of rounds and the round you used to calculate when to release the skill are not the same round.

We ensure the two Players both have at least one Pokémon in the list when tatakai.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
pok1.atk;

</div>
</div>
<div class="layoutArea">
<div class="column">
pok1.hp -= pok2.atk;

</div>
</div>
<div class="layoutArea">
<div class="column">
Player.java Pokemon.java Skill.java Player.java

</div>
</div>
<table>
<tbody>
<tr>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 publicstaticPlayertatakai(Playerp1,Playerp2)

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
pok2.hp -=

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
pokemons

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Submission:

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="section">
<div class="layoutArea">
<div class="column">
For this question, submit four java files: , , Pokemon.java , Skill.java .

Test Procedure Sample

</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3 4 5

6 7 8 9

<pre>10
11
12
13
14
15
16
17
18
19
</pre>
<pre>20
21
22
23
24
25
26
27
28
29
30
31
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Battle.java

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
1 2

3 4 5 6 7 8 9

10

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>player1 = new Player(new Mail("1@mail.sustech.edu.cn"), new
PhoneNumber("1"), "1");
player2 = new Player(new Mail("2@mail.sustech.edu.cn"),new PhoneNumber("2"),
"2");
Skill skill1 = new Skill("skill1", 2, 3);
Skill skill2 = new Skill("skill2", 3, 2);
Pokemon pokemon1 = new Pokemon("pokemon1", 10, 1, skill1, 1, 1, 3, 3);
Pokemon pokemon2 = new Pokemon("pokemon2", 10, 1, skill2, 1, 2, 3, 3);
player1.addPokemon(pokemon1);
player2.addPokemon(pokemon2);
</pre>
<pre>Player winner = Battle.tatakai(player1, player2);
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td colspan="2" rowspan="1"></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Since pokemon1.speed &lt; pokemon2.speed , pokemon2 attack first. Below shows what happens in each round:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>-- Round 1 --
pokemon1.hp = 10; pokemon2.hp = 10;
pokemon2 attack first, its attack value is normal attack damage: 1;
pokemon1.hp = 9;
Then, it's pokemon1's turn to attack, the attack value is normal attack
damage: 1;
pokemon2.hp = 9;
</pre>
<pre>-- Round 2 --
pokemon1.hp = 9; pokemon2.hp = 9;
pokemon2 attack first, its attack value is normal attack damage: 1;
pokemon1.hp = 8;
Then pokemon1's skill is ready, it's attack value is skill damage: 3;
pokemon2.hp = 6;
</pre>
<pre>-- Round 3 --
pokemon1.hp = 8; pokemon2.hp = 6;
pokemon2's skill is ready, its attack value is skill damage: 2;
pokemon1.hp = 6;
Then, it's pokemon1's turn to attack, the attack value is normal attack
damage: 1;
pokemon2.hp = 5;
</pre>
<pre>-- Round 4 --
pokemon1.hp = 6; pokemon2.hp = 5;
pokemon2 attack first, its attack value is normal attack damage: 1;
pokemon1.hp = 5;
Then pokemon1's skill is ready, it's attack value is skill damage: 3;
pokemon2.hp = 2;
</pre>
<pre>-- Round 5 --
pokemon1.hp = 5; pokemon2.hp = 2;
pokemon2 attack first, its attack value is normal attack damage: 1;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Player.java

</div>
</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
32 33

<pre>34
35
36
37
38
39
40
41
42
43
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>pokemon1.hp = 4;
Then, it's pokemon1's turn to attack, the attack value is normal attack
damage: 1;
pokemon2.hp = 1;
</pre>
<pre>-- Round 6 --
pokemon1.hp = 4; pokemon2.hp = 1;
pokemon2's skill is ready, its attack value is skill damage: 2;
pokemon1.hp = 2;
Then pokemon1's skill is ready, it's attack value is skill damage: 3;
pokemon2.hp = -2;
</pre>
<pre>Since pokemon2.hp &lt; 0, pokemon1 win. The winner is player1.
</pre>
</div>
</div>
</div>
</div>
</div>
