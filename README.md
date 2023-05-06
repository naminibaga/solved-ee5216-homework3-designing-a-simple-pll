Download Link: https://assignmentchef.com/product/solved-ee5216-homework3-designing-a-simple-pll
<br>
<ul>

 <li><strong>Objective: To design a simple cell-based Phased-Locked Loop (PLL) and perform frequency acquisition. </strong></li>

 <li><strong>Step-by-Step Procedure </strong></li>

</ul>

Design a low-resolution Phase-Locked Loop to produce a 500MHz clock signal, denoted as <em>clk_out</em>, from a 10MHz reference clock signal, <em>clk_ref. </em>

<ul>

 <li>Design a <strong>path-selection-based Digital Controlled Oscillator (DCO)</strong> as indicated below. Report the oscillation frequency of your DCO under various control code values. Note that you may need to use a longer buffer chain and a control code with more bits than what is shown in the figure to ensure that the oscillation frequency fits your needs. (30%)</li>

</ul>




<ul>

 <li>Design a <strong>frequency divider </strong>and a <strong>controller</strong> that works with your <strong>DCO</strong> and some Phase Detector (<strong>PD</strong>) you have developed in homework #1 so that your PLL will produce a frequency closest to the designated clock frequency after<strong> frequency acquisition</strong>. Verify your DLL design by Verilog simulation using as accurate delay model as possible for your DCO, frequency divider, and controller. Use the behavior model you have constructed in homework #1 for your PD. <strong>Show the average clock cycle times of <em>clk_out</em> observed over 10 clock cycles after the frequency acquisition and its error as compared to the ideal clock cycle time (which is 2000ps).</strong> (40%)</li>

 <li>Try to use SOC Encounter to <strong>generate the layout</strong> of your design. What is the size of your layout? (15%)</li>

 <li>Try to do <strong>post-layout Verilog simulation</strong> for your PLL. Your TDL, frequency divider, and controller should be back-annotated with the post-layout SDF information, while using the behavior model for your PD. Compare your results with those derived in the pre-layout simulation. (15%)</li>

</ul>

<ul>

 <li><strong>Deliverables: Submit the following documents (combined into a PDF file) to our iLMS system. </strong></li>

 <li>A cover page containing 所有組員之系所，中英文姓名，學號等資訊</li>

 <li>Your results to questions (a)-(d).</li>

 <li>各個組員的負責項目，或是貢獻方式的一段簡述。</li>

</ul>

1


