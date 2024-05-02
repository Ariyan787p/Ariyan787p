<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name - Personal Website</title>
<style>
  body { font-family: Arial, sans-serif; line-height: 1.6; }
  .container { width: 80%; margin: auto; overflow: hidden; }
  header { background: #50b3a2; color: white; padding-top: 30px; min-height: 70px; border-bottom: #e8491d 3px solid; }
  header a { color: #ffffff; text-decoration: none; text-transform: uppercase; font-size: 16px; }
  header ul { padding: 0; list-style: none; }
  header li { display: inline; padding: 0 20px 0 20px; }
  header #branding { float: left; }
  header #branding h1 { margin: 0; }
  header nav { float: right; margin-top: 10px; }
  header .highlight, header .current a { color: #e8491d; font-weight: bold; }
  header a:hover { color: #ffffff; font-weight: bold; }
  #showcase { min-height: 400px; background: url('banner.jpg') no-repeat 0 -400px; text-align: center; color: white; }
  #showcase h1 { margin-top: 100px; font-size: 55px; margin-bottom: 10px; }
  #showcase p { font-size: 20px; }
  #main { padding: 30px; }
  #main .content { float: left; width: 70%; }
  #sidebar { float: right; width: 30%; padding: 30px; background: #e8491d; }
  #sidebar h3 { color: white; }
  #sidebar ul { padding: 0; list-style: none; }
  #sidebar ul li { text-align: center; line-height: 2.5; }
  footer { background: #50b3a2; color: white; text-align: center; padding: 30px 0; }
</style>
</head>
<body>
  <header>
    <div class="container">
      <div id="branding">
        <h1><span class="highlight">Your</span> Name</h1>
      </div>
      <nav>
        <ul>
          <li class="current"><a href="#bio">Biography</a></li>
          <li><a href="#resume">Resume</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="showcase">
    <div class="container">
      <h1>Your Professional Tagline Here</h1>
      <p>Describe yourself and your professional goals briefly.</p>
    </div>
  </section>

  <section id="main">
    <div class="container">
      <article id="bio" class="content">
        <h2>Biography</h2>
        <p>Your biography goes here. Talk about yourself, your interests, and your achievements.</p>
      </article>

      <aside id="sidebar">
        <div class="dark">
          <h3>Resume</h3>
          <ul>
            <li><a href="resume.pdf" target="_blank">Download Resume (PDF)</a></li>
          </ul>
        </div>
      </aside>
    </div>
  </section>

  <footer>
    <p>Your Name © 2024</p>
  </footer>

  <script>
    // JavaScript for toggling menu on small screens
    document.getElementById('menu-toggle').addEventListener('click', function(e){
      document.getElementById('menu').classList.toggle('show');
    });
  </script>
</body>
</html>
