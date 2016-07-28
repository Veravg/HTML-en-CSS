# HTML-en-CSS
TEST
<!DOCTYPE html.
<html.
	<head.
		<title, hallo </title,
	<body.
	<p.

<!-- alleen zichtbaar voor maker-->

<h1> heading </h1>

<div class="container"> 

<div class="photo">
    <img src="https://media.licdn.com/mpr/mpr/shrinknp_200_200/AAEAAQAAAAAAAAPFAAAAJDY2MjU4MWMzLTY1MzUtNDYyNi04MzM1LWI1NDgzYTNmMGQ0ZA.jpg">
  </div>
  <div class="text">
    <h4><b> Paragraph</b></h4>
    <h4><b> &copy; 2016 Vera van Gelder</b></h4>
  </div>
</div>

<ol>
 <li> tellen kan met ol!</li>
    <ul>
       <li>bolletjes met ul!</li>
       <li>beide aanvullen met li </li>
    </ul>
 <li> handigg</li>
    <ul>
    <li>main.CSS</li>
    <li style="text-align:center">index.HTML</li>
    </ul>
</ol>

<div class="container2">
  <p> Here is <a href=”https://wwww.google.com/maps”>Google maps</a>!</p>
  
<p style="background-color: yellow; font-family: Cambria; color:blue; font-size: 15px"> font size color background in HTML</p>
 <em>em</em>  <strong> strong</strong>

  <video width="320" height="240" controls>
    <source src="https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-1/ollie.mp4" type="video/mp4"> </video>

</div>

<div class="second">
  <p> <b>border= black line, padding= between and margin=outside</b> </p>
</div>

<table border="1px">
    <thead>
               <tr> 
               <th>tussen tr</th>
               <th>daarna th dikgedrukt</th>
               </tr> 
            </thead>
  <tr>
        <td>tussen tr</td>
        <td>td=naast elkaar</td>     
     </tr>
            
      <tr>
         <td>tr= onder elkaar</td>
      </tr>
 </table>

<p id="footer">Doei</p>




CSS
h1 {
  color: DarkOliveGreen;
  font-size: 50px;
}

body {
  background-image: url('https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-3/background.jpg');
  font-family: arial, serif;
  font-size: 18px;
  color: black;
  height: 100%;
  margin: 0;
  text-align: center;
}

h4 {
  text-align: left;
}

p {
  font-size: 18px text-shadow: 0 3px #000000;
}

.container {
  background-image: url("https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-3/moss1.jpg");
  display: flex;
  justify-content: center;
  border: 5px solid #000;
  padding: 20px 0;
  margin: 30px;
}

.text {
  border: 5px solid; 
  padding: 10px 0;
  margin: 30px;
  background-color: DarkOliveGreen;
  display: inline;
  color: black;
  text-align: left;
}

.photo {
  border: 5px solid;
  color: DarkOliveGreen;
}

.container2 {
  display: inline
}

.second {
  background-image: url("https://s3.amazonaws.com/codecademy-content/projects/make-a-website/lesson-3/moss6.jpg");
  background-position: center top;
  border: 5px dashed #000;
  padding: 20px 0;
  margin: 30px;
  text-shadow: 0 2px #000000;
  font-family: 'Trebuchet MS', 'Helvetica', sans-serif;
  color: #fff;
}

li {
  text-align: left;
}
