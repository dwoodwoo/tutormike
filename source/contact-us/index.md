title: contact-us
date: 2015-11-28 20:09:33
---


<div>
<form action="http://formspree.io/dwoo@sent.com" method="POST">
	<div class="site-form">foo</div>
		<input type="text" name="name" placeholder="name..."><br>
		<input type="email" name="_replyto" placeholder="email"><br>

		<input type="checkbox" name="food" value="food" checked>I ate food</input>
		<textarea name="message" rows="4" cols="50" placeholder="text..."></textarea><br>
		<input type="hidden" name="_next" value="http://0.0.0.0:3333/thanks.html" />
		<input type="submit" value="Send">
</form>
</div>

<div>
<form action="http://formspree.io/dwoo@sent.com" method="POST">
<span style="color:red">should be red</span>
	<input type="checkbox" name="food" value="food" checked>I ate food<br>
<select name="car">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
  <input type="radio" name="sex" value="male" checked>Male
  <br>
  <input type="radio" name="sex" value="female">Female
	<input type="submit" value="Send">
</form>
</div>
