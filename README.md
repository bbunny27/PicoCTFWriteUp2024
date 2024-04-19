<h1>PicoCTF Write-up! <><> WORK IN PROGRESS <><></h1>
<p>My team the Cyberhawks competed in the PicoCTF 2024 competition! We finished 2169th place out of 6947 teams in the open category, as we had one member of our team who was not a college student. I will update this when I have time.</p>
<h4>Super SSH (General Skills)</h4>
<p>Super SSH is the first and lowest point challenge in Pico CTF as a whole. The goal is to connect with a server through SSH.</p>
<img src='https://github.com/bbunny27/PicoCTFWriteUp2024/blob/main/322240722-5bd17e06-ef17-4dc5-905d-86e78a5e7df8.png'>
<p> We will use the following command to connect to the server: ssh ctf-player@titan.picoctf.net -p 50368 </p>
<p>The password we will need is 1ad5be0d and with that we are in! Our flag is picoCTF{s3cur3_c0nn3ct10n_07a987ac} </p>

<h4>Bookmarklet</h4>
<p>Why search for the flag when I can make a bookmarklet to print it for me? Browse here, and find the flag!</p>
<p>This is seemingly a pretty straight forward question. Based on what I know, I believe the challenge wants us to run a bookmarklet (javascript in the browser) in order to get the flag.</p>
<p>Here is the website.</p>
<img src='https://github.com/bbunny27/PicoCTFWriteUp2024/blob/main/bookmarklet1.PNG'>
<p>As you can see, it's just some javascript code for us to save as a bookmark and run. When I do that, I get this pop up:</p>
<img src='https://github.com/bbunny27/PicoCTFWriteUp2024/blob/main/success.PNG'> 
<p>Success! The Flag is: picoCTF{p@f3_turn3r_0c0d211f}</p>
