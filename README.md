<html>
<head>
HTML Tutorial
</head>
<body>
  <h1> Hello World! </h1>
  
  <p> This is the first HTML code </p>
  
  <h2> Heading 2 </h2>
  
  <h6> Heading 6 </h6>
  
  <p> This is paragraph </p>
  
  <span> This is span.</span>
  
  <span> The 'br' tag is used after span to break the line </span>
  
  <br/>
  
  <div style="color:blue;">
    The 'div' tag can be used for formatting the tags inside it at once using 'style' and 'classes'␣˓→etc.
    <p> This paragraph is inside the 'div' tag </p>
    <span> This span is inside the 'div' tag </span>
    <br/>
  </div>
  
  <h3 align="center"> Heading 3 is centered</h3>
  <p align="center"><span> Centered span inside the paragraph.</span><p>
    
  Two horizontal line is drawn using two 'hr' tag.
  <hr />
  <hr>
  
  <pre> 'pre' tag preserve the formatting (good for writing codes)
    # Python code
    x = 2
    y = 3
    print(x+y)
  </pre>
  
  <p id='para1'> This is paragraph with id 'para1' </p>
  
  <p id='para2'> This is paragraph with id 'para2' </p>
  
  <p class="c_blue"> This is paragraph with class 'blue'</p>
  
  <span class="c_blue"> This is span with class 'blue'</span>
  
  <p style="font-weight:bold; color:red;">Style attribute is used to bold and color</p>
  
  <p class="my_class" id="para_with_class" style="color:green"> Multiple attributes </p>
  
  <!-- border - color, width and height -->
  <table border="1" bordercolor="black" width="450" height="100">
  <caption>Table 1 : Various tags of table</caption>
    <tr bgcolor="red" > <!-- row -->
      <th>Column 1</th> <!-- header -->
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
    <tr bgcolor="cyan"> <!-- background color -->
      <td>Data 1</td> <!-- data -->
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
    <tr bgcolor="yellow"> <!-- row -->
      <td colspan="2">New Data 1</td> <!-- column span -->
      <td>New Data 2</td> <!-- data -->
    </tr>
  </table>
  
  <!-- width in % -->
  <table border="1" bordercolor="black" width="80%" height="100">
  <caption> Table 2 : Width is 80%</caption>
    <tr bgcolor="red" >
      <th>Column 1</th>
      <th>Column 2</th>
      <th>Column 3</th>
    </tr>
    <tr bgcolor="cyan"> <!-- row -->
      <td>Data 1</td> <!-- data -->
      <td>Data 2</td>
      <td>Data 3</td>
    </tr>
  </table>
  
  <!-- Text formatting -->
  <p>This is <b>bold</b> text</p>
  
  <p>This is <strike>striked</strike> text</p>
  
  <p>This is <sub>subscript</sub> text</p>
  
  <!-- Images -->
  <img src="img/logo.jpg" alt="Logo.jpg" width="20%"/>
  <br/> <br/>
  <img src="img/logoa.jpg" alt="Missing Logo.jpg" width="20%"/>
  
  <!-- Lists -->
  <!-- unordered list -->
  <ul> Unordered List
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
  </ul>
  <ul type="circle"> Change bullets : 'square', 'circle' or 'disc'
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
  </ul>
  
  <!-- ordered list -->
  <ol> Ordered List
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
  </ol>
  
  <ol type='i'> Change style : 'i', 'I', '1', 'a' or 'A'
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
  </ol>
  
  <ol type='i' start="5"> Start from 'v'
    <li>Pen</li>
    <li>Pencil</li>
    <li>Eraser</li>
  </ol>
  
  <!-- Definition list -->
  <dl>
    <dt> <h4>HTML Definition List</h4> </dt>
      <dd> HTML is easy </dd>
      <dd> HTML is good </dd>
  </dl>
  
  <!-- links -->
  
  <p>Go to paragraph with<a href="#para1"> id='para1'</a></p>
  
  <a href="http://pythondsp.readthedocs.io"> PythonDSP </a>
  
  <br>
  
  <p><a href="js.html" target="_self"> JavaScript Tutorial</a> in same window.</p>
  
  <p><a href="js.html" target="_blank"> JavaScript Tutorial</a> in new Window.</p>
  
  <p><a href="http://pythondsp.readthedocs.io/pdf">Download PDF, DOC or Zip Files</a></p>
  
  <p><a href="mailto:pythondsp@gmail.com">Email me</a></p>
  
  <p><a href="mailto:pythondsp@gmail.com?subject=Feedback&body=Your feedback here">Feeback email</a></p>
 
 <form>
  <h4>Text input </h4>
  
  Name : <input type="text" name="user_name" size="4" value="e.g. meher21" maxlength="10"><br>
  
  Password : <input type="password" name="user_pass" ><br>
  
  <h4> Radio button: name should be same</h4>
    <input type="radio" name="r_gender"> Male
    <input type="radio" name="r_gender"> Female
    <input type="radio" name="r_gender" checked> Infant
  
  <h4> Check box : name should be different</h4>
    <input type="checkbox" name="c_male" checked> Male
    <input type="checkbox" name="c_female"> Female
    <input type="checkbox" name="c_infant"> Infant
  
  <h4> Select box : drop-down</h4>
  <select name="s_box">
    <option value="s_male">Male</option>
    <option value="s_female" selected>Female</option>
    <option value="s_infant">Infant</option>
  </select>
  
  <h4> Select box : scroll</h4>
  <select name="s_box" size="4" multiple>
    <option value="s_male" selected>Male</option>
    <option value="s_female" selected>Female</option>
    <option value="s_infant">Infant 1</option>
    <option value="s_infant" selected>Infant 2</option>
    <option value="s_infant">Infant 3</option>
    <option value="s_infant">Infant 4</option>
  </select>
  
  <h4> Text area</h4>
  <textarea rows="10" cols="80" name="txt_area">Initial Text
    x = 2
    y = 3
  </textarea> <!-- formatting work as pre -->
 </form>
 
 <form method="get|post" action="jquery.html">
  <h4> Buttons and Hidden</h4>
  
  Name : <input type="text" name="user_name" size="4" value="Meher" maxlength="16"><br>
  
  Password : <input type="password" name="user_pass" ><br>
  
  <input type="button" onclick="alert('Hello')" name="b_alert" value="Say Hello"/><br>
  
  <input type="submit" name="b_submit" value="Go to jQuery"/>
  
  <input type="reset" name="b_reset" value="Reset"/><br>
  
  <input type="hidden" name="h_data" value="html_tutorial">
 </form>

</body>
</html>
