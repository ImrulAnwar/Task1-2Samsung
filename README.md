<h2><strong>Step By Step Guide to create a watch face on the Watch Face Studio</strong></h2>
<p>We will be building a Watch Face with a battery indicator which turns red if the battery percentage is less than or equal to 20. 
    Final Output is in the <a href = "https://github.com/ImrulAnwar/Task1-2Samsung/releases">release</a> section:</p>
<ul>
  <li>Step 1: Go to Watch Face Studio and create a new project then give it a name.</li>
   <li>
    <img src="https://github.com/user-attachments/assets/39bc26b9-4370-478a-a200-6971c69367f8" alt="new project" style="width: 200px;">
  </li>
</ul>
<ul>
  <li>Step 2: Go to the Add Component on top. Add an Analog Clock. Then You may add an index as well from there as well.</li>
   <li>
    <img src="https://github.com/user-attachments/assets/88657e7c-10a4-41dd-9dc9-2cb475a61acc" alt="new project" style="width: 200px;">
  </li>
</ul>  
<ul>
  <li>Step 3: Now add a circle. Place the circle on your desired spot. Select the circle with a progress bar.</li>
   <li>
       <img src="https://github.com/user-attachments/assets/25ac203f-a4f7-480c-b483-4b5525929c19" alt="new project" style="width: 200px;">
  </li>
</ul>  
<ul>
  <li>Step 4: From the properties tab select Default Provider as Watch Battery.</li>
   <li>
      <img src="https://github.com/user-attachments/assets/e5f61622-cf1f-45cf-9778-c08116029e64" alt="new project" style="width: 200px;">
  </li>
</ul>  
<ul>
  <li>Step 5: On the layer tab, rename the Circle Complication Slot as Battery Level.</li>
   <li>
      <img src="https://github.com/user-attachments/assets/a54f46dd-666e-4ca4-9299-1c109847db85" alt="new project" style="width: 200px;">    
  </li>
</ul>
<ul>
  <li>Step 6: Duplicate Battery Level and rename it as Battery Level Low. And move it below the Group Battery Level.</li>
   <li>
      <img src="https://github.com/user-attachments/assets/ec889f69-da60-4548-8f67-20585d48173d" alt="new project" style="width: 200px;">    
  </li>
</ul>  
<ul>
  <li>Step 7: Select the Progress Bar in Battery Level. In the Properties tab, go to color section and select the color as red.</li>
   <li>
      <img src="https://github.com/user-attachments/assets/d6dc2d3b-9915-46ea-87c3-edea6ad899f2" alt="new project" style="width: 200px;">    
  </li>
</ul> 
<ul>
  <li>Step 8: In tags Use this Tag Expression and click done. Set the Background Opacity to 0.
        <pre>
            <code>
            [BATT_PER]>20?-100:0
            </code>
        </pre>
    </li>
</ul>
<ul>
  <li>Step 9: Change watch Battery in the Run Tab to see if it is working.</li>
   <li>
      <img src="https://github.com/user-attachments/assets/29faa381-9cf7-464a-b3e6-0b8e3b51882c" alt="new project" style="height: 300px;">    
     <img src="https://github.com/user-attachments/assets/1cbafb2d-7e07-4b9d-909a-aa564a3f534b" alt="new project" style="height: 300px;">    
  </li>
</ul> 
<ul>
  <li>Step 10: Go to file and click Save As to export the project.</li>
   <li>
     <img src="https://github.com/user-attachments/assets/83110a13-8930-449b-987c-06a5c4a44aaf" alt="new project" style="height: 300px;">    
  </li>
</ul> 
