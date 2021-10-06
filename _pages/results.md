---
permalink: /results/
title: Results
subtitle: 
---

### Comparison of our model with baselines

| Model ||| Social Goal |||| Physical Goal ||
|-------|:-----------:|:--------:|:-----------:|:----------:|:----------:|:---------:|:---------------:|
|       | Cooperation | Conflict | Competition | Coercion | Exchange| Overall | |
| *Human*  | *0.934* | *0.952* | *0.623* | *0.724* | *0.876* | *0.823* | *0.974* |
| Extended Social MDP (Ours)  | **0.845** | **0.851** | **0.471** | **0.651** | **0.814** | **0.726** | **0.831** |
| Inverse Planning | 0.763 | 0.784 | 0.261 | 0.283 | 0.197 | 0.457 | 0.783 |
| Cue Based Model | 0.461 | 0.434 | 0.127 | 0.156 | 0.083 | 0.252 | 0.432 | 

<p><span style="font-size:medium;">The accuracy of humans and each of the models at determining which social interaction is taking place in each of the 72 scenarios. Our model is significantly more accurate, particularly when it comes to recognizing social interactions.</span></p>

---

### Comparison of Physical and Social Goals between Human estimates and our model

<img src="/images/index/goal-weights.png" width="900">
<p><span style="font-size:medium;">Humans and our model scored 72 scenarios according to how likely each social goal was and how likely one of the physical goals was. The straight line is the best linear fit and the light blue band represents the 95% confidence interval. Our model agrees with humans and predicts their confidence scores for both social goal and the physical goal.</span></p>

---

### Results for experimental scenarios
For each of the experiment scenario we show the yellow robot's estimation of the physical and social goal of the red robot using Social MDP at different levels and at each time step. 
<!--For physical goal estimations the lines <span style="color: red"> in red represents the physical goal tree</span> and <span style="color: blue"> in blue represents the physical goal construction site</span>. For Social Goal estimations the lines <span style="color: blue"> in red represents cooperation</span>, <span style="color: olive"> in olive represents conflict</span>, <span style="color: green">in green represents competition</span>, and <span style="color: orange">in orange represents exchange</span>.-->

<table style="text-align:center">
<thead><tr><th style="text-align:center">Result for Scenario #</th>
<th colspan="2" style="text-align:center">Yellow Robot</th>
<th colspan="2" style="text-align:center">Red Robot</th>
</tr></thead>
<tbody><tr>
<td> </td>
    <td><b>Physical Goal</b></td>
    <td><b>Social Goal</b></td>
    <td><b>Social Goal</b></td>
    <td><b>Physical Goal</b></td>
