# projetvoltairesolver
a selenium bot to realize all exercices in projet voltaire

<h1>Python selenium solver for Projet voltaire exercises.</h1>

<p><b>Please note :</b> My account is now outdated, and unfortunately the project isn't free. Therefore I can't rewrite the scripts in a real proper way. Also, I am not responsible if someone uses this project to cheat on Projet Voltaire, I just wanted to realize an automation of the website and share it to the git community. </p>

If I could here are some points i'd like to add:
<ul>
    <li>Make a bypass for rechapcha2 (that is at connection screen).</li>
    <li>This would allow the next.</li>
    <li>Make headless app + command line prompt app (don't realize exercises with ipynb, but directly from the prompt. Actually it wouldn't be so long to do).</li>
    <li>Rewrite properly the code, and delete useless chunks (because I can't test it, I don't want to delete it).</li>
    <li>Maybe comment my code more... </li>
</ul>

   
<h2>How the code works.</h2>

<b>first of all you need:</b>
<ul>
    <li>To create two csv file (I nammed them respectively "fichier.csv" and "fichier2.csv").</li>
    <li>Dowload a chromedriver.exe in order to use Selenium.</li>
    <li>You can use the first chunck to install libs used in the project.</li>
</ul>



the first chunk is to create the object Voltaire, that has method to realize all level of PV. Even for different section. The code was made to make last exercises automatically.

the second chunk is here to connect you to the website. you can insert your logs (at the end of the first chunk). valid the captacha, connect and use chunk 3 to realize exercises.

<h2> A quick description of the program's logic </h2>
