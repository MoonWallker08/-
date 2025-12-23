<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Whitesquare</title>
<style>
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  margin: 0;
  padding: 0;
  color: #333;
}

.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #fff;
  padding: 10px 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.logo {
  display: flex;
  align-items: center;
}

.logo-square {
  width: 20px;
  height: 20px;
  background-color: #00bfff;
  margin-right: 10px;
}

.logo-text {
  font-family: Arial, sans-serif;
  font-size: 18px;
  font-weight: bold;
  color: #333;
}

.search-box {
  display: flex;
  align-items: center;
}

.search-box input[type="text"] {
  padding: 5px 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.search-box button {
  background-color: #00bfff;
  border: none;
  color: #fff;
  padding: 6px 12px;
  margin-left: 5px;
  border-radius: 4px;
  cursor: pointer;
}

nav {
  background-color: #fff;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.nav {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

.nav li {
  margin: 0;
}

.nav a {
  display: block;
  padding: 12px 20px;
  text-decoration: none;
  color: #555;
  font-weight: normal;
}

.nav a.active,
.nav a:hover {
  background-color: #00bfff;
  color: #fff;
}

.main {
  padding: 20px;
  max-width: 1200px;
  margin: auto;
}

h2 {
  font-size: 24px;
  margin-top: 40px;
  margin-bottom: 10px;
  color: #333;
}

h2.about {
  border-bottom: 1px solid #ccc;
  padding-bottom: 10px;
  font-weight: normal;
}

.quote {
  background-color: #00bfff;
  color: #fff;
  font-style: italic;
  font-size: 20px;
  padding: 20px;
  margin-top: 20px;
  border-radius: 4px;
  font-family: Arial, sans-serif;
  line-height: 1.4;
}

.author {
  font-size: 14px;
  color: #eee;
  margin-top: 10px;
  text-align: right;
}

.content-text {
  margin-top: 20px;
  font-size: 14px;
  line-height: 1.6;
  color: #555;
}

.offices {
  margin-top: 40px;
  display: flex;
  flex-direction: column;
}

.office {
  background-color: #fff;
  padding: 10px;
  margin-bottom: 10px;
  border-left: 4px solid #00bfff;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

.team {
  margin-top: 40px;
}

.team-title {
  background-color: #00bfff;
  color: #fff;
  padding: 10px;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 10px;
  border-radius: 3px;
}

.team-members {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.member {
  width: calc(20% - 10px);
  background-color: #fff;
  padding: 10px;
  text-align: center;
  border-radius: 4px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
}

.member-name {
  font-weight: bold;
  margin-top: 10px;
  font-size: 14px;
}

.member-position {
  font-size: 12px;
  color: #777;
}

.footer {
  background-color: #ccc;
  padding: 20px;
  font-size: 14px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 40px;
}

.footer-column {
  flex: 1;
  min-width: 150px;
  margin-bottom: 10px;
}

.footer h4 {
  margin-top: 0;
  margin-bottom: 10px;
  font-weight: bold;
}

.social-icons {
  display: flex;
  gap: 10px;
  margin-top: 10px;
}

.social-icons a {
  display: inline-block;
  width: 24px;
  height: 24px;
  background-color: #fff;
  border-radius: 50%;
  text-align: center;
  line-height: 24px;
  color: #555;
  text-decoration: none;
  font-size: 14px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.2);
}
</style>
</head>
<body>

<header class="header">
  <div class="logo">
    <div class="logo-square"></div>
    <div class="logo-text">whitesquare</div>
  </div>
  <div class="search-box">
    <input type="text" placeholder="Search..."/>
    <button>Go</button>
  </div>
</header>

<nav>
  <ul class="nav">
    <li><a href="#" class="active">Home</a></li>
    <li><a href="#">About Us</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Partners</a></li>
    <li><a href="#">Customers</a></li>
    <li><a href="#">Projects</a></li>
    <li><a href="#">Careers</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>

<div class="main">

  <section>
    <h2 class="about">ABOUT US</h2>
    <div class="quote">“QUISQUE IN ENIM VELIT, AT DIGNISSIM EST. NULLA UL CORPER, DOLOR AC PELLENTESQUE PLACERAT, JUSTO TELLUS GRAVIDA ERAT, VEL PORTTITOR LIBERO ERAT.”</div>
    <div class="author">John Doe, Lorem Ipsum</div>
    <div class="content-text">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean non neque ac sem accumsan rhoncus ut ut turpis. In hac habitasse platea dictumst. Proin eget nisi erat, et feugiat arcu. Duis semper porttitor luctus, ac pharetra erat imperdiet nec. Morbi interdum felis nulla. Aenean eros orci, pellentesque sed egestas vitae, auctor aliquam nisl. Nulla nec libero eget sem rutrum iaculis. Quisque in enim velit, at dignissim est. Nulla ullamcorper, dolor ac pellentesque placerat, justo tellus gravida erat, vel porttitor libero erat, condimentum metus. Donec sodales aliquam orci id suscipit. Proin sed risus sit amet sapien ultrices laoreet quis a erat. Aliquam et metus id erat vulputate egestas. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
      <p>Donec vel nisl nibh. Aenean quam tortor, tempus sit amet mattis dapibus, egestas tempor dui. Duis vestibulum imperdiet risus pretium pretium. Nunc vitae porta ligula. Vestibulum sit amet nulla quam. Aenean lacinia, ante vitae sodales sagittis, leo felis bibendum neque, mattis sagittis neque urna vel magna. Sed at sem vitae lorem blandit feugiat.</p>
      <p>Donec vel orci purus, ut ornare orci. Aenean rutrum pellentesque quam. Quisque gravida adipiscing augue, eget commodo augue egestas varius. Integer vulputate, tellus porta tincidunt sodales, lacus est tempus odio, fringilla blandit tortor luctus ut sem. Pellentesque nec sem lacus, at semper nec quam. Etiam varius urna quis arcu cursus in consectetur dui tincidunt. Quisque arcu orci, laoreet eget pretium vel, luctus pellentesque nibh, tincidunt cursus lacus eget neque viverra vestibulum. Aenean erat volutpat. Duis pulvinar tellus ut urna facilisis. Maecenas ac pharetra dui. Pellentesque neque ante, luctus eget congue eget, rhoncus vel mauris. Duis nisi magna, aliquet a convallis non, venenatis at nisi. Nunc ac turpis augue, luctus eget congue eget, rhoncus vel mauris. Duis bibendum aliquam felis, eu venenatis risus sodales non. In ligula mi, faucibus eu tristique sed, vulputate rutrum dolor.</p>
    </div>
  </section>

  <section>
    <h2 class="about">OUR OFFICES</h2>
    <div class="offices">
      <div class="office">
        <h3>Office 1</h3>
        <p>Address: 123 Main Street, City</p>
        <p>Phone: +123456789</p>
        <p>Email: info@office1.com</p>
      </div>
      <div class="office">
        <h3>Office 2</h3>
        <p>Address: 456 Second Street, City</p>
        <p>Phone: +987654321</p>
        <p>Email: info@office2.com</p>
      </div>
    </div>
  </section>

  <section>
    <h2 class="about">OUR TEAM</h2>
    <div class="team">
      <div class="team-title">Our Team</div>
      <div class="team-members">
        <div class="member">
          <div class="member-name">John Doe</div>
          <div class="member-position">CEO</div>
        </div>
        <div class="member">
          <div class="member-name">Saundra Pittsley</div>
          <div class="member-position">Team Leader</div>
        </div>
        <div class="member">
          <div class="member-name">Julio Simser</div>
          <div class="member-position">Senior Developer</div>
        </div>
        <div class="member">
          <div class="member-name">Margery Venuti</div>
          <div class="member-position">Senior Developer</div>
        </div>
        <div class="member">
          <div class="member-name">Fernando Tondrea</div>
          <div class="member-position">Developer</div>
        </div>
        <div class="member">
          <div class="member-name">Ericka Nobriga</div>
          <div class="member-position">Art Director</div>
        </div>
        <div class="member">
          <div class="member-name">Cody Rousselle</div>
          <div class="member-position">Senior UI Designer</div>
        </div>
        <div class="member">
          <div class="member-name">Erik Wollman</div>
          <div class="member-position">Senior UI Designer</div>
        </div>
        <div class="member">
          <div class="member-name">Dona Shoff</div>
          <div class="member-position">UX Designer</div>
        </div>
        <div class="member">
          <div class="member-name">Darryl Brunton</div>
          <div class="member-position">UI Designer</div>
        </div>
      </div>
    </div>
  </section>
</div>

<footer class="footer">
  <div class="footer-column">
    <h4>TWITTER FEED</h4>
    <p>23 oct<br/>In ultrices pellentesque massa a porta. Aliquam ipsum enim, hendrerit ut porta nec, ullamcorper ut nisi. In eget mi dui, at amet scelerisque nunc. Aenean augue</p>
  </div>
  <div class="footer-column">
    <h4>SITEMAP</h4>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>
  <div class="footer-column">
    <h4>SOCIAL NETWORKS</h4>
    <div class="social-icons">
      <a href="#">F</a>
      <a href="#">T</a>
      <a href="#">G</a>
      <a href="#">L</a>
    </div>
  </div>
</footer>

</body>
</html>