</tr>
<tr>
<td><A href="#result-for-scenario-1">Result for Scenario 1</A></td>
<td>Tree</td>
<td>None</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-2">Result for Scenario 2</A></td>
<td>Construction Site</td>
<td>None</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-3">Result for Scenario 3</A></td>
<td>Tree</td>
<td>None</td>
<td>Competiton</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-4">Result for Scenario 4</A></td>
<td>Tree</td>
<td>None</td>
<td>Coercion</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-5">Result for Scenario 5</A></td>
<td>Construction Site</td>
<td>None</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-6">Result for Scenario 6</A></td>
<td>Tree</td>
<td>None</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-7">Result for Scenario 7</A></td>
<td>Tree</td>
<td>Cooperate</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-8">Result for Scenario 8</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-9">Result for Scenario 9</A></td>
<td>Tree</td>
<td>Cooperate</td>
<td>Competiton</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-10">Result for Scenario 10</A></td>
<td>Tree</td>
<td>Cooperate</td>
<td>Coercion</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-11">Result for Scenario 11</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-12">Result for Scenario 12</A></td>
<td>Tree</td>
<td>Cooperate</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-13">Result for Scenario 13</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>Cooperate</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-14">Result for Scenario 14</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-15">Result for Scenario 15</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>Competiton</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-16">Result for Scenario 16</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-17">Result for Scenario 17</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-18">Result for Scenario 18</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>None</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-19">Result for Scenario 19</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-20">Result for Scenario 20</A></td>
<td>Construction Site</td>
<td>Competiton</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-21">Result for Scenario 21</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>Competiton</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-22">Result for Scenario 22</A></td>
<td>Construction Site</td>
<td>Competiton</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-23">Result for Scenario 23</A></td>
<td>Construction Site</td>
<td>Competiton</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-24">Result for Scenario 24</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-25">Result for Scenario 25</A></td>
<td>Construction Site</td>
<td>Coercion</td>
<td>Cooperate</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-26">Result for Scenario 26</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Conflict</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-27">Result for Scenario 27</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Competiton</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-28">Result for Scenario 28</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Coercion</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-29">Result for Scenario 29</A></td>
<td>Construction Site</td>
<td>Coercion</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-30">Result for Scenario 30</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-31">Result for Scenario 31</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Cooperate</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-32">Result for Scenario 32</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-33">Result for Scenario 33</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-34">Result for Scenario 34</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-35">Result for Scenario 35</A></td>
<td>Tree</td>
<td>Exchange</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-36">Result for Scenario 36</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>None</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-37">Result for Scenario 37</A></td>
<td>Construction Site</td>
<td>None</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-38">Result for Scenario 38</A></td>
<td>Tree</td>
<td>None</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-39">Result for Scenario 39</A></td>
<td>Tree</td>
<td>None</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-40">Result for Scenario 40</A></td>
<td>Tree</td>
<td>None</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-41">Result for Scenario 41</A></td>
<td>Construction Site</td>
<td>None</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-42">Result for Scenario 42</A></td>
<td>Construction Site</td>
<td>None</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-43">Result for Scenario 43</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-44">Result for Scenario 44</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Conflict</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-45">Result for Scenario 45</A></td>
<td>Tree</td>
<td>Cooperate</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-46">Result for Scenario 46</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Coercion</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-47">Result for Scenario 47</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-48">Result for Scenario 48</A></td>
<td>Construction Site</td>
<td>Cooperate</td>
<td>None</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-49">Result for Scenario 49</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-50">Result for Scenario 50</A></td>
<td>Construction Site</td>
<td>Conflict</td>
<td>Conflict</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-51">Result for Scenario 51</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-52">Result for Scenario 52</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-53">Result for Scenario 53</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-54">Result for Scenario 54</A></td>
<td>Tree</td>
<td>Conflict</td>
<td>None</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-55">Result for Scenario 55</A></td>
<td>Construction Site</td>
<td>Competiton</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-56">Result for Scenario 56</A></td>
<td>Construction Site</td>
<td>Competiton</td>
<td>Conflict</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-57">Result for Scenario 57</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-58">Result for Scenario 58</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-59">Result for Scenario 59</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>Exchange</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-60">Result for Scenario 60</A></td>
<td>Tree</td>
<td>Competiton</td>
<td>None</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-61">Result for Scenario 61</A></td>
<td>Construction Site</td>
<td>Coercion</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-62">Result for Scenario 62</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-63">Result for Scenario 63</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-64">Result for Scenario 64</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-65">Result for Scenario 65</A></td>
<td>Construction Site</td>
<td>Coercion</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-66">Result for Scenario 66</A></td>
<td>Tree</td>
<td>Coercion</td>
<td>None</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-67">Result for Scenario 67</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Cooperate</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-68">Result for Scenario 68</A></td>
<td>Tree</td>
<td>Exchange</td>
<td>Conflict</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-69">Result for Scenario 69</A></td>
<td>Tree</td>
<td>Exchange</td>
<td>Competiton</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-70">Result for Scenario 70</A></td>
<td>Tree</td>
<td>Exchange</td>
<td>Coercion</td>
<td>Tree</td>
</tr>
<tr>
<td><A href="#result-for-scenario-71">Result for Scenario 71</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>Exchange</td>
<td>Construction Site</td>
</tr>
<tr>
<td><A href="#result-for-scenario-72">Result for Scenario 72</A></td>
<td>Construction Site</td>
<td>Exchange</td>
<td>None</td>
<td>Construction Site</td>
</tr>
</tbody></table>

