# python-project
https://www.youtube.com/watch?v=PsO5dZqBckY

https://app.tana.inc?nodeid=F-VcQAKLTwnS

author's repo:
https://github.com/devopshint/python-project

I ran it with this command based on this 5 minute flask video ()
python  -m flask --app src/app.py run --port 5001

(using port 5001 because 5000 was already being used by Control Center on Mac Air)

But when I tried to access from both the browser and from curl, I got an error:

❯ curl http://127.0.0.1:5001
<!doctype html>
<html lang=en>
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>

Rewrote it following simple example here, and it worked, so wtf knows?
https://medium.com/@alains/building-a-simple-app-with-flask-in-python-full-source-code-8cdd1116ff43

