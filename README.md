<h1>Linux Server Configuration</h1>
Configure a Linux Server and upload the Items Catalog project
<br>
IP address: 52.39.64.250
Port = 2200
URL: http://52.39.64.250/

login using: ssh grader@52.39.64.250 -p 2200 -i ~/.ssh/linuxCourse

<h2>Software used:</h2>
<ul>
    <li>Finger</li>
    <li>Apache2</li>
    <li>Wsgi</li>
    <li>Flask</li>
    <li>Python-Pip</li>
    <li>Virtualenv</li>
    <li>PostgreSql</li>
    <li>Python</li>
    <li>Amazon lightsail</li>
    <li>Ubuntu</li>
</ul>

<h2>Firewall settings</h2>
	22                         ALLOW       Anywhere<br>
    2200/tcp                   ALLOW       Anywhere<br>
    2222/tcp                   ALLOW       Anywhere<br>
    80/tcp                     ALLOW       Anywhere<br>
    123                        ALLOW       Anywhere<br>
    22 (v6)                    ALLOW       Anywhere (v6)<br>
    2200/tcp (v6)              ALLOW       Anywhere (v6)<br>
    2222/tcp (v6)              ALLOW       Anywhere (v6)<br>
    80/tcp (v6)                ALLOW       Anywhere (v6)<br>
    123 (v6)                   ALLOW       Anywhere (v6)<br>
    
<h2>Sources Used</h2>
    https://medium.com/coding-blocks/creating-user-database-and-adding-access-on-postgresql-8bfcd2f4a91e<br>
    https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps<br>
    Udacity Full stack web development course materials