###### Result for Scenario 1 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social: **Cooperate** Physical: *Construction Site*<br/><font color="orange">Yellow robot's goals&nbsp;</font> Social: **None** Physical: *Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp1.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs1.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p1.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s1.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip1.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips1.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp1.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs1.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 2 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp2.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs2.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p2.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s2.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip2.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips2.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp2.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs2.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 3 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp3.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs3.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p3.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s3.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip3.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips3.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp3.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs3.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 4 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp4.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs4.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p4.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s4.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip4.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips4.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp4.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs4.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 5 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp5.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs5.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p5.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s5.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip5.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips5.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp5.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs5.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 6 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp6.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs6.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p6.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s6.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip6.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips6.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp6.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs6.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 7 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp7.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs7.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p7.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s7.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip7.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips7.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp7.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs7.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 8 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp8.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs8.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p8.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s8.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip8.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips8.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp8.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs8.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 9 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp9.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs9.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p9.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s9.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip9.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips9.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp9.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs9.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 10 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp10.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs10.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p10.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s10.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip10.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips10.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp10.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs10.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 11 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp11.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs11.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p11.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s11.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip11.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips11.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp11.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs11.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 12 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp12.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs12.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p12.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s12.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip12.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips12.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp12.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs12.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 13 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp13.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs13.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p13.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s13.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip13.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips13.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp13.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs13.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 14 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp14.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs14.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p14.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s14.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip14.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips14.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp14.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs14.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 15 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp15.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs15.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p15.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s15.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip15.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips15.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp15.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs15.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 16 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp16.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs16.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p16.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s16.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip16.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips16.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp16.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs16.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 17 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp17.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs17.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p17.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s17.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip17.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips17.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp17.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs17.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 18 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp18.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs18.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p18.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s18.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip18.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips18.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp18.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs18.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 19 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp19.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs19.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p19.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s19.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip19.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips19.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp19.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs19.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 20 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp20.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs20.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p20.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s20.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip20.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips20.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp20.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs20.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 21 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp21.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs21.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p21.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s21.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip21.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips21.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp21.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs21.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 22 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp22.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs22.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p22.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s22.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip22.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips22.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp22.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs22.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 23 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp23.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs23.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p23.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s23.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip23.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips23.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp23.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs23.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 24 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp24.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs24.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p24.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s24.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip24.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips24.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp24.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs24.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 25 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp25.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs25.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p25.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s25.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip25.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips25.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp25.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs25.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 26 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp26.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs26.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p26.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s26.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip26.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips26.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp26.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs26.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 27 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp27.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs27.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p27.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s27.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip27.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips27.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp27.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs27.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 28 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp28.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs28.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p28.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s28.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip28.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips28.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp28.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs28.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 29 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp29.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs29.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p29.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s29.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip29.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips29.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp29.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs29.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 30 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp30.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs30.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p30.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s30.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip30.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips30.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp30.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs30.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 31 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp31.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs31.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p31.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s31.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip31.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips31.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp31.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs31.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 32 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp32.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs32.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p32.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s32.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip32.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips32.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp32.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs32.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 33 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp33.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs33.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p33.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s33.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip33.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips33.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp33.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs33.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 34 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp34.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs34.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p34.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s34.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip34.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips34.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp34.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs34.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 35 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp35.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs35.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p35.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s35.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip35.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips35.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp35.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs35.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 36 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp36.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs36.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p36.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s36.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip36.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips36.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp36.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs36.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 37 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp37.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs37.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p37.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s37.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip37.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips37.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp37.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs37.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 38 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp38.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs38.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p38.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s38.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip38.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips38.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp38.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs38.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 39 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp39.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs39.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p39.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s39.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip39.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips39.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp39.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs39.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 40 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp40.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs40.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p40.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s40.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip40.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips40.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp40.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs40.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 41 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site*</span>

<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp41.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs41.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p41.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s41.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip41.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips41.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp41.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs41.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 42 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**None** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp42.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs42.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p42.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s42.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip42.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips42.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp42.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs42.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 43 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp43.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs43.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p43.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s43.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip43.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips43.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp43.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs43.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 44 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp44.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs44.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p44.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s44.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip44.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips44.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp44.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs44.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 45 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp45.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs45.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p45.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s45.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip45.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips45.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp45.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs45.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 46 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp46.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs46.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p46.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s46.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip46.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips46.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp46.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs46.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 47 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp47.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs47.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p47.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s47.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip47.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips47.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp47.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs47.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 48 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Cooperate** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp48.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs48.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p48.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s48.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip48.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips48.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp48.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs48.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 49 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp49.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs49.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p49.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s49.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip49.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips49.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp49.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs49.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 50 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp50.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs50.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p50.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s50.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip50.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips50.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp50.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs50.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 51 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp51.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs51.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p51.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s51.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip51.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips51.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp51.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs51.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 52 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp52.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs52.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p52.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s52.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip52.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips52.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp52.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs52.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 53 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp53.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs53.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p53.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s53.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip53.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips53.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp53.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs53.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 54 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Conflict** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp54.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs54.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p54.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s54.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip54.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips54.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp54.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs54.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 55 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp55.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs55.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p55.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s55.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip55.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips55.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp55.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs55.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 56 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp56.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs56.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p56.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s56.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip56.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips56.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp56.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs56.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 57 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp57.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs57.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p57.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s57.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip57.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips57.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp57.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs57.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 58 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp58.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs58.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p58.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s58.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip58.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips58.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp58.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs58.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 59 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp59.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs59.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p59.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s59.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip59.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips59.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp59.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs59.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 60 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Competition** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp60.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs60.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p60.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s60.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip60.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips60.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp60.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs60.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 61 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp61.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs61.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p61.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s61.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip61.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips61.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp61.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs61.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 62 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp62.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs62.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p62.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s62.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip62.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips62.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp62.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs62.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 63 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp63.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs63.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p63.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s63.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip63.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips63.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp63.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs63.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 64 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp64.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs64.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p64.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s64.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip64.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips64.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp64.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs64.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 65 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp65.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs65.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p65.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s65.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip65.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips65.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp65.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs65.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 66 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Coercion** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp66.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs66.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p66.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s66.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip66.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips66.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp66.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs66.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 67 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Cooperate** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp67.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs67.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p67.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s67.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip67.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips67.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp67.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs67.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 68 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Conflict** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp68.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs68.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p68.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s68.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip68.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips68.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp68.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs68.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 69 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Competition** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp69.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs69.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p69.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s69.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip69.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips69.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp69.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs69.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 70 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Coercion** Physical:*Tree* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Tree*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp70.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs70.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p70.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s70.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip70.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips70.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp70.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs70.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 71 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**Exchange** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp71.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs71.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p71.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s71.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip71.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips71.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp71.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs71.png"> 
        </td>
    </tr>
</table>

---

###### Result for Scenario 72 ######
<span style="font-size:medium;"><font color="red">Red robot's goals&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</font> Social:**None** Physical:*Construction Site* <br/><font color="orange">Yellow robot's goals&nbsp;</font> Social:**Exchange** Physical:*Construction Site*</span>
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;">Model</td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Physical goal estimation<br>(Level 1)
        </td>
        <td style="width:40%; text-align:center; font-weight: bold; font-size: large;">
            Social goal estimation<br>(Level 2)
        </td>
    </tr>
    
    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-hp72.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-hs1.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Extended Social MDP</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-p72.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-s72.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Inverse Planning</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-ip72.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-ips72.png"> 
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Cue Based Model</td>
        <td>
            <img src="/images/results/physical_goals/s-mdp-cp72.png"> 
        </td>
        <td>
            <img src="/images/results/social_goals/smdp-cs72.png"> 
        </td>
    </tr>
</table>

---